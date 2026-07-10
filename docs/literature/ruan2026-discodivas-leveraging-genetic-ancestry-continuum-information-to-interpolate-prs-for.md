---
type: paper
citekey: "ruan2026discodivasleveraging"
title: "DiscoDivas: Leveraging genetic-ancestry continuum information to interpolate PRS for admixed populations."
year: 2026
journal: "The American Journal of Human Genetics"
status: bioflow-analyzed
major_topic: "Statistical genetics"
subtopics:
  - "GWAS disease genetics"
doi: "10.1016/j.ajhg.2026.05.006"
pmid: "42235505"
url: "https://doi.org/10.1016/j.ajhg.2026.05.006"
abstract_summary: "Genome-wide association study (GWAS) summary statistics for training and individual-level cohorts for fine-tuning are essential for constructing predictive polygenic risk score (PRS) models. However, the relatively low representation of admixed populations in both GWAS summary statistics and individual-level datasets hinders the development of PRSs and equitable clinical translation for admixed populations. Prior work indicates that the most informative PRS model for a genetically homogeneous sample varies linearly in an ancestry continuum space. Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries. DiscoDivas leverages multiple PRS models fine-tuned within existing samples, which are mostly of single ancestry, and genetic distance. It provides a new approach to generate genetic-ancestry-specific PRSs when a suitably matched individual-level fine-tuning cohort is unavailable or underpowered. DiscoDivas treats genetic ancestry as a continuous variable and does not require shifting across different models when calculating PRSs for different ancestries. We generated PRSs with DiscoDivas and the current conventional method, i.e., fine-tuning multiple GWAS PRSs using the matched or similar genetic-ancestry samples. DiscoDivas generated a harmonized PRS, performing comparable to or better than the conventional approach, with the greatest advantage exhibited in admixed individuals."
prior_limitations:
  - "However, the relatively low representation of admixed populations in both GWAS summary statistics and individual-level datasets hinders the development of PRSs and equitable clinical translation for admixed populations."
solution: "Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries."
differentiator: "Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries."
healthcare_relevance: "질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다."
datasets:
  - "GWAS summary statistics"
methods:
  - "GWAS"
  - "Polygenic score modeling"
  - "Genome-wide association analysis"
topics:
  - "Statistical genetics"
  - "GWAS disease genetics"
tags:
  - paper
  - graph-topic
  - major-statistical-genetics
  - subtopic-gwas-disease-genetics
---
# DiscoDivas: Leveraging genetic-ancestry continuum information to interpolate PRS for admixed populations.
## Healthcare relevance
질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
## Analysis
- Abstract: Genome-wide association study (GWAS) summary statistics for training and individual-level cohorts for fine-tuning are essential for constructing predictive polygenic risk score (PRS) models. However, the relatively low representation of admixed populations in both GWAS summary statistics and individual-level datasets hinders the development of PRSs and equitable clinical translation for admixed populations. Prior work indicates that the most informative PRS model for a genetically homogeneous sample varies linearly in an ancestry continuum space. Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries. DiscoDivas leverages multiple PRS models fine-tuned within existing samples, which are mostly of single ancestry, and genetic distance. It provides a new approach to generate genetic-ancestry-specific PRSs when a suitably matched individual-level fine-tuning cohort is unavailable or underpowered. DiscoDivas treats genetic ancestry as a continuous variable and does not require shifting across different models when calculating PRSs for different ancestries. We generated PRSs with DiscoDivas and the current conventional method, i.e., fine-tuning multiple GWAS PRSs using the matched or similar genetic-ancestry samples. DiscoDivas generated a harmonized PRS, performing comparable to or better than the conventional approach, with the greatest advantage exhibited in admixed individuals.
- Prior limitation: However, the relatively low representation of admixed populations in both GWAS summary statistics and individual-level datasets hinders the development of PRSs and equitable clinical translation for admixed populations.
- Differentiator: Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42235505/), DOI landing page (https://doi.org/10.1016/j.ajhg.2026.05.006).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: Genome-wide association study (GWAS) summary statistics for training and individual-level cohorts for fine-tuning are essential for constructing predictive polygenic risk score (PRS) models.
- Why the problem matters: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Prior work baseline: However, the relatively low representation of admixed populations in both GWAS summary statistics and individual-level datasets hinders the development of PRSs and equitable clinical translation for admixed populations.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Statistical genetics -> GWAS disease genetics 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: Genome-wide association study (GWAS) summary statistics for training and individual-level cohorts for fine-tuning are essential for constructing predictive polygenic risk score (PRS) models. However, the relatively low representation of admixed populations in both GWAS summary statistics and individual-level datasets hinders the development of PRSs and equitable clinical translation for admixed populations. Prior work indicates that the most informative PRS model for a genetically homogeneous sample varies linearly in an ancestry continuum space. Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries. DiscoDivas leverages multiple PRS models fine-tuned within existing samples, which are mostly of single ancestry, and genetic distance. It provides a new approach to generate genetic-ancestry-specific PRSs when a suitably matched individual-level fine-tuning cohort is unavailable or underpowered. DiscoDivas treats genetic ancestry as a continuous variable and does not require shifting across different models when calculating PRSs for different ancestries. We generated PRSs with DiscoDivas and the current conventional method, i.e., fine-tuning multiple GWAS PRSs using the matched or similar genetic-ancestry samples. DiscoDivas generated a harmonized PRS, performing comparable to or better than the conventional approach, with the greatest advantage exhibited in admixed individuals.
- Input / cohort / material: GWAS summary statistics
- Output / endpoint: Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries.
- Expected clinical or biological impact: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
### Methods
- Method type: GWAS, Polygenic score modeling, Genome-wide association analysis
- Key input: GWAS summary statistics
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: However, the relatively low representation of admixed populations in both GWAS summary statistics and individual-level datasets hinders the development of PRSs and equitable clinical translation for admixed populations.
- Output: Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries.
- Why this differs from prior methods: Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: GWAS summary statistics
- Purpose: GWAS disease genetics branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: However, the relatively low representation of admixed populations in both GWAS summary statistics and individual-level datasets hinders the development of PRSs and equitable clinical translation for admixed populations.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries.
- Main result: Genome-wide association study (GWAS) summary statistics for training and individual-level cohorts for fine-tuning are essential for constructing predictive polygenic risk score (PRS) models. However, the relatively low representation of admixed populations in both GWAS summary statistics and individual-level datasets hinders the development of PRSs and equitable clinical translation for admixed populations. Prior work indicates that the most informative PRS model for a genetically homogeneous sample varies linearly in an ancestry continuum space. Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries. DiscoDivas leverages multiple PRS models fine-tuned within existing samples, which are mostly of single ancestry, and genetic distance. It provides a new approach to generate genetic-ancestry-specific PRSs when a suitably matched individual-level fine-tuning cohort is unavailable or underpowered. DiscoDivas treats genetic ancestry as a continuous variable and does not require shifting across different models when calculating PRSs for different ancestries. We generated PRSs with DiscoDivas and the current conventional method, i.e., fine-tuning multiple GWAS PRSs using the matched or similar genetic-ancestry samples. DiscoDivas generated a harmonized PRS, performing comparable to or better than the conventional approach, with the greatest advantage exhibited in admixed individuals.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Statistical genetics 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: Guided by these observations, we introduce a genetic-distance-assisted PRS combination pipeline for diverse genetic ancestries (DiscoDivas) to interpolate a harmonized PRS for diverse, especially admixed, genetic ancestries.
- Why this matters for healthcare or biology: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Statistical genetics -> GWAS disease genetics branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: The American Journal of Human Genetics
- DOI: https://doi.org/10.1016/j.ajhg.2026.05.006
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42235505/
- Article: https://doi.org/10.1016/j.ajhg.2026.05.006
- Journal source: https://www.sciencedirect.com/journal/the-american-journal-of-human-genetics
- Secondary journal source: https://www.cell.com/AJHG/home
- Screening report: reports/ajhg/2026-07-07_11-13-00.md
