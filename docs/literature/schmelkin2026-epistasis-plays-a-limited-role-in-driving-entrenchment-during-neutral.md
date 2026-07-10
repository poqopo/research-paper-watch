---
type: paper
citekey: "schmelkin2026epistasisplays"
title: "Epistasis plays a limited role in driving entrenchment during neutral protein evolution."
year: 2026
journal: "Genome Biology"
status: bioflow-analyzed
major_topic: "Protein bioinformatics"
subtopics:
  - "Protein evolution modeling"
doi: "10.1186/s13059-026-04157-0"
pmid: "42304410"
url: "https://doi.org/10.1186/s13059-026-04157-0"
abstract_summary: "BACKGROUND: Substitutional entrenchment arising from epistatic interactions renders previously acceptable amino-acid states unfavorable over evolutionary time and has often been attributed to novel adaptive processes. However, recent simulations based on Potts-Hamiltonian models have suggested that entrenchment may also emerge during protein evolution governed by the neutral theory of molecular evolution (NTME). RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME. Since Potts models are inferred from a large collection of homologous rather than orthologous sequences, they may allow substitutions that are incompatible with NTME. Our analysis revealed that Potts-based simulations permit amino-acid substitutions whose Hamiltonian energies (PHE, φ) often fall outside empirically derived NTME φ neighborhoods, thus allowing non-neutral evolution of domain sequences. To prevent such transgressions, we implement simulations that impose purifying selection whenever Potts-acceptable substitutions depart from the NTME φ neighborhood. When these substitutions are eliminated, we observed limited substitutional entrenchment, with site-specific amino-acid preferences remaining stable over biologically relevant timescales in neutral protein evolution. We further find that overdispersion of the molecular clock is modest and scales directly with the proportion of evolutionary lineages displaying epistasis-driven among-site rate heterogeneity, independent of entrenchment. CONCLUSIONS: These results demonstrate that significant entrenchment is not an inherent property of epistasis during protein evolution consistent with NTME. Our findings establish baseline expectations for neutral evolution with epistasis and suggest that pronounced entrenchment observed in natural protein evolution likely reflects non-neutral evolutionary histories, including adaptation."
prior_limitations:
  - "However, recent simulations based on Potts-Hamiltonian models have suggested that entrenchment may also emerge during protein evolution governed by the neutral theory of molecular evolution (NTME)."
solution: "RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME."
differentiator: "RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME."
healthcare_relevance: "주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다."
datasets:
  - "Abstract-level source metadata"
methods:
  - "Abstract-level computational or genomic analysis"
topics:
  - "Protein bioinformatics"
  - "Protein evolution modeling"
tags:
  - paper
  - graph-topic
  - major-protein-bioinformatics
  - subtopic-protein-evolution-modeling
---
# Epistasis plays a limited role in driving entrenchment during neutral protein evolution.
## Healthcare relevance
주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
## Analysis
- Abstract: BACKGROUND: Substitutional entrenchment arising from epistatic interactions renders previously acceptable amino-acid states unfavorable over evolutionary time and has often been attributed to novel adaptive processes. However, recent simulations based on Potts-Hamiltonian models have suggested that entrenchment may also emerge during protein evolution governed by the neutral theory of molecular evolution (NTME). RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME. Since Potts models are inferred from a large collection of homologous rather than orthologous sequences, they may allow substitutions that are incompatible with NTME. Our analysis revealed that Potts-based simulations permit amino-acid substitutions whose Hamiltonian energies (PHE, φ) often fall outside empirically derived NTME φ neighborhoods, thus allowing non-neutral evolution of domain sequences. To prevent such transgressions, we implement simulations that impose purifying selection whenever Potts-acceptable substitutions depart from the NTME φ neighborhood. When these substitutions are eliminated, we observed limited substitutional entrenchment, with site-specific amino-acid preferences remaining stable over biologically relevant timescales in neutral protein evolution. We further find that overdispersion of the molecular clock is modest and scales directly with the proportion of evolutionary lineages displaying epistasis-driven among-site rate heterogeneity, independent of entrenchment. CONCLUSIONS: These results demonstrate that significant entrenchment is not an inherent property of epistasis during protein evolution consistent with NTME. Our findings establish baseline expectations for neutral evolution with epistasis and suggest that pronounced entrenchment observed in natural protein evolution likely reflects non-neutral evolutionary histories, including adaptation.
- Prior limitation: However, recent simulations based on Potts-Hamiltonian models have suggested that entrenchment may also emerge during protein evolution governed by the neutral theory of molecular evolution (NTME).
- Differentiator: RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42304410/), DOI landing page (https://doi.org/10.1186/s13059-026-04157-0).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: BACKGROUND: Substitutional entrenchment arising from epistatic interactions renders previously acceptable amino-acid states unfavorable over evolutionary time and has often been attributed to novel adaptive processes.
- Why the problem matters: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
- Prior work baseline: However, recent simulations based on Potts-Hamiltonian models have suggested that entrenchment may also emerge during protein evolution governed by the neutral theory of molecular evolution (NTME).
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Protein bioinformatics -> Protein evolution modeling 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: BACKGROUND: Substitutional entrenchment arising from epistatic interactions renders previously acceptable amino-acid states unfavorable over evolutionary time and has often been attributed to novel adaptive processes. However, recent simulations based on Potts-Hamiltonian models have suggested that entrenchment may also emerge during protein evolution governed by the neutral theory of molecular evolution (NTME). RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME. Since Potts models are inferred from a large collection of homologous rather than orthologous sequences, they may allow substitutions that are incompatible with NTME. Our analysis revealed that Potts-based simulations permit amino-acid substitutions whose Hamiltonian energies (PHE, φ) often fall outside empirically derived NTME φ neighborhoods, thus allowing non-neutral evolution of domain sequences. To prevent such transgressions, we implement simulations that impose purifying selection whenever Potts-acceptable substitutions depart from the NTME φ neighborhood. When these substitutions are eliminated, we observed limited substitutional entrenchment, with site-specific amino-acid preferences remaining stable over biologically relevant timescales in neutral protein evolution. We further find that overdispersion of the molecular clock is modest and scales directly with the proportion of evolutionary lineages displaying epistasis-driven among-site rate heterogeneity, independent of entrenchment. CONCLUSIONS: These results demonstrate that significant entrenchment is not an inherent property of epistasis during protein evolution consistent with NTME. Our findings establish baseline expectations for neutral evolution with epistasis and suggest that pronounced entrenchment observed in natural protein evolution likely reflects non-neutral evolutionary histories, including adaptation.
- Input / cohort / material: Abstract-level source metadata
- Output / endpoint: RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME.
- Expected clinical or biological impact: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
### Methods
- Method type: Abstract-level computational or genomic analysis
- Key input: Abstract-level source metadata
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: However, recent simulations based on Potts-Hamiltonian models have suggested that entrenchment may also emerge during protein evolution governed by the neutral theory of molecular evolution (NTME).
- Output: RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME.
- Why this differs from prior methods: RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: Abstract-level source metadata
- Purpose: Protein evolution modeling branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: However, recent simulations based on Potts-Hamiltonian models have suggested that entrenchment may also emerge during protein evolution governed by the neutral theory of molecular evolution (NTME).
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME.
- Main result: BACKGROUND: Substitutional entrenchment arising from epistatic interactions renders previously acceptable amino-acid states unfavorable over evolutionary time and has often been attributed to novel adaptive processes. However, recent simulations based on Potts-Hamiltonian models have suggested that entrenchment may also emerge during protein evolution governed by the neutral theory of molecular evolution (NTME). RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME. Since Potts models are inferred from a large collection of homologous rather than orthologous sequences, they may allow substitutions that are incompatible with NTME. Our analysis revealed that Potts-based simulations permit amino-acid substitutions whose Hamiltonian energies (PHE, φ) often fall outside empirically derived NTME φ neighborhoods, thus allowing non-neutral evolution of domain sequences. To prevent such transgressions, we implement simulations that impose purifying selection whenever Potts-acceptable substitutions depart from the NTME φ neighborhood. When these substitutions are eliminated, we observed limited substitutional entrenchment, with site-specific amino-acid preferences remaining stable over biologically relevant timescales in neutral protein evolution. We further find that overdispersion of the molecular clock is modest and scales directly with the proportion of evolutionary lineages displaying epistasis-driven among-site rate heterogeneity, independent of entrenchment. CONCLUSIONS: These results demonstrate that significant entrenchment is not an inherent property of epistasis during protein evolution consistent with NTME. Our findings establish baseline expectations for neutral evolution with epistasis and suggest that pronounced entrenchment observed in natural protein evolution likely reflects non-neutral evolutionary histories, including adaptation.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Protein bioinformatics 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: RESULTS: Here, we re-examine this conclusion by assessing whether substitutions permitted in such simulations are consistent with empirical expectations of NTME.
- Why this matters for healthcare or biology: 주로 생물학적 해석이나 계산 방법론을 개선하며, 관련 disease model 또는 omics workflow의 downstream 분석 품질을 높일 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Protein bioinformatics -> Protein evolution modeling branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: Genome Biology
- DOI: https://doi.org/10.1186/s13059-026-04157-0
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42304410/
- Article: https://doi.org/10.1186/s13059-026-04157-0
- Journal source: https://link.springer.com/journal/13059
- Secondary journal source: https://genomebiology.biomedcentral.com/
- Screening report: reports/genome-biology/2026-07-07_11-13-00.md
