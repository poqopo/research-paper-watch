---
type: paper
citekey: "bisht2026ovariancpg"
title: "Liquid biopsy-based diagnostic evaluation of hypermethylated CpG sites for ovarian cancer diagnosis."
year: 2026
journal: "Molecular Oncology"
status: bioflow-analyzed
major_topic: "Epigenome"
subtopics:
  - "Cancer liquid biopsy"
doi: "10.1002/1878-0261.70277"
pmid: "42299856"
url: "https://doi.org/10.1002/1878-0261.70277"
abstract_summary: "This ovarian cancer pilot study uses CpG-specific ARMS-PCR to screen six diagnostically relevant CpG sites in 65 epithelial ovarian cancer tissues and 35 healthy controls, then evaluates selected CpG sites in serum cell-free DNA using a TaqMan MethyLight assay. The multiplex MethyLight assay reached 86% sensitivity, 90% specificity, and AUC 0.97 in the serum cohort, supporting hypermethylated/hypomethylated CpG biomarkers as liquid biopsy candidates for ovarian cancer detection."
prior_limitations:
  - "Ovarian cancer lacks reliable early detection biomarkers and is often diagnosed late."
  - "Many candidate methylation biomarkers require translation from tissue discovery to serum cfDNA-compatible assays."
solution: "Screen diagnostically relevant CpG sites in tissue and evaluate selected markers in serum cell-free DNA using MethyLight."
differentiator: "The study compares ARMS-PCR and TaqMan MethyLight readouts and moves selected CpG sites into a serum cfDNA assay."
healthcare_relevance: "Ovarian cancer has a major unmet early-detection need; a serum cfDNA methylation assay could complement imaging and CA-125 if externally validated."
datasets:
  - "65 epithelial ovarian cancer tissues"
  - "35 healthy controls"
  - "Serum cell-free DNA cohort"
methods:
  - "CpG-specific ARMS-PCR"
  - "TaqMan MethyLight assay"
  - "Serum cfDNA methylation analysis"
topics:
  - "Epigenome"
  - "Cancer liquid biopsy"
tags:
  - paper
  - graph-topic
  - major-epigenome
  - subtopic-cancer-liquid-biopsy
---
# Liquid biopsy-based diagnostic evaluation of hypermethylated CpG sites for ovarian cancer diagnosis.

## Healthcare relevance

Ovarian cancer는 reliable screening biomarker가 부족한 대표 암종이다. 이 연구는 serum cfDNA methylation assay로 진단 가능성을 평가하지만, 아직 pilot 수준이라 population screening보다는 biomarker development 단계로 해석해야 한다.

## BioProject-style analysis

### Evidence level

- Source level: PubMed/E-utilities abstract and DOI metadata checked on 2026-07-07.
- Source records: PMID 42299856, DOI 10.1002/1878-0261.70277.
- Missing source material: Full PDF, selected CpG genomic annotations, serum cohort size, stage-specific sensitivity, and validation split details were not extracted.

### Background

- Problem context: Ovarian cancer는 mortality가 높고 조기 발견 biomarker가 충분하지 않다.
- Why the problem matters: early-stage detection이 가능하면 수술 가능성과 생존율 개선 가능성이 있다.
- Prior work baseline: methylation changes are promising, but tissue biomarkers must be adapted to low-input serum cfDNA.
- Gap that remains: candidate CpG sites need serum-compatible assays and independent validation.

### Overview

- Core question: hypermethylated/hypomethylated CpG sites can be translated into a serum cfDNA diagnostic assay for ovarian cancer?
- Paper's framing: tissue screening 후 MethyLight serum cfDNA panel로 diagnostic performance를 평가한다.
- Input / cohort / material: 65 epithelial ovarian cancer tissues, 35 healthy controls, serum cfDNA cohort.
- Output / endpoint: sensitivity, specificity, AUC.
- Expected clinical or biological impact: ovarian cancer liquid biopsy marker panel 후보.

### Methods

- Method type: Targeted CpG methylation liquid biopsy assay development.
- Key input: ovarian cancer tissue, healthy control tissue, serum cfDNA.
- Core processing step: six CpG sites를 ARMS-PCR로 평가하고 top CpG sites를 MethyLight assay로 serum cfDNA에 적용.
- Comparator / baseline: ARMS-PCR singleplex/multiplex panels.
- Output: TaqMan-based MethyLight panel including cg02957270, cg00480298, and Col2A1 endogenous control.
- Why this differs from prior methods: tissue methylation discovery와 serum cfDNA assay translation을 한 study 안에서 연결한다.

### Figures / Tables

- PDF/figure 확인 필요. CpG selection table, assay design, and stage-specific performance require full-text extraction.

### Results

- Tissue evaluation: six CpG sites screened in 65 ovarian cancer tissues and 35 controls.
- ARMS-PCR performance: singleplex/multiplex sensitivities of 80%, 73.3%, and 82.3%.
- Serum MethyLight performance: 86% sensitivity, 90% specificity, AUC 0.97.
- Additional result: MethyLight showed significant clinicopathological correlations (P < 0.05), while ARMS-PCR panels had limited correlations.
- How this supports the claim: serum cfDNA methylation can capture ovarian cancer-associated epigenetic signal with promising diagnostic discrimination.

### Limitations

- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: serum cohort size is not visible in the abstract, and ovarian cancer screening requires extremely high specificity in average-risk settings.
- Missing validation: prospective symptomatic/adnexal mass cohorts, benign gynecologic disease controls, stage I/II sensitivity, and CA-125/HE4 comparison.
- Weak link between evidence and claim: detection promise is supported, but early screening utility remains unproven without broader validation.

### Final Takeaways

- Main takeaway: MethyLight serum cfDNA methylation markers show strong pilot ovarian cancer detection performance.
- Why this matters for healthcare: It addresses a high-need cancer type, but implementation depends on specificity against benign conditions and early-stage sensitivity.
- Next-paper idea: Validate the panel in prediagnostic or adnexal-mass cohorts with CA-125/HE4 comparison.
- Reusable idea for this vault: Use as a targeted CpG assay example distinct from genome-wide cfDNA methylome classifiers.

## Source

- PubMed: https://pubmed.ncbi.nlm.nih.gov/42299856/
- DOI: https://doi.org/10.1002/1878-0261.70277

