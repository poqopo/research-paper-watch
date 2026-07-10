---
type: paper
citekey: "lim2026graphylovarpredicting"
title: "GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model."
year: 2026
journal: "Bioinformatics"
status: bioflow-analyzed
major_topic: "Epigenome"
subtopics:
  - "Disease regulatory variant interpretation"
doi: "10.1093/bioinformatics/btag426"
pmid: "42330352"
url: "https://doi.org/10.1093/bioinformatics/btag426"
abstract_summary: "MOTIVATION: Understanding the functional impact of genetic variants is a key problem for precision medicine. Tools like CADD, PhyloP, and PhastCons are useful, but they often look at each position in the genome in isolation. This means they can miss important information from the evolutionary history that connects different species. In this paper, we extend our previous model, Graphylo, to predict the effects of variants. Our new model, GraphyloVar, is built to directly utilize the phylogenetic tree that relates the species. RESULTS: GraphyloVar is a deep learning model that considers both DNA sequence and evolutionary patterns from many species. It uses two main components: Graph Convolutional Networks (GCNs) to process the phylogenetic tree, and Transformer encoders to extract features from the DNA sequences. Pre-trained to predict population-level allele frequencies on the TOPMed whole-genome sequencing cohort, GraphyloVar achieves an AUROC of 0.6246 zero-shot on ∼149M held-out variants, and an ensemble with CADD reaches 0.6442 (+0.020, P<10-15). Fine-tuned GraphyloVar achieves the highest AUROC across all 13 MPRA benchmark datasets. By integrating deep learning with explicit phylogenetic input, GraphyloVar offers a powerful and complementary approach to variant effect prediction that utilizes the full evolutionary history from many species to better identify and prioritize important non-coding variants. AVAILABILITY AND IMPLEMENTATION: Code and datasets are available at https://github.com/DongjoonLim/GraphyloVar under DOI: 10.5281/zenodo.20616818."
prior_limitations:
  - "Tools like CADD, PhyloP, and PhastCons are useful, but they often look at each position in the genome in isolation."
solution: "GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model. 논문은 Disease regulatory variant interpretation 문제를 Epigenome 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다."
differentiator: "GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model. 논문은 Disease regulatory variant interpretation 문제를 Epigenome 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다."
healthcare_relevance: "주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다."
datasets:
  - "genome sequencing"
methods:
  - "Deep learning"
  - "Phylogenetic inference"
topics:
  - "Epigenome"
  - "Disease regulatory variant interpretation"
tags:
  - paper
  - graph-topic
  - major-epigenome
  - subtopic-disease-regulatory-variant-interpretation
---
# GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model.
## Healthcare relevance
주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
## Analysis
- Abstract: MOTIVATION: Understanding the functional impact of genetic variants is a key problem for precision medicine. Tools like CADD, PhyloP, and PhastCons are useful, but they often look at each position in the genome in isolation. This means they can miss important information from the evolutionary history that connects different species. In this paper, we extend our previous model, Graphylo, to predict the effects of variants. Our new model, GraphyloVar, is built to directly utilize the phylogenetic tree that relates the species. RESULTS: GraphyloVar is a deep learning model that considers both DNA sequence and evolutionary patterns from many species. It uses two main components: Graph Convolutional Networks (GCNs) to process the phylogenetic tree, and Transformer encoders to extract features from the DNA sequences. Pre-trained to predict population-level allele frequencies on the TOPMed whole-genome sequencing cohort, GraphyloVar achieves an AUROC of 0.6246 zero-shot on ∼149M held-out variants, and an ensemble with CADD reaches 0.6442 (+0.020, P<10-15). Fine-tuned GraphyloVar achieves the highest AUROC across all 13 MPRA benchmark datasets. By integrating deep learning with explicit phylogenetic input, GraphyloVar offers a powerful and complementary approach to variant effect prediction that utilizes the full evolutionary history from many species to better identify and prioritize important non-coding variants. AVAILABILITY AND IMPLEMENTATION: Code and datasets are available at https://github.com/DongjoonLim/GraphyloVar under DOI: 10.5281/zenodo.20616818.
- Prior limitation: Tools like CADD, PhyloP, and PhastCons are useful, but they often look at each position in the genome in isolation.
- Differentiator: GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model. 논문은 Disease regulatory variant interpretation 문제를 Epigenome 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42330352/), DOI landing page (https://doi.org/10.1093/bioinformatics/btag426).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: MOTIVATION: Understanding the functional impact of genetic variants is a key problem for precision medicine.
- Why the problem matters: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
- Prior work baseline: Tools like CADD, PhyloP, and PhastCons are useful, but they often look at each position in the genome in isolation.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Epigenome -> Disease regulatory variant interpretation 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: MOTIVATION: Understanding the functional impact of genetic variants is a key problem for precision medicine. Tools like CADD, PhyloP, and PhastCons are useful, but they often look at each position in the genome in isolation. This means they can miss important information from the evolutionary history that connects different species. In this paper, we extend our previous model, Graphylo, to predict the effects of variants. Our new model, GraphyloVar, is built to directly utilize the phylogenetic tree that relates the species. RESULTS: GraphyloVar is a deep learning model that considers both DNA sequence and evolutionary patterns from many species. It uses two main components: Graph Convolutional Networks (GCNs) to process the phylogenetic tree, and Transformer encoders to extract features from the DNA sequences. Pre-trained to predict population-level allele frequencies on the TOPMed whole-genome sequencing cohort, GraphyloVar achieves an AUROC of 0.6246 zero-shot on ∼149M held-out variants, and an ensemble with CADD reaches 0.6442 (+0.020, P<10-15). Fine-tuned GraphyloVar achieves the highest AUROC across all 13 MPRA benchmark datasets. By integrating deep learning with explicit phylogenetic input, GraphyloVar offers a powerful and complementary approach to variant effect prediction that utilizes the full evolutionary history from many species to better identify and prioritize important non-coding variants. AVAILABILITY AND IMPLEMENTATION: Code and datasets are available at https://github.com/DongjoonLim/GraphyloVar under DOI: 10.5281/zenodo.20616818.
- Input / cohort / material: genome sequencing
- Output / endpoint: GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model. 논문은 Disease regulatory variant interpretation 문제를 Epigenome 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
- Expected clinical or biological impact: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
### Methods
- Method type: Deep learning, Phylogenetic inference
- Key input: genome sequencing
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: Tools like CADD, PhyloP, and PhastCons are useful, but they often look at each position in the genome in isolation.
- Output: GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model. 논문은 Disease regulatory variant interpretation 문제를 Epigenome 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
- Why this differs from prior methods: GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model. 논문은 Disease regulatory variant interpretation 문제를 Epigenome 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: genome sequencing
- Purpose: Disease regulatory variant interpretation branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: Tools like CADD, PhyloP, and PhastCons are useful, but they often look at each position in the genome in isolation.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model. 논문은 Disease regulatory variant interpretation 문제를 Epigenome 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
- Main result: MOTIVATION: Understanding the functional impact of genetic variants is a key problem for precision medicine. Tools like CADD, PhyloP, and PhastCons are useful, but they often look at each position in the genome in isolation. This means they can miss important information from the evolutionary history that connects different species. In this paper, we extend our previous model, Graphylo, to predict the effects of variants. Our new model, GraphyloVar, is built to directly utilize the phylogenetic tree that relates the species. RESULTS: GraphyloVar is a deep learning model that considers both DNA sequence and evolutionary patterns from many species. It uses two main components: Graph Convolutional Networks (GCNs) to process the phylogenetic tree, and Transformer encoders to extract features from the DNA sequences. Pre-trained to predict population-level allele frequencies on the TOPMed whole-genome sequencing cohort, GraphyloVar achieves an AUROC of 0.6246 zero-shot on ∼149M held-out variants, and an ensemble with CADD reaches 0.6442 (+0.020, P<10-15). Fine-tuned GraphyloVar achieves the highest AUROC across all 13 MPRA benchmark datasets. By integrating deep learning with explicit phylogenetic input, GraphyloVar offers a powerful and complementary approach to variant effect prediction that utilizes the full evolutionary history from many species to better identify and prioritize important non-coding variants. AVAILABILITY AND IMPLEMENTATION: Code and datasets are available at https://github.com/DongjoonLim/GraphyloVar under DOI: 10.5281/zenodo.20616818.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Epigenome 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model. 논문은 Disease regulatory variant interpretation 문제를 Epigenome 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: GraphyloVar: predicting the impact of non-coding variants using a multi-species sequence model. 논문은 Disease regulatory variant interpretation 문제를 Epigenome 맥락에서 다루는 새 데이터, 방법, 또는 해석 프레임을 제공한다.
- Why this matters for healthcare or biology: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Epigenome -> Disease regulatory variant interpretation branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: Bioinformatics
- DOI: https://doi.org/10.1093/bioinformatics/btag426
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42330352/
- Article: https://doi.org/10.1093/bioinformatics/btag426
- Journal source: https://academic.oup.com/bioinformatics
- Secondary journal source: https://academic.oup.com/bioinformatics/advance-articles
- Screening report: reports/bioinformatics/2026-07-07_11-13-00.md
