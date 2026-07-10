---
type: paper
citekey: "dai2026identifyingcondition"
title: "Identifying condition-related cell-cell communication events using supervised tensor analysis."
year: 2026
journal: "The American Journal of Human Genetics"
status: bioflow-analyzed
major_topic: "Single-cell and spatial omics"
subtopics:
  - "Spatial signaling models"
doi: "10.1016/j.ajhg.2026.05.005"
pmid: "42242209"
url: "https://doi.org/10.1016/j.ajhg.2026.05.005"
abstract_summary: "Many tools have been developed to infer active cell-cell communication (CCC) events, which are essential for understanding biological processes and diseases. However, existing methods for assessing the relationships between CCC events and biological conditions have at least one practical limitation: a lack of clear interpretation, an inability to adjust for confounders, or an inability to model inherent dependencies among CCC events. To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events. STACCato employs a tensor-based regression model to enable statistical inference of the relationships between biological conditions (e.g., disease status or tissue types) and individual CCC events while accounting for confounders and dependencies among CCC events. Through extensive simulations and real-world applications on a lupus single-cell RNA sequencing (scRNA-seq) dataset and an autism single-nucleus RNA-seq (snRNA-seq) dataset, we demonstrate that STACCato consistently provides improved inference of condition-related CCC events compared to alternative methods. The STACCato tool is freely available on GitHub."
prior_limitations:
  - "However, existing methods for assessing the relationships between CCC events and biological conditions have at least one practical limitation: a lack of clear interpretation, an inability to adjust for confounders, or an inability to model inherent dependencies among CCC events."
solution: "To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events."
differentiator: "To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events."
healthcare_relevance: "질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다."
datasets:
  - "Abstract-level source metadata"
methods:
  - "Single-cell analysis"
topics:
  - "Single-cell and spatial omics"
  - "Spatial signaling models"
tags:
  - paper
  - graph-topic
  - major-single-cell-and-spatial-omics
  - subtopic-spatial-signaling-models
---
# Identifying condition-related cell-cell communication events using supervised tensor analysis.
## Healthcare relevance
질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
## Analysis
- Abstract: Many tools have been developed to infer active cell-cell communication (CCC) events, which are essential for understanding biological processes and diseases. However, existing methods for assessing the relationships between CCC events and biological conditions have at least one practical limitation: a lack of clear interpretation, an inability to adjust for confounders, or an inability to model inherent dependencies among CCC events. To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events. STACCato employs a tensor-based regression model to enable statistical inference of the relationships between biological conditions (e.g., disease status or tissue types) and individual CCC events while accounting for confounders and dependencies among CCC events. Through extensive simulations and real-world applications on a lupus single-cell RNA sequencing (scRNA-seq) dataset and an autism single-nucleus RNA-seq (snRNA-seq) dataset, we demonstrate that STACCato consistently provides improved inference of condition-related CCC events compared to alternative methods. The STACCato tool is freely available on GitHub.
- Prior limitation: However, existing methods for assessing the relationships between CCC events and biological conditions have at least one practical limitation: a lack of clear interpretation, an inability to adjust for confounders, or an inability to model inherent dependencies among CCC events.
- Differentiator: To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42242209/), DOI landing page (https://doi.org/10.1016/j.ajhg.2026.05.005).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: Many tools have been developed to infer active cell-cell communication (CCC) events, which are essential for understanding biological processes and diseases.
- Why the problem matters: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Prior work baseline: However, existing methods for assessing the relationships between CCC events and biological conditions have at least one practical limitation: a lack of clear interpretation, an inability to adjust for confounders, or an inability to model inherent dependencies among CCC events.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Single-cell and spatial omics -> Spatial signaling models 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: Many tools have been developed to infer active cell-cell communication (CCC) events, which are essential for understanding biological processes and diseases. However, existing methods for assessing the relationships between CCC events and biological conditions have at least one practical limitation: a lack of clear interpretation, an inability to adjust for confounders, or an inability to model inherent dependencies among CCC events. To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events. STACCato employs a tensor-based regression model to enable statistical inference of the relationships between biological conditions (e.g., disease status or tissue types) and individual CCC events while accounting for confounders and dependencies among CCC events. Through extensive simulations and real-world applications on a lupus single-cell RNA sequencing (scRNA-seq) dataset and an autism single-nucleus RNA-seq (snRNA-seq) dataset, we demonstrate that STACCato consistently provides improved inference of condition-related CCC events compared to alternative methods. The STACCato tool is freely available on GitHub.
- Input / cohort / material: Abstract-level source metadata
- Output / endpoint: To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events.
- Expected clinical or biological impact: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
### Methods
- Method type: Single-cell analysis
- Key input: Abstract-level source metadata
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: However, existing methods for assessing the relationships between CCC events and biological conditions have at least one practical limitation: a lack of clear interpretation, an inability to adjust for confounders, or an inability to model inherent dependencies among CCC events.
- Output: To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events.
- Why this differs from prior methods: To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: Abstract-level source metadata
- Purpose: Spatial signaling models branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: However, existing methods for assessing the relationships between CCC events and biological conditions have at least one practical limitation: a lack of clear interpretation, an inability to adjust for confounders, or an inability to model inherent dependencies among CCC events.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events.
- Main result: Many tools have been developed to infer active cell-cell communication (CCC) events, which are essential for understanding biological processes and diseases. However, existing methods for assessing the relationships between CCC events and biological conditions have at least one practical limitation: a lack of clear interpretation, an inability to adjust for confounders, or an inability to model inherent dependencies among CCC events. To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events. STACCato employs a tensor-based regression model to enable statistical inference of the relationships between biological conditions (e.g., disease status or tissue types) and individual CCC events while accounting for confounders and dependencies among CCC events. Through extensive simulations and real-world applications on a lupus single-cell RNA sequencing (scRNA-seq) dataset and an autism single-nucleus RNA-seq (snRNA-seq) dataset, we demonstrate that STACCato consistently provides improved inference of condition-related CCC events compared to alternative methods. The STACCato tool is freely available on GitHub.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Single-cell and spatial omics 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: To comprehensively address these limitations, we introduce STACCato, a supervised tensor analysis tool for identifying condition-related CCC events.
- Why this matters for healthcare or biology: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Single-cell and spatial omics -> Spatial signaling models branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: The American Journal of Human Genetics
- DOI: https://doi.org/10.1016/j.ajhg.2026.05.005
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42242209/
- Article: https://doi.org/10.1016/j.ajhg.2026.05.005
- Journal source: https://www.sciencedirect.com/journal/the-american-journal-of-human-genetics
- Secondary journal source: https://www.cell.com/AJHG/home
- Screening report: reports/ajhg/2026-07-07_11-13-00.md
