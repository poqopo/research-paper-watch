---
type: paper
citekey: "kang2026aflexible"
title: "A flexible and unified framework for single- and multi-outcome Mendelian randomization using summary statistics."
year: 2026
journal: "The American Journal of Human Genetics"
status: bioflow-analyzed
major_topic: "Statistical genetics"
subtopics:
  - "GWAS disease genetics"
doi: "10.1016/j.ajhg.2026.03.017"
pmid: "41997142"
url: "https://doi.org/10.1016/j.ajhg.2026.03.017"
abstract_summary: "Mendelian randomization (MR) is widely used to evaluate causal effects of complex trait exposures on disease outcomes. Recently, MR has been increasingly applied to molecular traits, such as gene expression, to map risk genes. However, transcriptome-wide MR (TWMR) faces unique challenges. The number of available cis-QTLs as instrumental variables (IVs) is often limited, and horizontal pleiotropy is pervasive, violating core MR assumptions and compromising inference validity. We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures. Our single-outcome model, FusioMRs, incorporates gene-region-specific empirical priors informed by the number and strength of QTLs, linkage disequilibrium, and effect size consistency. It uses sampling-based inference to improve robustness when instruments are limited. Our multi-outcome model, FusioMRm, is motivated by the observation that many complex diseases have correlated diseases, subtypes, or comorbidities, which could be affected by shared or correlated exposures. FusioMRm jointly analyzes two correlated outcomes, leveraging shared IVs and pleiotropic effects of shared/correlated exposures to improve estimation precision and power, particularly for underpowered outcomes. We applied FusioMRs to identify cell-type-specific gene expression traits associated with Alzheimer disease using single-cell eQTL and GWAS summary data. We applied FusioMRm to detect alternative polyadenylation events affecting atrial fibrillation and ischemic stroke, and to estimate the causal effect of low-density lipoprotein on ischemic stroke in South Asian populations by borrowing information from European ancestry data. These applications highlight the generalizability of FusioMR for both molecular and complex trait exposures."
prior_limitations:
  - "However, transcriptome-wide MR (TWMR) faces unique challenges."
solution: "We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures."
differentiator: "We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures."
healthcare_relevance: "질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다."
datasets:
  - "Abstract-level source metadata"
methods:
  - "Single-cell analysis"
  - "GWAS"
  - "Mendelian randomization"
  - "Transcriptomics"
topics:
  - "Statistical genetics"
  - "GWAS disease genetics"
tags:
  - paper
  - graph-topic
  - major-statistical-genetics
  - subtopic-gwas-disease-genetics
---
# A flexible and unified framework for single- and multi-outcome Mendelian randomization using summary statistics.
## Healthcare relevance
질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
## Analysis
- Abstract: Mendelian randomization (MR) is widely used to evaluate causal effects of complex trait exposures on disease outcomes. Recently, MR has been increasingly applied to molecular traits, such as gene expression, to map risk genes. However, transcriptome-wide MR (TWMR) faces unique challenges. The number of available cis-QTLs as instrumental variables (IVs) is often limited, and horizontal pleiotropy is pervasive, violating core MR assumptions and compromising inference validity. We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures. Our single-outcome model, FusioMRs, incorporates gene-region-specific empirical priors informed by the number and strength of QTLs, linkage disequilibrium, and effect size consistency. It uses sampling-based inference to improve robustness when instruments are limited. Our multi-outcome model, FusioMRm, is motivated by the observation that many complex diseases have correlated diseases, subtypes, or comorbidities, which could be affected by shared or correlated exposures. FusioMRm jointly analyzes two correlated outcomes, leveraging shared IVs and pleiotropic effects of shared/correlated exposures to improve estimation precision and power, particularly for underpowered outcomes. We applied FusioMRs to identify cell-type-specific gene expression traits associated with Alzheimer disease using single-cell eQTL and GWAS summary data. We applied FusioMRm to detect alternative polyadenylation events affecting atrial fibrillation and ischemic stroke, and to estimate the causal effect of low-density lipoprotein on ischemic stroke in South Asian populations by borrowing information from European ancestry data. These applications highlight the generalizability of FusioMR for both molecular and complex trait exposures.
- Prior limitation: However, transcriptome-wide MR (TWMR) faces unique challenges.
- Differentiator: We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/41997142/), DOI landing page (https://doi.org/10.1016/j.ajhg.2026.03.017).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: Mendelian randomization (MR) is widely used to evaluate causal effects of complex trait exposures on disease outcomes.
- Why the problem matters: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Prior work baseline: However, transcriptome-wide MR (TWMR) faces unique challenges.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Statistical genetics -> GWAS disease genetics 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: Mendelian randomization (MR) is widely used to evaluate causal effects of complex trait exposures on disease outcomes. Recently, MR has been increasingly applied to molecular traits, such as gene expression, to map risk genes. However, transcriptome-wide MR (TWMR) faces unique challenges. The number of available cis-QTLs as instrumental variables (IVs) is often limited, and horizontal pleiotropy is pervasive, violating core MR assumptions and compromising inference validity. We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures. Our single-outcome model, FusioMRs, incorporates gene-region-specific empirical priors informed by the number and strength of QTLs, linkage disequilibrium, and effect size consistency. It uses sampling-based inference to improve robustness when instruments are limited. Our multi-outcome model, FusioMRm, is motivated by the observation that many complex diseases have correlated diseases, subtypes, or comorbidities, which could be affected by shared or correlated exposures. FusioMRm jointly analyzes two correlated outcomes, leveraging shared IVs and pleiotropic effects of shared/correlated exposures to improve estimation precision and power, particularly for underpowered outcomes. We applied FusioMRs to identify cell-type-specific gene expression traits associated with Alzheimer disease using single-cell eQTL and GWAS summary data. We applied FusioMRm to detect alternative polyadenylation events affecting atrial fibrillation and ischemic stroke, and to estimate the causal effect of low-density lipoprotein on ischemic stroke in South Asian populations by borrowing information from European ancestry data. These applications highlight the generalizability of FusioMR for both molecular and complex trait exposures.
- Input / cohort / material: Abstract-level source metadata
- Output / endpoint: We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures.
- Expected clinical or biological impact: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
### Methods
- Method type: Single-cell analysis, GWAS, Mendelian randomization, Transcriptomics
- Key input: Abstract-level source metadata
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: However, transcriptome-wide MR (TWMR) faces unique challenges.
- Output: We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures.
- Why this differs from prior methods: We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: Abstract-level source metadata
- Purpose: GWAS disease genetics branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: However, transcriptome-wide MR (TWMR) faces unique challenges.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures.
- Main result: Mendelian randomization (MR) is widely used to evaluate causal effects of complex trait exposures on disease outcomes. Recently, MR has been increasingly applied to molecular traits, such as gene expression, to map risk genes. However, transcriptome-wide MR (TWMR) faces unique challenges. The number of available cis-QTLs as instrumental variables (IVs) is often limited, and horizontal pleiotropy is pervasive, violating core MR assumptions and compromising inference validity. We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures. Our single-outcome model, FusioMRs, incorporates gene-region-specific empirical priors informed by the number and strength of QTLs, linkage disequilibrium, and effect size consistency. It uses sampling-based inference to improve robustness when instruments are limited. Our multi-outcome model, FusioMRm, is motivated by the observation that many complex diseases have correlated diseases, subtypes, or comorbidities, which could be affected by shared or correlated exposures. FusioMRm jointly analyzes two correlated outcomes, leveraging shared IVs and pleiotropic effects of shared/correlated exposures to improve estimation precision and power, particularly for underpowered outcomes. We applied FusioMRs to identify cell-type-specific gene expression traits associated with Alzheimer disease using single-cell eQTL and GWAS summary data. We applied FusioMRm to detect alternative polyadenylation events affecting atrial fibrillation and ischemic stroke, and to estimate the causal effect of low-density lipoprotein on ischemic stroke in South Asian populations by borrowing information from European ancestry data. These applications highlight the generalizability of FusioMR for both molecular and complex trait exposures.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Statistical genetics 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: We introduce FusioMR, a robust MR framework tailored for molecular trait exposures while also applicable to complex trait exposures.
- Why this matters for healthcare or biology: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Statistical genetics -> GWAS disease genetics branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: The American Journal of Human Genetics
- DOI: https://doi.org/10.1016/j.ajhg.2026.03.017
- PubMed: https://pubmed.ncbi.nlm.nih.gov/41997142/
- Article: https://doi.org/10.1016/j.ajhg.2026.03.017
- Journal source: https://www.sciencedirect.com/journal/the-american-journal-of-human-genetics
- Secondary journal source: https://www.cell.com/AJHG/home
- Screening report: reports/ajhg/2026-07-07_11-13-00.md
