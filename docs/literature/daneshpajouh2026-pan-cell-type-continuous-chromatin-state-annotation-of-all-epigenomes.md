---
type: paper
citekey: "daneshpajouh2026pancell"
title: "Pan-cell type continuous chromatin state annotation of all epigenomes from the International Human Epigenome Consortium."
year: 2026
journal: "Genome Biology"
status: bioflow-analyzed
major_topic: "Epigenome"
subtopics:
  - "3D genome architecture"
doi: "10.1186/s13059-026-04148-1"
pmid: "42271487"
url: "https://doi.org/10.1186/s13059-026-04148-1"
abstract_summary: "BACKGROUND: The International Human Epigenome Consortium has generated thousands of datasets profiling transcription factor binding, histone modification, and DNA accessibility. Existing segmentation and annotation approaches typically produce cell type-specific regulatory maps, which have become increasingly difficult to maintain and apply as the number of profiled cell types has grown. Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes. RESULTS: Using 9,539 histone modification signal tracks from 1,698 epigenomes, epigenome-ssm produces 33 continuous chromatin state features that compactly capture regulatory programs across cell types. These features distinguish canonical activities such as promoters, enhancers, transcription, and heterochromatin, while also encoding cell type-specific regulatory patterns. Compared with alternative pan-cell type annotation methods, the continuous features achieve superior or comparable predictive performance for gene expression, enhancer activity, and evolutionary conservation, despite using fewer dimensions. The model effectively captures both broad and lineage-specific regulatory programs, linking chromatin states to gene expression and functional annotations. Additionally, a derived conservation-associated activity score (SSM-CAAS) highlights genomic regions enriched for disease-associated variants, demonstrating utility for interpreting noncoding variation. CONCLUSIONS: Continuous pan-cell type chromatin state features provide a compact, expressive, and biologically informative representation of the human epigenome. This framework improves integration and interpretation of large-scale epigenomic data, enables accurate prediction of genomic function, and facilitates identification of regulatory elements relevant to disease. The resulting resource offers a scalable foundation for downstream analyses of gene regulation and genetic variation."
prior_limitations:
  - "Existing segmentation and annotation approaches typically produce cell type-specific regulatory maps, which have become increasingly difficult to maintain and apply as the number of profiled cell types has grown."
solution: "Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes."
differentiator: "Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes."
healthcare_relevance: "질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다."
datasets:
  - "International Human Epigenome Consortium"
methods:
  - "Chromatin/regulatory genomics"
topics:
  - "Epigenome"
  - "3D genome architecture"
tags:
  - paper
  - graph-topic
  - major-epigenome
  - subtopic-3d-genome-architecture
---
# Pan-cell type continuous chromatin state annotation of all epigenomes from the International Human Epigenome Consortium.
## Healthcare relevance
질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
## Analysis
- Abstract: BACKGROUND: The International Human Epigenome Consortium has generated thousands of datasets profiling transcription factor binding, histone modification, and DNA accessibility. Existing segmentation and annotation approaches typically produce cell type-specific regulatory maps, which have become increasingly difficult to maintain and apply as the number of profiled cell types has grown. Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes. RESULTS: Using 9,539 histone modification signal tracks from 1,698 epigenomes, epigenome-ssm produces 33 continuous chromatin state features that compactly capture regulatory programs across cell types. These features distinguish canonical activities such as promoters, enhancers, transcription, and heterochromatin, while also encoding cell type-specific regulatory patterns. Compared with alternative pan-cell type annotation methods, the continuous features achieve superior or comparable predictive performance for gene expression, enhancer activity, and evolutionary conservation, despite using fewer dimensions. The model effectively captures both broad and lineage-specific regulatory programs, linking chromatin states to gene expression and functional annotations. Additionally, a derived conservation-associated activity score (SSM-CAAS) highlights genomic regions enriched for disease-associated variants, demonstrating utility for interpreting noncoding variation. CONCLUSIONS: Continuous pan-cell type chromatin state features provide a compact, expressive, and biologically informative representation of the human epigenome. This framework improves integration and interpretation of large-scale epigenomic data, enables accurate prediction of genomic function, and facilitates identification of regulatory elements relevant to disease. The resulting resource offers a scalable foundation for downstream analyses of gene regulation and genetic variation.
- Prior limitation: Existing segmentation and annotation approaches typically produce cell type-specific regulatory maps, which have become increasingly difficult to maintain and apply as the number of profiled cell types has grown.
- Differentiator: Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42271487/), DOI landing page (https://doi.org/10.1186/s13059-026-04148-1).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: BACKGROUND: The International Human Epigenome Consortium has generated thousands of datasets profiling transcription factor binding, histone modification, and DNA accessibility.
- Why the problem matters: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Prior work baseline: Existing segmentation and annotation approaches typically produce cell type-specific regulatory maps, which have become increasingly difficult to maintain and apply as the number of profiled cell types has grown.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Epigenome -> 3D genome architecture 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: BACKGROUND: The International Human Epigenome Consortium has generated thousands of datasets profiling transcription factor binding, histone modification, and DNA accessibility. Existing segmentation and annotation approaches typically produce cell type-specific regulatory maps, which have become increasingly difficult to maintain and apply as the number of profiled cell types has grown. Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes. RESULTS: Using 9,539 histone modification signal tracks from 1,698 epigenomes, epigenome-ssm produces 33 continuous chromatin state features that compactly capture regulatory programs across cell types. These features distinguish canonical activities such as promoters, enhancers, transcription, and heterochromatin, while also encoding cell type-specific regulatory patterns. Compared with alternative pan-cell type annotation methods, the continuous features achieve superior or comparable predictive performance for gene expression, enhancer activity, and evolutionary conservation, despite using fewer dimensions. The model effectively captures both broad and lineage-specific regulatory programs, linking chromatin states to gene expression and functional annotations. Additionally, a derived conservation-associated activity score (SSM-CAAS) highlights genomic regions enriched for disease-associated variants, demonstrating utility for interpreting noncoding variation. CONCLUSIONS: Continuous pan-cell type chromatin state features provide a compact, expressive, and biologically informative representation of the human epigenome. This framework improves integration and interpretation of large-scale epigenomic data, enables accurate prediction of genomic function, and facilitates identification of regulatory elements relevant to disease. The resulting resource offers a scalable foundation for downstream analyses of gene regulation and genetic variation.
- Input / cohort / material: International Human Epigenome Consortium
- Output / endpoint: Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes.
- Expected clinical or biological impact: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
### Methods
- Method type: Chromatin/regulatory genomics
- Key input: International Human Epigenome Consortium
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: Existing segmentation and annotation approaches typically produce cell type-specific regulatory maps, which have become increasingly difficult to maintain and apply as the number of profiled cell types has grown.
- Output: Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes.
- Why this differs from prior methods: Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: International Human Epigenome Consortium
- Purpose: 3D genome architecture branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: Existing segmentation and annotation approaches typically produce cell type-specific regulatory maps, which have become increasingly difficult to maintain and apply as the number of profiled cell types has grown.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes.
- Main result: BACKGROUND: The International Human Epigenome Consortium has generated thousands of datasets profiling transcription factor binding, histone modification, and DNA accessibility. Existing segmentation and annotation approaches typically produce cell type-specific regulatory maps, which have become increasingly difficult to maintain and apply as the number of profiled cell types has grown. Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes. RESULTS: Using 9,539 histone modification signal tracks from 1,698 epigenomes, epigenome-ssm produces 33 continuous chromatin state features that compactly capture regulatory programs across cell types. These features distinguish canonical activities such as promoters, enhancers, transcription, and heterochromatin, while also encoding cell type-specific regulatory patterns. Compared with alternative pan-cell type annotation methods, the continuous features achieve superior or comparable predictive performance for gene expression, enhancer activity, and evolutionary conservation, despite using fewer dimensions. The model effectively captures both broad and lineage-specific regulatory programs, linking chromatin states to gene expression and functional annotations. Additionally, a derived conservation-associated activity score (SSM-CAAS) highlights genomic regions enriched for disease-associated variants, demonstrating utility for interpreting noncoding variation. CONCLUSIONS: Continuous pan-cell type chromatin state features provide a compact, expressive, and biologically informative representation of the human epigenome. This framework improves integration and interpretation of large-scale epigenomic data, enables accurate prediction of genomic function, and facilitates identification of regulatory elements relevant to disease. The resulting resource offers a scalable foundation for downstream analyses of gene regulation and genetic variation.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Epigenome 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: Here, we apply epigenome-ssm, a continuous state-space modeling framework, to generate a unified, interpretable representation of chromatin states across thousands of human epigenomes.
- Why this matters for healthcare or biology: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Epigenome -> 3D genome architecture branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: Genome Biology
- DOI: https://doi.org/10.1186/s13059-026-04148-1
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42271487/
- Article: https://doi.org/10.1186/s13059-026-04148-1
- Journal source: https://link.springer.com/journal/13059
- Secondary journal source: https://genomebiology.biomedcentral.com/
- Screening report: reports/genome-biology/2026-07-07_11-13-00.md
