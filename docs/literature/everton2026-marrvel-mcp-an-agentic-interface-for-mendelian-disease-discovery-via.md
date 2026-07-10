---
type: paper
citekey: "everton2026marrvelmcp"
title: "MARRVEL-MCP: An agentic interface for Mendelian disease discovery via tool-augmented context engineering."
year: 2026
journal: "The American Journal of Human Genetics"
status: bioflow-analyzed
major_topic: "Rare disease"
subtopics:
  - "Variant ranking"
doi: "10.1016/j.ajhg.2026.04.012"
pmid: "42167217"
url: "https://doi.org/10.1016/j.ajhg.2026.04.012"
abstract_summary: "Variant interpretation in rare diseases requires navigating multiple genomic databases, each with strict input formats, while synthesizing heterogeneous evidence. This process creates significant barriers for non-experts and imposes a substantial cognitive burden on experienced specialists. These challenges are evident in tools such as model organism aggregated resources for rare variant exploration (MARRVEL), which require precise variant formatting (e.g., Human Genome Variation Society [HGVS] notation) and return complex, heterogeneous outputs. To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access. This work demonstrates the impact of tool-augmented context engineering, the purposeful design of domain-aware tool environments and structured information scaffolding through executable function interfaces, on reshaping the role of model scale in genomics. MARRVEL-MCP equips LLMs with 44 tools spanning gene and variant utilities, pathogenicity databases, phenotype resources, expression atlases, ortholog data, and literature APIs. Without hard-coded workflows, LLMs infer which tools to invoke and in what sequence, performing named-entity recognition, identifier normalization, and multi-database synthesis from clinical queries. Using 100 expert-curated questions, lightweight models (3B-20B parameters) with MARRVEL-MCP matched or outperformed larger models without tool access. A 20B-parameter model (gpt-oss-20b) achieved a 94% pass rate, versus 41% without MARRVEL-MCP, approaching state-of-the-art proprietary performance. Although expert oversight remains essential and tool use adds cost, these results show that contextual guidance can compensate for limited model capacity. These findings establish context engineering as a core principle for biomedical AI and support scalable integration of LLMs with curated genomic resources."
prior_limitations:
  - "Although expert oversight remains essential and tool use adds cost, these results show that contextual guidance can compensate for limited model capacity."
solution: "To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access."
differentiator: "To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access."
healthcare_relevance: "희귀질환 진단, 병인 유전자 해석, 변이 우선순위화, 또는 환자 관리 의사결정에 직접 연결될 수 있다."
datasets:
  - "Abstract-level source metadata"
methods:
  - "Large language model"
topics:
  - "Rare disease"
  - "Variant ranking"
tags:
  - paper
  - graph-topic
  - major-rare-disease
  - subtopic-variant-ranking
---
# MARRVEL-MCP: An agentic interface for Mendelian disease discovery via tool-augmented context engineering.
## Healthcare relevance
희귀질환 진단, 병인 유전자 해석, 변이 우선순위화, 또는 환자 관리 의사결정에 직접 연결될 수 있다.
## Analysis
- Abstract: Variant interpretation in rare diseases requires navigating multiple genomic databases, each with strict input formats, while synthesizing heterogeneous evidence. This process creates significant barriers for non-experts and imposes a substantial cognitive burden on experienced specialists. These challenges are evident in tools such as model organism aggregated resources for rare variant exploration (MARRVEL), which require precise variant formatting (e.g., Human Genome Variation Society [HGVS] notation) and return complex, heterogeneous outputs. To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access. This work demonstrates the impact of tool-augmented context engineering, the purposeful design of domain-aware tool environments and structured information scaffolding through executable function interfaces, on reshaping the role of model scale in genomics. MARRVEL-MCP equips LLMs with 44 tools spanning gene and variant utilities, pathogenicity databases, phenotype resources, expression atlases, ortholog data, and literature APIs. Without hard-coded workflows, LLMs infer which tools to invoke and in what sequence, performing named-entity recognition, identifier normalization, and multi-database synthesis from clinical queries. Using 100 expert-curated questions, lightweight models (3B-20B parameters) with MARRVEL-MCP matched or outperformed larger models without tool access. A 20B-parameter model (gpt-oss-20b) achieved a 94% pass rate, versus 41% without MARRVEL-MCP, approaching state-of-the-art proprietary performance. Although expert oversight remains essential and tool use adds cost, these results show that contextual guidance can compensate for limited model capacity. These findings establish context engineering as a core principle for biomedical AI and support scalable integration of LLMs with curated genomic resources.
- Prior limitation: Although expert oversight remains essential and tool use adds cost, these results show that contextual guidance can compensate for limited model capacity.
- Differentiator: To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42167217/), DOI landing page (https://doi.org/10.1016/j.ajhg.2026.04.012).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: Variant interpretation in rare diseases requires navigating multiple genomic databases, each with strict input formats, while synthesizing heterogeneous evidence.
- Why the problem matters: 희귀질환 진단, 병인 유전자 해석, 변이 우선순위화, 또는 환자 관리 의사결정에 직접 연결될 수 있다.
- Prior work baseline: Although expert oversight remains essential and tool use adds cost, these results show that contextual guidance can compensate for limited model capacity.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Rare disease -> Variant ranking 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: Variant interpretation in rare diseases requires navigating multiple genomic databases, each with strict input formats, while synthesizing heterogeneous evidence. This process creates significant barriers for non-experts and imposes a substantial cognitive burden on experienced specialists. These challenges are evident in tools such as model organism aggregated resources for rare variant exploration (MARRVEL), which require precise variant formatting (e.g., Human Genome Variation Society [HGVS] notation) and return complex, heterogeneous outputs. To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access. This work demonstrates the impact of tool-augmented context engineering, the purposeful design of domain-aware tool environments and structured information scaffolding through executable function interfaces, on reshaping the role of model scale in genomics. MARRVEL-MCP equips LLMs with 44 tools spanning gene and variant utilities, pathogenicity databases, phenotype resources, expression atlases, ortholog data, and literature APIs. Without hard-coded workflows, LLMs infer which tools to invoke and in what sequence, performing named-entity recognition, identifier normalization, and multi-database synthesis from clinical queries. Using 100 expert-curated questions, lightweight models (3B-20B parameters) with MARRVEL-MCP matched or outperformed larger models without tool access. A 20B-parameter model (gpt-oss-20b) achieved a 94% pass rate, versus 41% without MARRVEL-MCP, approaching state-of-the-art proprietary performance. Although expert oversight remains essential and tool use adds cost, these results show that contextual guidance can compensate for limited model capacity. These findings establish context engineering as a core principle for biomedical AI and support scalable integration of LLMs with curated genomic resources.
- Input / cohort / material: Abstract-level source metadata
- Output / endpoint: To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access.
- Expected clinical or biological impact: 희귀질환 진단, 병인 유전자 해석, 변이 우선순위화, 또는 환자 관리 의사결정에 직접 연결될 수 있다.
### Methods
- Method type: Large language model
- Key input: Abstract-level source metadata
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: Although expert oversight remains essential and tool use adds cost, these results show that contextual guidance can compensate for limited model capacity.
- Output: To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access.
- Why this differs from prior methods: To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: Abstract-level source metadata
- Purpose: Variant ranking branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: Although expert oversight remains essential and tool use adds cost, these results show that contextual guidance can compensate for limited model capacity.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access.
- Main result: Variant interpretation in rare diseases requires navigating multiple genomic databases, each with strict input formats, while synthesizing heterogeneous evidence. This process creates significant barriers for non-experts and imposes a substantial cognitive burden on experienced specialists. These challenges are evident in tools such as model organism aggregated resources for rare variant exploration (MARRVEL), which require precise variant formatting (e.g., Human Genome Variation Society [HGVS] notation) and return complex, heterogeneous outputs. To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access. This work demonstrates the impact of tool-augmented context engineering, the purposeful design of domain-aware tool environments and structured information scaffolding through executable function interfaces, on reshaping the role of model scale in genomics. MARRVEL-MCP equips LLMs with 44 tools spanning gene and variant utilities, pathogenicity databases, phenotype resources, expression atlases, ortholog data, and literature APIs. Without hard-coded workflows, LLMs infer which tools to invoke and in what sequence, performing named-entity recognition, identifier normalization, and multi-database synthesis from clinical queries. Using 100 expert-curated questions, lightweight models (3B-20B parameters) with MARRVEL-MCP matched or outperformed larger models without tool access. A 20B-parameter model (gpt-oss-20b) achieved a 94% pass rate, versus 41% without MARRVEL-MCP, approaching state-of-the-art proprietary performance. Although expert oversight remains essential and tool use adds cost, these results show that contextual guidance can compensate for limited model capacity. These findings establish context engineering as a core principle for biomedical AI and support scalable integration of LLMs with curated genomic resources.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Rare disease 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: To address these usability barriers, we developed MARRVEL-MCP, a natural-language interface that enables large language models (LLMs) to perform end-to-end variant interpretation via structured tool access.
- Why this matters for healthcare or biology: 희귀질환 진단, 병인 유전자 해석, 변이 우선순위화, 또는 환자 관리 의사결정에 직접 연결될 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Rare disease -> Variant ranking branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: The American Journal of Human Genetics
- DOI: https://doi.org/10.1016/j.ajhg.2026.04.012
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42167217/
- Article: https://doi.org/10.1016/j.ajhg.2026.04.012
- Journal source: https://www.sciencedirect.com/journal/the-american-journal-of-human-genetics
- Secondary journal source: https://www.cell.com/AJHG/home
- Screening report: reports/ajhg/2026-07-07_11-13-00.md
