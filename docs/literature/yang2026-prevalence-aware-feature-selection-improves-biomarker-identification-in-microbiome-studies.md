---
type: paper
citekey: "yang2026prevalenceaware"
title: "Prevalence aware feature selection improves biomarker identification in microbiome studies."
year: 2026
journal: "Bioinformatics"
status: bioflow-analyzed
major_topic: "Microbiome genetics"
subtopics:
  - "Metagenomic health prediction"
doi: "10.1093/bioinformatics/btag371"
pmid: "42340677"
url: "https://doi.org/10.1093/bioinformatics/btag371"
abstract_summary: "MOTIVATION: Identifying robust microbial biomarkers is crucial for disease diagnosis and prediction, elucidation of biological mechanisms, and development of targeted therapies. Machine learning-based approaches, particularly the random forest model, have been widely used for biomarker identification during sample stratification. However, those biomarkers often vary considerably for the same disease, limiting their practical applicability. A robust framework for reliable biomarker identification in microbiome research is needed. To address this gap, we proposed a prevalence-aware feature selection framework (ParSlet) that incorporates a universal scaling relationship between taxon prevalence and selection frequency. RESULTS: We first identified a universal exponential scaling law linking the probability of a taxon being consistently recognized as a biomarker versus its prevalence. Then, we integrated this scaling law with taxa prevalence into the biomarker identification using random forest. We systematically evaluated this approach in both simulated microbiome datasets and real-world microbiome datasets and compared it with existing methods, finding that our integrated approach generally improved feature stability and reproducibility of biomarker identification. In colorectal cancer (CRC) datasets, our method robustly identified well-established microbial biomarkers such as Ruminococcus, Clostridium_XVIII, and Faecalibacterium. Integrating a prevalence-based scaling adjustment into feature importance enhances the stability of microbiome biomarker identification. This approach holds promise for enabling more reliable disease diagnostics, uncovering generalizable microbial signatures across cohorts, and guiding the development of targeted microbiome-based interventions. AVAILABILITY AND IMPLEMENTATION: ParSlet is available at https://github.com/KelabatOSU/Feature_selection."
prior_limitations:
  - "However, those biomarkers often vary considerably for the same disease, limiting their practical applicability."
solution: "Prevalence aware feature selection improves biomarker identification in microbiome studies. 논문은 Metagenomic health prediction 문제를 Microbiome genetics 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다."
differentiator: "Prevalence aware feature selection improves biomarker identification in microbiome studies. 논문은 Metagenomic health prediction 문제를 Microbiome genetics 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다."
healthcare_relevance: "질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다."
datasets:
  - "microbiome studies"
methods:
  - "Machine learning"
  - "Microbiome biomarker analysis"
topics:
  - "Microbiome genetics"
  - "Metagenomic health prediction"
tags:
  - paper
  - graph-topic
  - major-microbiome-genetics
  - subtopic-metagenomic-health-prediction
---
# Prevalence aware feature selection improves biomarker identification in microbiome studies.
## Healthcare relevance
질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
## Analysis
- Abstract: MOTIVATION: Identifying robust microbial biomarkers is crucial for disease diagnosis and prediction, elucidation of biological mechanisms, and development of targeted therapies. Machine learning-based approaches, particularly the random forest model, have been widely used for biomarker identification during sample stratification. However, those biomarkers often vary considerably for the same disease, limiting their practical applicability. A robust framework for reliable biomarker identification in microbiome research is needed. To address this gap, we proposed a prevalence-aware feature selection framework (ParSlet) that incorporates a universal scaling relationship between taxon prevalence and selection frequency. RESULTS: We first identified a universal exponential scaling law linking the probability of a taxon being consistently recognized as a biomarker versus its prevalence. Then, we integrated this scaling law with taxa prevalence into the biomarker identification using random forest. We systematically evaluated this approach in both simulated microbiome datasets and real-world microbiome datasets and compared it with existing methods, finding that our integrated approach generally improved feature stability and reproducibility of biomarker identification. In colorectal cancer (CRC) datasets, our method robustly identified well-established microbial biomarkers such as Ruminococcus, Clostridium_XVIII, and Faecalibacterium. Integrating a prevalence-based scaling adjustment into feature importance enhances the stability of microbiome biomarker identification. This approach holds promise for enabling more reliable disease diagnostics, uncovering generalizable microbial signatures across cohorts, and guiding the development of targeted microbiome-based interventions. AVAILABILITY AND IMPLEMENTATION: ParSlet is available at https://github.com/KelabatOSU/Feature_selection.
- Prior limitation: However, those biomarkers often vary considerably for the same disease, limiting their practical applicability.
- Differentiator: Prevalence aware feature selection improves biomarker identification in microbiome studies. 논문은 Metagenomic health prediction 문제를 Microbiome genetics 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42340677/), DOI landing page (https://doi.org/10.1093/bioinformatics/btag371).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: MOTIVATION: Identifying robust microbial biomarkers is crucial for disease diagnosis and prediction, elucidation of biological mechanisms, and development of targeted therapies.
- Why the problem matters: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Prior work baseline: However, those biomarkers often vary considerably for the same disease, limiting their practical applicability.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Microbiome genetics -> Metagenomic health prediction 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: MOTIVATION: Identifying robust microbial biomarkers is crucial for disease diagnosis and prediction, elucidation of biological mechanisms, and development of targeted therapies. Machine learning-based approaches, particularly the random forest model, have been widely used for biomarker identification during sample stratification. However, those biomarkers often vary considerably for the same disease, limiting their practical applicability. A robust framework for reliable biomarker identification in microbiome research is needed. To address this gap, we proposed a prevalence-aware feature selection framework (ParSlet) that incorporates a universal scaling relationship between taxon prevalence and selection frequency. RESULTS: We first identified a universal exponential scaling law linking the probability of a taxon being consistently recognized as a biomarker versus its prevalence. Then, we integrated this scaling law with taxa prevalence into the biomarker identification using random forest. We systematically evaluated this approach in both simulated microbiome datasets and real-world microbiome datasets and compared it with existing methods, finding that our integrated approach generally improved feature stability and reproducibility of biomarker identification. In colorectal cancer (CRC) datasets, our method robustly identified well-established microbial biomarkers such as Ruminococcus, Clostridium_XVIII, and Faecalibacterium. Integrating a prevalence-based scaling adjustment into feature importance enhances the stability of microbiome biomarker identification. This approach holds promise for enabling more reliable disease diagnostics, uncovering generalizable microbial signatures across cohorts, and guiding the development of targeted microbiome-based interventions. AVAILABILITY AND IMPLEMENTATION: ParSlet is available at https://github.com/KelabatOSU/Feature_selection.
- Input / cohort / material: microbiome studies
- Output / endpoint: Prevalence aware feature selection improves biomarker identification in microbiome studies. 논문은 Metagenomic health prediction 문제를 Microbiome genetics 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
- Expected clinical or biological impact: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
### Methods
- Method type: Machine learning, Microbiome biomarker analysis
- Key input: microbiome studies
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: However, those biomarkers often vary considerably for the same disease, limiting their practical applicability.
- Output: Prevalence aware feature selection improves biomarker identification in microbiome studies. 논문은 Metagenomic health prediction 문제를 Microbiome genetics 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
- Why this differs from prior methods: Prevalence aware feature selection improves biomarker identification in microbiome studies. 논문은 Metagenomic health prediction 문제를 Microbiome genetics 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: microbiome studies
- Purpose: Metagenomic health prediction branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: However, those biomarkers often vary considerably for the same disease, limiting their practical applicability.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 Prevalence aware feature selection improves biomarker identification in microbiome studies. 논문은 Metagenomic health prediction 문제를 Microbiome genetics 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
- Main result: MOTIVATION: Identifying robust microbial biomarkers is crucial for disease diagnosis and prediction, elucidation of biological mechanisms, and development of targeted therapies. Machine learning-based approaches, particularly the random forest model, have been widely used for biomarker identification during sample stratification. However, those biomarkers often vary considerably for the same disease, limiting their practical applicability. A robust framework for reliable biomarker identification in microbiome research is needed. To address this gap, we proposed a prevalence-aware feature selection framework (ParSlet) that incorporates a universal scaling relationship between taxon prevalence and selection frequency. RESULTS: We first identified a universal exponential scaling law linking the probability of a taxon being consistently recognized as a biomarker versus its prevalence. Then, we integrated this scaling law with taxa prevalence into the biomarker identification using random forest. We systematically evaluated this approach in both simulated microbiome datasets and real-world microbiome datasets and compared it with existing methods, finding that our integrated approach generally improved feature stability and reproducibility of biomarker identification. In colorectal cancer (CRC) datasets, our method robustly identified well-established microbial biomarkers such as Ruminococcus, Clostridium_XVIII, and Faecalibacterium. Integrating a prevalence-based scaling adjustment into feature importance enhances the stability of microbiome biomarker identification. This approach holds promise for enabling more reliable disease diagnostics, uncovering generalizable microbial signatures across cohorts, and guiding the development of targeted microbiome-based interventions. AVAILABILITY AND IMPLEMENTATION: ParSlet is available at https://github.com/KelabatOSU/Feature_selection.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Microbiome genetics 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: Prevalence aware feature selection improves biomarker identification in microbiome studies. 논문은 Metagenomic health prediction 문제를 Microbiome genetics 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: Prevalence aware feature selection improves biomarker identification in microbiome studies. 논문은 Metagenomic health prediction 문제를 Microbiome genetics 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
- Why this matters for healthcare or biology: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Microbiome genetics -> Metagenomic health prediction branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: Bioinformatics
- DOI: https://doi.org/10.1093/bioinformatics/btag371
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42340677/
- Article: https://doi.org/10.1093/bioinformatics/btag371
- Journal source: https://academic.oup.com/bioinformatics
- Secondary journal source: https://academic.oup.com/bioinformatics/advance-articles
- Screening report: reports/bioinformatics/2026-07-07_11-13-00.md
