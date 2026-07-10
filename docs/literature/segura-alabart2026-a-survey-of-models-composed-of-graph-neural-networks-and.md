---
type: paper
citekey: "segura-alabart2026asurvey"
title: "A survey of models composed of graph neural networks and large language models for molecular science."
year: 2026
journal: "Bioinformatics"
status: bioflow-analyzed
major_topic: "Computational drug discovery"
subtopics:
  - "Molecular foundation models"
doi: "10.1093/bioinformatics/btag387"
pmid: "42296336"
url: "https://doi.org/10.1093/bioinformatics/btag387"
abstract_summary: "MOTIVATION: Graphs have been demonstrated to have an impressive ability to keep the structural and semantic properties of chemical compounds and are therefore widely used in molecular modeling. Moreover, Graph Neural Networks (GNNs) and Large Language Models (LLMs) have achieved outstanding results in predicting molecular properties and generating textual descriptions given graphs or texts, respectively. Recently, some mathematical models have been presented for molecular science applications, which combine the GNNs ability to capture the structural and semantic information and the generative ability of LLMs. However, these models are dispersed across the literature and vary in architecture, input-output design, and application scope, making it difficult to systematically compare them or to identify suitable approaches for specific research objectives. RESULTS: This paper classifies recent GNN-LLM models and summarizes them with the aim of providing guidance for research involving their use or the development of new models. We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications. In addition, a new model classification is presented to help researchers define the models they use or future ones. Finally, we quantitatively compare these models based on their reported experimental results."
prior_limitations:
  - "However, these models are dispersed across the literature and vary in architecture, input-output design, and application scope, making it difficult to systematically compare them or to identify suitable approaches for specific research objectives."
solution: "We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications."
differentiator: "We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications."
healthcare_relevance: "주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다."
datasets:
  - "Abstract-level source metadata"
methods:
  - "Graph neural network"
  - "Large language model"
topics:
  - "Computational drug discovery"
  - "Molecular foundation models"
tags:
  - paper
  - graph-topic
  - major-computational-drug-discovery
  - subtopic-molecular-foundation-models
---
# A survey of models composed of graph neural networks and large language models for molecular science.
## Healthcare relevance
주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
## Analysis
- Abstract: MOTIVATION: Graphs have been demonstrated to have an impressive ability to keep the structural and semantic properties of chemical compounds and are therefore widely used in molecular modeling. Moreover, Graph Neural Networks (GNNs) and Large Language Models (LLMs) have achieved outstanding results in predicting molecular properties and generating textual descriptions given graphs or texts, respectively. Recently, some mathematical models have been presented for molecular science applications, which combine the GNNs ability to capture the structural and semantic information and the generative ability of LLMs. However, these models are dispersed across the literature and vary in architecture, input-output design, and application scope, making it difficult to systematically compare them or to identify suitable approaches for specific research objectives. RESULTS: This paper classifies recent GNN-LLM models and summarizes them with the aim of providing guidance for research involving their use or the development of new models. We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications. In addition, a new model classification is presented to help researchers define the models they use or future ones. Finally, we quantitatively compare these models based on their reported experimental results.
- Prior limitation: However, these models are dispersed across the literature and vary in architecture, input-output design, and application scope, making it difficult to systematically compare them or to identify suitable approaches for specific research objectives.
- Differentiator: We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42296336/), DOI landing page (https://doi.org/10.1093/bioinformatics/btag387).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: MOTIVATION: Graphs have been demonstrated to have an impressive ability to keep the structural and semantic properties of chemical compounds and are therefore widely used in molecular modeling.
- Why the problem matters: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
- Prior work baseline: However, these models are dispersed across the literature and vary in architecture, input-output design, and application scope, making it difficult to systematically compare them or to identify suitable approaches for specific research objectives.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Computational drug discovery -> Molecular foundation models 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: MOTIVATION: Graphs have been demonstrated to have an impressive ability to keep the structural and semantic properties of chemical compounds and are therefore widely used in molecular modeling. Moreover, Graph Neural Networks (GNNs) and Large Language Models (LLMs) have achieved outstanding results in predicting molecular properties and generating textual descriptions given graphs or texts, respectively. Recently, some mathematical models have been presented for molecular science applications, which combine the GNNs ability to capture the structural and semantic information and the generative ability of LLMs. However, these models are dispersed across the literature and vary in architecture, input-output design, and application scope, making it difficult to systematically compare them or to identify suitable approaches for specific research objectives. RESULTS: This paper classifies recent GNN-LLM models and summarizes them with the aim of providing guidance for research involving their use or the development of new models. We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications. In addition, a new model classification is presented to help researchers define the models they use or future ones. Finally, we quantitatively compare these models based on their reported experimental results.
- Input / cohort / material: Abstract-level source metadata
- Output / endpoint: We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications.
- Expected clinical or biological impact: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
### Methods
- Method type: Graph neural network, Large language model
- Key input: Abstract-level source metadata
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: However, these models are dispersed across the literature and vary in architecture, input-output design, and application scope, making it difficult to systematically compare them or to identify suitable approaches for specific research objectives.
- Output: We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications.
- Why this differs from prior methods: We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: Abstract-level source metadata
- Purpose: Molecular foundation models branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: However, these models are dispersed across the literature and vary in architecture, input-output design, and application scope, making it difficult to systematically compare them or to identify suitable approaches for specific research objectives.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications.
- Main result: MOTIVATION: Graphs have been demonstrated to have an impressive ability to keep the structural and semantic properties of chemical compounds and are therefore widely used in molecular modeling. Moreover, Graph Neural Networks (GNNs) and Large Language Models (LLMs) have achieved outstanding results in predicting molecular properties and generating textual descriptions given graphs or texts, respectively. Recently, some mathematical models have been presented for molecular science applications, which combine the GNNs ability to capture the structural and semantic information and the generative ability of LLMs. However, these models are dispersed across the literature and vary in architecture, input-output design, and application scope, making it difficult to systematically compare them or to identify suitable approaches for specific research objectives. RESULTS: This paper classifies recent GNN-LLM models and summarizes them with the aim of providing guidance for research involving their use or the development of new models. We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications. In addition, a new model classification is presented to help researchers define the models they use or future ones. Finally, we quantitatively compare these models based on their reported experimental results.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Computational drug discovery 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: We present tables that depict the properties and parameters of the models, as well as their associated chemical computational applications.
- Why this matters for healthcare or biology: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Computational drug discovery -> Molecular foundation models branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: Bioinformatics
- DOI: https://doi.org/10.1093/bioinformatics/btag387
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42296336/
- Article: https://doi.org/10.1093/bioinformatics/btag387
- Journal source: https://academic.oup.com/bioinformatics
- Secondary journal source: https://academic.oup.com/bioinformatics/advance-articles
- Screening report: reports/bioinformatics/2026-07-07_11-13-00.md
