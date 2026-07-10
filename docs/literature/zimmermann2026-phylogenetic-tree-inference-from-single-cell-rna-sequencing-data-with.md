---
type: paper
citekey: "zimmermann2026phylogenetictree"
title: "Phylogenetic tree inference from single-cell RNA sequencing data with SCITE-RNA."
year: 2026
journal: "Genome Biology"
status: bioflow-analyzed
major_topic: "Single-cell and spatial omics"
subtopics:
  - "Single-cell lineage inference"
doi: "10.1186/s13059-026-04123-w"
pmid: "42298641"
url: "https://doi.org/10.1186/s13059-026-04123-w"
abstract_summary: "We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input. Our approach uses a maximum-likelihood random-scan greedy search that alternates between cell lineage tree and mutation tree representations to escape local optima until convergence is achieved in both. We demonstrate superior performance on simulated data compared to existing methods. Furthermore, we show its applicability to cancer single-cell RNA sequencing data, where it allows us to link evolutionary trajectories of cells to their gene expression profiles."
prior_limitations:
  - "기존 Single-cell lineage inference 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다."
solution: "We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input."
differentiator: "We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input."
healthcare_relevance: "주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다."
datasets:
  - "Abstract-level source metadata"
methods:
  - "Single-cell analysis"
  - "Phylogenetic inference"
topics:
  - "Single-cell and spatial omics"
  - "Single-cell lineage inference"
tags:
  - paper
  - graph-topic
  - major-single-cell-and-spatial-omics
  - subtopic-single-cell-lineage-inference
---
# Phylogenetic tree inference from single-cell RNA sequencing data with SCITE-RNA.
## Healthcare relevance
주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
## Analysis
- Abstract: We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input. Our approach uses a maximum-likelihood random-scan greedy search that alternates between cell lineage tree and mutation tree representations to escape local optima until convergence is achieved in both. We demonstrate superior performance on simulated data compared to existing methods. Furthermore, we show its applicability to cancer single-cell RNA sequencing data, where it allows us to link evolutionary trajectories of cells to their gene expression profiles.
- Prior limitation: 기존 Single-cell lineage inference 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다.
- Differentiator: We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42298641/), DOI landing page (https://doi.org/10.1186/s13059-026-04123-w).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input.
- Why the problem matters: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
- Prior work baseline: 기존 Single-cell lineage inference 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Single-cell and spatial omics -> Single-cell lineage inference 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input. Our approach uses a maximum-likelihood random-scan greedy search that alternates between cell lineage tree and mutation tree representations to escape local optima until convergence is achieved in both. We demonstrate superior performance on simulated data compared to existing methods. Furthermore, we show its applicability to cancer single-cell RNA sequencing data, where it allows us to link evolutionary trajectories of cells to their gene expression profiles.
- Input / cohort / material: Abstract-level source metadata
- Output / endpoint: We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input.
- Expected clinical or biological impact: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
### Methods
- Method type: Single-cell analysis, Phylogenetic inference
- Key input: Abstract-level source metadata
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: 기존 Single-cell lineage inference 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다.
- Output: We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input.
- Why this differs from prior methods: We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: Abstract-level source metadata
- Purpose: Single-cell lineage inference branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: 기존 Single-cell lineage inference 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input.
- Main result: We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input. Our approach uses a maximum-likelihood random-scan greedy search that alternates between cell lineage tree and mutation tree representations to escape local optima until convergence is achieved in both. We demonstrate superior performance on simulated data compared to existing methods. Furthermore, we show its applicability to cancer single-cell RNA sequencing data, where it allows us to link evolutionary trajectories of cells to their gene expression profiles.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Single-cell and spatial omics 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: We present SCITE-RNA, a novel phylogenetic tree inference method designed for single-cell RNA sequencing data which takes reference and alternative read counts of single-nucleotide variants as input.
- Why this matters for healthcare or biology: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Single-cell and spatial omics -> Single-cell lineage inference branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: Genome Biology
- DOI: https://doi.org/10.1186/s13059-026-04123-w
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42298641/
- Article: https://doi.org/10.1186/s13059-026-04123-w
- Journal source: https://link.springer.com/journal/13059
- Secondary journal source: https://genomebiology.biomedcentral.com/
- Screening report: reports/genome-biology/2026-07-07_11-13-00.md
