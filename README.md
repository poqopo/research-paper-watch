# Research Paper Agent

Local-first literature agent for this Obsidian-compatible `papers/` vault.

The vault stores paper notes as Markdown and generates three static HTML views:

- `Research Paper Explorer.html`: topic and subtopic explorer.
- `Research Paper List.html`: recent-order paper list with journal filtering.
- `Research Idea Forecaster.html`: high-priority next-paper idea view.

## Requirements

- Node.js 18 or newer.
- Python 3 for journal-watch scanner scripts and local serving.
- Codex skills installed when running journal screening from the bundled scanner paths.

No npm dependencies are required for the current local build.

## Quick Start

From this `papers/` folder:

```bash
npm run validate
npm run build
npm run serve
```

Then open:

```text
http://127.0.0.1:8765/Research%20Paper%20Explorer.html
```

From the workspace root, use:

```bash
npm --prefix papers run validate
npm --prefix papers run build
```

## Main Commands

```bash
npm run build      # regenerate all HTML/data outputs from Markdown
npm run validate   # syntax, contract, and generated-output checks
npm run journals   # print enabled watched journals and scanner paths
npm run daily      # scan watched journals, rebuild outputs, validate links
npm run export     # create a shareable bundle under ../exports/
npm run pages:build # build a GitHub Pages-ready site under docs/
npm run serve      # serve this vault locally at http://127.0.0.1:8765
```

## GitHub Pages Site

Build a static site that keeps the same interactive HTML experience as the local generated files:

```bash
npm run pages:build
```

This writes a GitHub Pages-ready bundle to `docs/`:

```text
docs/index.html      # main landing page
docs/explorer/       # Research Paper Explorer
docs/papers/         # Research Paper List
docs/ideas/          # Research Idea Forecaster
```

If this folder is committed to a GitHub repository, set GitHub Pages to deploy from the `docs/` folder on the target branch. The main page then routes to `/explorer/`, `/papers/`, and `/ideas/`. Telegram can send the Pages URL as a short link, while the daily cron message stays focused on newly detected papers.

The Pages bundle also copies Markdown source notes under `docs/literature/`, `docs/topics/`, and `docs/ideas/` so the generated "Open source MD" links do not break. Do not publish `docs/` to a public repository if those Markdown notes should remain private.

## Agent Commands

The agent layer keeps state and review queues on top of the harness commands:

```bash
npm run agent:status   # summarize agent state and queue counts
npm run agent:plan -- queue
npm run agent:plan -- autonomous
npm run agent:skills
npm run agent:policy
npm run agent:daily    # scan journals, refresh review queue, keep imports gated
npm run agent:reason   # run LLM reasoning methods or deterministic fallback
npm run agent:autonomous -- --dry-run
npm run agent:autonomous
npm run agent:daily-auto
npm run agent:queue    # refresh candidates from latest existing reports only
npm run agent:review   # write agent/review_queue/REVIEW.md
npm run agent:accept   # manual fallback: import approved accepted.json entries
npm run agent:build    # build and validate through the agent
npm run agent:export   # export through the agent
```

Candidate discovery and autonomous import are policy controlled. `agent:autonomous` refreshes candidates, reasons over them, promotes import decisions, imports papers, rebuilds outputs, and validates. Use `--dry-run` to inspect what would be imported without changing paper notes.

Manual fallback is still available: add selected IDs to `agent/review_queue/accepted.json` with `approved: true`, `major_topic`, and `subtopics`, then run `npm run agent:accept`.

## OpenClaw Telegram Cron

OpenClaw can run the daily paper agent as a Gateway cron command and deliver the command output to Telegram.

Preview the message locally:

```bash
npm run openclaw:daily-report
```

Install an 08:00 Asia/Seoul daily OpenClaw cron job:

```bash
OPENCLAW_TELEGRAM_TO=<telegram-user-or-chat-id> npm run openclaw:cron:install
```

The default cron mode is `dry-run`: it scans journals, refreshes reasoning, and sends a summary without importing papers. To allow autonomous imports that pass policy gates:

```bash
OPENCLAW_TELEGRAM_TO=<telegram-user-or-chat-id> \
OPENCLAW_PAPER_AGENT_MODE=import \
npm run openclaw:cron:install
```

Optional settings:

```bash
OPENCLAW_PAPER_CRON_SCHEDULE="0 8 * * *"
OPENCLAW_PAPER_CRON_TZ="Asia/Seoul"
OPENCLAW_PAPER_REPORT_MAX=5
OPENCLAW_PAPER_ATTACH_HTML=1
OPENCLAW_PAPER_BUILD_PAGES=1
OPENCLAW_PAPER_PUBLISH_PAGES=1
OPENCLAW_PAPER_PAGES_URL="https://<user>.github.io/<repo>/"
OPENCLAW_TELEGRAM_THREAD_ID=42
```

When `OPENCLAW_PAPER_ATTACH_HTML=1`, daily cron sends only the newly detected candidate report when there are new candidates in that run. To receive the full static HTML exports on demand, send `html 다시 보내줘` in Telegram:

- `Research Paper Explorer.static.html`
- `Research Paper List.static.html`
- `Research Idea Forecaster.static.html`

The text summary also includes a short research-trend brief based on the current candidate topic distribution.

By default `OPENCLAW_PAPER_BUILD_PAGES=1`, so the cron run refreshes `docs/` after the paper agent updates the generated HTML. Set `OPENCLAW_PAPER_PUBLISH_PAGES=1` to commit and push changed `docs/` files to the configured `origin` remote. If `OPENCLAW_PAPER_PAGES_URL` is set, the daily Telegram summary appends that URL as the full-view link.

Telegram command replies are handled by a deterministic bridge, not by arbitrary shell execution. Supported messages:

```text
반영해줘
상태
html 다시 보내줘
DNA methylation rare disease 추가조사해줘
도움말
```

`반영해줘` runs the import-enabled paper-agent path, then sends the short summary plus a new-item report when new candidates are present.
`<주제> 추가조사해줘` searches recent PubMed records for that topic, writes an abstract-level analysis report under `reports/topic-research/`, and sends the Markdown report to Telegram. It does not import papers into the vault.

The agent loop and skill wiring live in:

```text
agent/policies/react-loop-policy.json
agent/policies/loop-engineering-policy.json
agent/policies/skills-policy.json
agent/policies/skill-update-policy.json
agent/policies/llm-reasoning-policy.json
agent/reasoning_methods/
```

## Configure

Edit files under `config/`:

- `journals.json`: watched journals and scanner scripts.
- `topics.json`: topic graph and classification policy.
- `scoring.json`: idea forecaster thresholds and labels.
- `output.json`: generated output paths and UI behavior.

See `config/README.md` for journal addition and scoring examples.

## Agent Contract

The reusable workflow contract is:

```text
agent/AGENT_CONTRACT.md
```

Machine-readable metadata is:

```text
agent/agent-contract.json
```

Run:

```bash
npm run validate:contract
```

## Source Of Truth

Markdown is canonical:

```text
literature/*.md
topics/*.md
topics/Major topics.md
```

HTML and JSON files are generated from those notes.
