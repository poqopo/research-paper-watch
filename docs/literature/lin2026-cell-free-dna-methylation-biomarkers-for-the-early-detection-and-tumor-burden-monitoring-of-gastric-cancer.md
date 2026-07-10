---
type: paper
citekey: "lin2026gcmlscore"
title: "Cell-free DNA methylation biomarkers for the early detection and tumor burden monitoring of gastric cancer."
year: 2026
journal: "NPJ Precision Oncology"
status: bioflow-analyzed
major_topic: "Epigenome"
subtopics:
  - "Cancer liquid biopsy"
doi: "10.1038/s41698-026-01525-8"
pmid: "42230944"
url: "https://doi.org/10.1038/s41698-026-01525-8"
abstract_summary: "This gastric cancer study performs genome-wide methylation sequencing on 78 tissue and 241 plasma samples from 171 gastric cancer patients and 114 healthy controls across two clinical centers. Paired tumor/normal tissue DMRs were refined through cfDNA profiles and LASSO regression into a 13-DMR GCML-score. The score achieved overall AUCs of 0.95, 0.99, and 0.95, and early gastric cancer AUCs of 0.96, 0.99, and 0.82 in training, internal validation, and external validation. In 12 neoadjuvant chemotherapy patients, dynamic GCML-score changes tracked radiological tumor burden."
prior_limitations:
  - "Gastric cancer early detection lacks sensitive noninvasive biomarkers."
  - "Markers discovered in tissue do not always translate robustly to plasma cfDNA."
solution: "Use tissue-paired DMR discovery and cfDNA refinement to construct a 13-DMR GCML-score for gastric cancer early detection and tumor burden monitoring."
differentiator: "The study connects early detection and longitudinal tumor burden monitoring using one cfDNA methylation score."
healthcare_relevance: "A cfDNA methylation score for gastric cancer could support noninvasive early detection and response monitoring, especially where endoscopy access is limited."
datasets:
  - "78 tissue samples"
  - "241 plasma samples"
  - "171 gastric cancer patients"
  - "114 healthy controls"
  - "Two independent clinical centers"
  - "12 neoadjuvant chemotherapy monitoring patients"
methods:
  - "Genome-wide methylation sequencing"
  - "DMR screening"
  - "cfDNA methylation profiling"
  - "LASSO regression"
  - "Longitudinal tumor burden monitoring"
topics:
  - "Epigenome"
  - "Cancer liquid biopsy"
tags:
  - paper
  - graph-topic
  - major-epigenome
  - subtopic-cancer-liquid-biopsy
---
# Cell-free DNA methylation biomarkers for the early detection and tumor burden monitoring of gastric cancer.

## Healthcare relevance

Gastric cancer는 조기 발견 시 치료 가능성이 커지지만 endoscopy 기반 선별검사는 비용/접근성 제약이 있다. 이 연구의 GCML-score는 blood-based early detection과 치료 중 tumor burden monitoring을 동시에 겨냥한다.

## BioProject-style analysis

### Evidence level

- Source level: PubMed/E-utilities abstract and DOI metadata checked on 2026-07-07.
- Source records: PMID 42230944, DOI 10.1038/s41698-026-01525-8.
- Missing source material: Full PDF, DMR genomic coordinates, LASSO details, exact cohort split, and radiology correlation plots were not extracted.

### Background

- Problem context: Gastric cancer는 초기 증상이 비특이적이라 late-stage diagnosis가 흔하다.
- Why the problem matters: blood-based assay는 endoscopy를 보완하거나 risk-based triage에 쓰일 수 있다.
- Prior work baseline: tissue methylation biomarkers are abundant, but cfDNA-compatible and externally validated panels are harder.
- Gap that remains: early GC detection과 longitudinal monitoring을 같은 methylation score로 연결하는 evidence가 필요했다.

### Overview

- Core question: tissue-derived and cfDNA-refined methylation DMRs can support early gastric cancer detection and tumor burden monitoring?
- Paper's framing: genome-wide methylation sequencing에서 DMR을 찾고 LASSO로 cfDNA GCML-score를 만든다.
- Input / cohort / material: 78 tissue and 241 plasma samples from 171 GC patients and 114 controls.
- Output / endpoint: overall and early-GC AUC, neoadjuvant therapy monitoring consistency.
- Expected clinical or biological impact: gastric cancer screening/triage and response monitoring.

### Methods

- Method type: cfDNA methylation biomarker discovery and validation.
- Key input: paired GC/normal tissues, plasma cfDNA profiles.
- Core processing step: DMRs were screened from paired tissue, refined through cfDNA profiles, and selected by LASSO into a 13-DMR score.
- Comparator / baseline: full text 확인 필요 for comparison against CA markers, endoscopy, or other methylation panels.
- Output: GCML-score.
- Why this differs from prior methods: the score is evaluated for both detection and dynamic burden monitoring.

### Figures / Tables

- PDF/figure 확인 필요. ROC curves, center-specific performance, early-stage counts, and longitudinal trajectories need full-text extraction.

### Results

- Discovery/validation material: 78 tissue and 241 plasma samples.
- Cohort: 171 GC patients and 114 healthy controls from two independent clinical centers.
- Overall AUC: 0.95 training, 0.99 internal validation, 0.95 external validation.
- Early GC AUC: 0.96 training, 0.99 internal validation, 0.82 external validation.
- Monitoring: in 12 neoadjuvant chemotherapy patients, GCML-score dynamics were consistent with radiological tumor burden.
- How this supports the claim: methylation signals selected from tissue and refined in cfDNA remain detectable in plasma and carry both diagnostic and burden information.

### Limitations

- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: early GC external AUC drops to 0.82, suggesting performance may be cohort-sensitive.
- Missing validation: prospective screening, benign gastric disease controls, Helicobacter/inflammation confounding, and endoscopy-comparator utility.
- Weak link between evidence and claim: monitoring result is promising but based on only 12 neoadjuvant chemotherapy patients.

### Final Takeaways

- Main takeaway: GCML-score is a strong recent gastric cfDNA methylation candidate because it links early detection with treatment monitoring.
- Why this matters for healthcare: it could help triage high-risk gastric cancer populations, but prospective screening evidence is still needed.
- Next-paper idea: Validate GCML-score in high-risk gastritis/metaplasia cohorts and compare against endoscopy-driven outcomes.
- Reusable idea for this vault: Use as the gastric cancer counterpart to HCC and CRC cfDNA methylation early-detection studies.

## Source

- PubMed: https://pubmed.ncbi.nlm.nih.gov/42230944/
- DOI: https://doi.org/10.1038/s41698-026-01525-8

