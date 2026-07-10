---
type: paper
citekey: "sanden2026hifisequencing"
title: "HiFi sequencing accurately identifies clinically relevant variants in paralogous genes."
year: 2026
journal: "The American Journal of Human Genetics"
status: bioflow-analyzed
major_topic: "Genome sequencing methods"
subtopics:
  - "Clinical long-read sequencing"
doi: "10.1016/j.ajhg.2026.04.014"
pmid: "42242190"
url: "https://doi.org/10.1016/j.ajhg.2026.04.014"
abstract_summary: "Short-read sequencing (SRS) methods have improved the detection of small genetic variants but remain limited in highly homologous genomic regions, such as segmental duplications with gene-pseudogene pairs. These paralogous regions often require complex, locus-specific assays for accurate analysis. Long-read genome sequencing (lrGS) technologies, such as PacBio HiFi sequencing, can span these regions but still face challenges in variant calling due to alignment ambiguities. Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci. Standard HiFi variant callers detected 95/125 variants, while the remaining 30 variants were only identified by Paraphase. Together, the standard variant callers and Paraphase detected all known variants, including single-nucleotide variants (SNVs), insertions or deletions (InDels), copy-number variants (CNVs), structural variants (SVs), and gene conversions. In addition, lrGS allowed for accurate phasing and gene-pseudogene copy-number detection. We demonstrate that PacBio HiFi lrGS, particularly when integrated with Paraphase, enables comprehensive variant detection in previously difficult-to-assess genomic regions. These results also suggest that lrGS is ready for a wider implementation, possibly as a first-tier diagnostic approach for individuals with suspected variants in these paralogous regions. Ideally, clinical adoption is guided by prospectively designed clinical utility studies, alongside evaluation of sensitivity, specificity, and cost-effectiveness."
prior_limitations:
  - "Short-read sequencing (SRS) methods have improved the detection of small genetic variants but remain limited in highly homologous genomic regions, such as segmental duplications with gene-pseudogene pairs."
solution: "Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci."
differentiator: "Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci."
healthcare_relevance: "질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다."
datasets:
  - "HiFi sequencing"
  - "genome sequencing"
methods:
  - "Long-read sequencing analysis"
  - "HiFi sequencing"
  - "Structural variant analysis"
topics:
  - "Genome sequencing methods"
  - "Clinical long-read sequencing"
tags:
  - paper
  - graph-topic
  - major-genome-sequencing-methods
  - subtopic-clinical-long-read-sequencing
---
# HiFi sequencing accurately identifies clinically relevant variants in paralogous genes.
## Healthcare relevance
질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
## Analysis
- Abstract: Short-read sequencing (SRS) methods have improved the detection of small genetic variants but remain limited in highly homologous genomic regions, such as segmental duplications with gene-pseudogene pairs. These paralogous regions often require complex, locus-specific assays for accurate analysis. Long-read genome sequencing (lrGS) technologies, such as PacBio HiFi sequencing, can span these regions but still face challenges in variant calling due to alignment ambiguities. Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci. Standard HiFi variant callers detected 95/125 variants, while the remaining 30 variants were only identified by Paraphase. Together, the standard variant callers and Paraphase detected all known variants, including single-nucleotide variants (SNVs), insertions or deletions (InDels), copy-number variants (CNVs), structural variants (SVs), and gene conversions. In addition, lrGS allowed for accurate phasing and gene-pseudogene copy-number detection. We demonstrate that PacBio HiFi lrGS, particularly when integrated with Paraphase, enables comprehensive variant detection in previously difficult-to-assess genomic regions. These results also suggest that lrGS is ready for a wider implementation, possibly as a first-tier diagnostic approach for individuals with suspected variants in these paralogous regions. Ideally, clinical adoption is guided by prospectively designed clinical utility studies, alongside evaluation of sensitivity, specificity, and cost-effectiveness.
- Prior limitation: Short-read sequencing (SRS) methods have improved the detection of small genetic variants but remain limited in highly homologous genomic regions, such as segmental duplications with gene-pseudogene pairs.
- Differentiator: Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci.
## BioProject-style analysis
### Evidence level
- Source level: Screening report generated from journal/PubMed metadata, PubMed record (https://pubmed.ncbi.nlm.nih.gov/42242190/), DOI landing page (https://doi.org/10.1016/j.ajhg.2026.04.014).
- Missing source material: Full PDF, figure panels, supplementary tables, exact benchmark settings, and author-stated limitations beyond abstract metadata were not extracted in this import.
### Background
- Problem context: Short-read sequencing (SRS) methods have improved the detection of small genetic variants but remain limited in highly homologous genomic regions, such as segmental duplications with gene-pseudogene pairs.
- Why the problem matters: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Prior work baseline: Short-read sequencing (SRS) methods have improved the detection of small genetic variants but remain limited in highly homologous genomic regions, such as segmental duplications with gene-pseudogene pairs.
- Gap that remains: full text 확인 필요. 현재 note는 abstract-level screening 기반이다.
### Overview
- Core question: 이 논문은 Genome sequencing methods -> Clinical long-read sequencing 흐름에서 어떤 새 데이터, 방법, 또는 해석을 제공하는가?
- Paper's framing: Short-read sequencing (SRS) methods have improved the detection of small genetic variants but remain limited in highly homologous genomic regions, such as segmental duplications with gene-pseudogene pairs. These paralogous regions often require complex, locus-specific assays for accurate analysis. Long-read genome sequencing (lrGS) technologies, such as PacBio HiFi sequencing, can span these regions but still face challenges in variant calling due to alignment ambiguities. Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci. Standard HiFi variant callers detected 95/125 variants, while the remaining 30 variants were only identified by Paraphase. Together, the standard variant callers and Paraphase detected all known variants, including single-nucleotide variants (SNVs), insertions or deletions (InDels), copy-number variants (CNVs), structural variants (SVs), and gene conversions. In addition, lrGS allowed for accurate phasing and gene-pseudogene copy-number detection. We demonstrate that PacBio HiFi lrGS, particularly when integrated with Paraphase, enables comprehensive variant detection in previously difficult-to-assess genomic regions. These results also suggest that lrGS is ready for a wider implementation, possibly as a first-tier diagnostic approach for individuals with suspected variants in these paralogous regions. Ideally, clinical adoption is guided by prospectively designed clinical utility studies, alongside evaluation of sensitivity, specificity, and cost-effectiveness.
- Input / cohort / material: HiFi sequencing; genome sequencing
- Output / endpoint: Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci.
- Expected clinical or biological impact: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
### Methods
- Method type: Long-read sequencing analysis, HiFi sequencing, Structural variant analysis
- Key input: HiFi sequencing; genome sequencing
- Core processing step: abstract metadata만으로 작성했으므로 세부 protocol, parameter, model architecture, validation split은 full text 확인 필요.
- Comparator / baseline: Short-read sequencing (SRS) methods have improved the detection of small genetic variants but remain limited in highly homologous genomic regions, such as segmental duplications with gene-pseudogene pairs.
- Output: Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci.
- Why this differs from prior methods: Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci.
### Figures / Tables
- PDF/figure 확인 필요. 현재 local note에는 figure panel, caption, table, supplementary evidence가 포함되지 않았다.
### Results
#### Dataset / cohort results
- Dataset or cohort: HiFi sequencing; genome sequencing
- Purpose: Clinical long-read sequencing branch에서 핵심 contribution을 평가한다.
- Scale: abstract에서 확인 가능한 범위만 기록했다.
- Baseline / comparator: Short-read sequencing (SRS) methods have improved the detection of small genetic variants but remain limited in highly homologous genomic regions, such as segmental duplications with gene-pseudogene pairs.
- Metric / endpoint: full text 확인 필요; 현재 endpoint는 Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci.
- Main result: Short-read sequencing (SRS) methods have improved the detection of small genetic variants but remain limited in highly homologous genomic regions, such as segmental duplications with gene-pseudogene pairs. These paralogous regions often require complex, locus-specific assays for accurate analysis. Long-read genome sequencing (lrGS) technologies, such as PacBio HiFi sequencing, can span these regions but still face challenges in variant calling due to alignment ambiguities. Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci. Standard HiFi variant callers detected 95/125 variants, while the remaining 30 variants were only identified by Paraphase. Together, the standard variant callers and Paraphase detected all known variants, including single-nucleotide variants (SNVs), insertions or deletions (InDels), copy-number variants (CNVs), structural variants (SVs), and gene conversions. In addition, lrGS allowed for accurate phasing and gene-pseudogene copy-number detection. We demonstrate that PacBio HiFi lrGS, particularly when integrated with Paraphase, enables comprehensive variant detection in previously difficult-to-assess genomic regions. These results also suggest that lrGS is ready for a wider implementation, possibly as a first-tier diagnostic approach for individuals with suspected variants in these paralogous regions. Ideally, clinical adoption is guided by prospectively designed clinical utility studies, alongside evaluation of sensitivity, specificity, and cost-effectiveness.
- How this supports the paper's claim: abstract 또는 metadata가 제시한 핵심 claim을 taxonomy placement와 연결했다.
#### Overall result pattern
- Repeated pattern: Genome sequencing methods 분야에서 최신 2025-2026 trend를 반영하는 branch로 분류된다.
- Strongest result: Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci.
- Result caveat: abstract-level import라서 수치, figure, external validation은 추가 검토가 필요하다.
### Limitations
- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: 현재 근거는 screening report와 abstract metadata에 제한된다.
- Missing validation: 독립 cohort, cross-platform replication, prospective utility, benchmark table은 paper-specific full text review가 필요하다.
- Weak link between evidence and claim: claim은 기록했지만 figure-level evidence extraction은 아직 수행하지 않았다.
### Final Takeaways
- Main takeaway: Here, we evaluated PacBio HiFi lrGS combined with Paraphase, a dedicated haplotype-based variant caller, in 86 individuals with 125 known clinically relevant variants across 11 paralogous loci.
- Why this matters for healthcare or biology: 질병 위험 예측, 진단 보조, 환자 stratification, 또는 임상 유전체 해석으로 확장될 수 있다.
- Next-paper idea: full text/PDF를 회수해 cohort, baseline, metric, figure, author-stated limitation을 deeper review note로 보강한다.
- Reusable idea for this vault: Genome sequencing methods -> Clinical long-read sequencing branch에서 관련 paper들과 trend 비교에 사용한다.
## Source
- Journal: The American Journal of Human Genetics
- DOI: https://doi.org/10.1016/j.ajhg.2026.04.014
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42242190/
- Article: https://doi.org/10.1016/j.ajhg.2026.04.014
- Journal source: https://www.sciencedirect.com/journal/the-american-journal-of-human-genetics
- Secondary journal source: https://www.cell.com/AJHG/home
- Screening report: reports/ajhg/2026-07-07_11-13-00.md
