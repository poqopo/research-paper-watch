---
type: paper
citekey: "lause2026compoundmodels"
title: "Compound models and Pearson residuals for single-cell RNA-seq data without UMIs."
year: 2026
journal: "Genome Biology"
status: bioflow-analyzed
major_topic: "Single-cell and spatial omics"
subtopics:
  - "Single-cell normalization methods"
doi: "10.1186/s13059-026-04161-4"
pmid: "42365288"
url: "https://doi.org/10.1186/s13059-026-04161-4"
abstract_summary: "Recent work employed Pearson residuals from Poisson or negative binomial models to normalize UMI-based scRNA-seq data. To extend this approach to non-UMI data, we model the amplification step with a compound distribution: we assume that captured RNA molecules follow a negative binomial distribution and are replicated following an amplification distribution. This model leads to compound Pearson residuals, yielding meaningful gene selection and embeddings of Smart-seq2 datasets. Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law. The resulting compound model captures previously unexplained overdispersion and zero-inflation patterns in non-UMI data."
prior_limitations:
  - "기존 Single-cell normalization methods 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다."
solution: "Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law."
differentiator: "Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law."
healthcare_relevance: "주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다."
datasets:
  - "single-cell RNA-seq"
methods:
  - "Single-cell analysis"
topics:
  - "Single-cell and spatial omics"
  - "Single-cell normalization methods"
tags:
  - paper
  - graph-topic
  - major-single-cell-and-spatial-omics
  - subtopic-single-cell-normalization-methods
---
# Compound models and Pearson residuals for single-cell RNA-seq data without UMIs.
## Healthcare relevance
주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
## Analysis
- Abstract: Recent work employed Pearson residuals from Poisson or negative binomial models to normalize UMI-based scRNA-seq data. To extend this approach to non-UMI data, we model the amplification step with a compound distribution: we assume that captured RNA molecules follow a negative binomial distribution and are replicated following an amplification distribution. This model leads to compound Pearson residuals, yielding meaningful gene selection and embeddings of Smart-seq2 datasets. Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law. The resulting compound model captures previously unexplained overdispersion and zero-inflation patterns in non-UMI data.
- Prior limitation: 기존 Single-cell normalization methods 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다.
- Differentiator: Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42365288/), DOI landing page (https://doi.org/10.1186/s13059-026-04161-4).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: Recent work employed Pearson residuals from Poisson or negative binomial models to normalize UMI-based scRNA-seq data.
- Why the problem matters: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
- Prior work baseline: 기존 Single-cell normalization methods 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Single-cell and spatial omics -> Single-cell normalization methods 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: Recent work employed Pearson residuals from Poisson or negative binomial models to normalize UMI-based scRNA-seq data. To extend this approach to non-UMI data, we model the amplification step with a compound distribution: we assume that captured RNA molecules follow a negative binomial distribution and are replicated following an amplification distribution. This model leads to compound Pearson residuals, yielding meaningful gene selection and embeddings of Smart-seq2 datasets. Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law. The resulting compound model captures previously unexplained overdispersion and zero-inflation patterns in non-UMI data.
- Input / cohort / material: single-cell RNA-seq
- Output / endpoint: Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law.
- Expected clinical or biological impact: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
### Methods
- Method type: Single-cell analysis
- Key input: single-cell RNA-seq
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: 기존 Single-cell normalization methods 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다.
- Output: Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law.
- Why this differs from prior methods: Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: single-cell RNA-seq
- Purpose: Single-cell normalization methods branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: 기존 Single-cell normalization methods 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law.
- Main result: Recent work employed Pearson residuals from Poisson or negative binomial models to normalize UMI-based scRNA-seq data. To extend this approach to non-UMI data, we model the amplification step with a compound distribution: we assume that captured RNA molecules follow a negative binomial distribution and are replicated following an amplification distribution. This model leads to compound Pearson residuals, yielding meaningful gene selection and embeddings of Smart-seq2 datasets. Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law. The resulting compound model captures previously unexplained overdispersion and zero-inflation patterns in non-UMI data.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Single-cell and spatial omics 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: Furthermore, we show that amplification distributions across several sequencing protocols can be described by a broken power law.
- Why this matters for healthcare or biology: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Single-cell and spatial omics -> Single-cell normalization methods branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: Genome Biology
- DOI: https://doi.org/10.1186/s13059-026-04161-4
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42365288/
- Article: https://doi.org/10.1186/s13059-026-04161-4
- Journal source: https://link.springer.com/journal/13059
- Secondary journal source: https://genomebiology.biomedcentral.com/
- Screening report: reports/genome-biology/2026-07-07_11-13-00.md
