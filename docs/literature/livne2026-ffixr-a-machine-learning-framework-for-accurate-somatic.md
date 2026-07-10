---
type: paper
citekey: "livne2026ffixr"
title: "FFixR: A Machine Learning Framework for Accurate Somatic Mutation Calling from FFPE RNA-Seq Data in Cancer"
year: 2026
journal: "Bioinformatics"
status: bioflow-analyzed
major_topic: "Cancer genomics"
subtopics:
  - "Somatic mutation calling"
doi: "10.1093/bioinformatics/btag405"
pmid: "42340671"
url: "https://doi.org/10.1093/bioinformatics/btag405"
abstract_summary: "MOTIVATION: Formalin-fixed paraffin-embedded (FFPE) tissues are widely used in clinical and research settings, yet their use for detecting somatic mutations from RNA sequencing (RNA-seq) is hindered by artefactual mutations introduced by cytosine deamination and strand-specific damage. Existing FFPE noise-filtering tools are tailored to DNA-seq and rely on strand bias, rendering them unsuitable for RNA-seq. Here, we present FFixR, a machine learning-based framework that filters FFPE-induced artefacts from RNA-seq data without requiring matched-normal samples."
prior_limitations:
  - "Formalin-fixed paraffin-embedded (FFPE) tissues are widely used in clinical and research settings, yet their use for detecting somatic mutations from RNA sequencing (RNA-seq) is hindered by artefactual mutations introduced by cytosine deamination and strand-specific damage. Existing FFPE noise-filtering tools are tailored to DNA-seq and rely on strand bias, rendering them unsuitable for RNA-seq."
solution: "Trained on FFPE melanoma samples with matched DNA, FFixR leverages allele-specific read counts, variant features, and mutational signature probabilities. FFixR removed up to 98% of artefactual mutations while maintaining ~92% recall of true variants."
differentiator: "Trained on FFPE melanoma samples with matched DNA, FFixR leverages allele-specific read counts, variant features, and mutational signature probabilities. FFixR removed up to 98% of artefactual mutations while maintaining ~92% recall of true variants."
healthcare_relevance: "Improves mutation calling from clinically common FFPE RNA-seq cancer specimens."
datasets: []
methods:
  - "Machine learning"
  - "FFPE RNA-seq"
  - "Somatic mutation calling"
topics:
  - "Cancer genomics"
  - "Somatic mutation calling"
tags:
  - paper
  - graph-topic
  - major-cancer-genomics
  - subtopic-somatic-mutation-calling
---

# FFixR: A Machine Learning Framework for Accurate Somatic Mutation Calling from FFPE RNA-Seq Data in Cancer

## Healthcare relevance

Improves mutation calling from clinically common FFPE RNA-seq cancer specimens.

## Analysis

- Abstract: MOTIVATION: Formalin-fixed paraffin-embedded (FFPE) tissues are widely used in clinical and research settings, yet their use for detecting somatic mutations from RNA sequencing (RNA-seq) is hindered by artefactual mutations introduced by cytosine deamination and strand-specific damage.  Existing FFPE noise-filtering tools are tailored to DNA-seq and rely on strand bias, rendering them unsuitable for RNA-seq.  Here, we present FFixR, a machine learning-based framework that filters FFPE-induced artefacts from RNA-seq data without requiring matched-normal samples.
- Prior limitation: Formalin-fixed paraffin-embedded (FFPE) tissues are widely used in clinical and research settings, yet their use for detecting somatic mutations from RNA sequencing (RNA-seq) is hindered by artefactual mutations introduced by cytosine deamination and strand-specific damage.  Existing FFPE noise-filtering tools are tailored to DNA-seq and rely on strand bias, rendering them unsuitable for RNA-seq.
- Differentiator: Trained on FFPE melanoma samples with matched DNA, FFixR leverages allele-specific read counts, variant features, and mutational signature probabilities.  FFixR removed up to 98% of artefactual mutations while maintaining ~92% recall of true variants.

## BioProject-style analysis

### Evidence level

- Source level: PubMed record (https://pubmed.ncbi.nlm.nih.gov/42340671/), DOI landing page (https://doi.org/10.1093/bioinformatics/btag405), and Bioinformatics journal pages (https://academic.oup.com/bioinformatics; https://academic.oup.com/bioinformatics/advance-articles).
- Missing source material: Full PDF, figures, tables, supplementary benchmarks beyond PubMed abstract, and exact implementation details were not extracted in this pass.

### Background

- Problem context: MOTIVATION: Formalin-fixed paraffin-embedded (FFPE) tissues are widely used in clinical and research settings, yet their use for detecting somatic mutations from RNA sequencing (RNA-seq) is hindered by artefactual mutations introduced by cytosine deamination and strand-specific damage.  Existing FFPE noise-filtering tools are tailored to DNA-seq and rely on strand bias, rendering them unsuitable for RNA-seq.  Here, we present FFixR, a machine learning-based framework that filters FFPE-induced artefacts from RNA-seq data without requiring matched-normal samples.
- Why the problem matters: Improves mutation calling from clinically common FFPE RNA-seq cancer specimens.
- Prior work baseline: Formalin-fixed paraffin-embedded (FFPE) tissues are widely used in clinical and research settings, yet their use for detecting somatic mutations from RNA sequencing (RNA-seq) is hindered by artefactual mutations introduced by cytosine deamination and strand-specific damage.  Existing FFPE noise-filtering tools are tailored to DNA-seq and rely on strand bias, rendering them unsuitable for RNA-seq.
- Gap that remains: Formalin-fixed paraffin-embedded (FFPE) tissues are widely used in clinical and research settings, yet their use for detecting somatic mutations from RNA sequencing (RNA-seq) is hindered by artefactual mutations introduced by cytosine deamination and strand-specific damage.  Existing FFPE noise-filtering tools are tailored to DNA-seq and rely on strand bias, rendering them unsuitable for RNA-seq.

### Overview

- Core question: How does this paper advance Somatic mutation calling within the broader Cancer genomics topic?
- Paper's framing: MOTIVATION: Formalin-fixed paraffin-embedded (FFPE) tissues are widely used in clinical and research settings, yet their use for detecting somatic mutations from RNA sequencing (RNA-seq) is hindered by artefactual mutations introduced by cytosine deamination and strand-specific damage.  Existing FFPE noise-filtering tools are tailored to DNA-seq and rely on strand bias, rendering them unsuitable for RNA-seq.
- Input / cohort / material: Dataset details require full text review; PubMed abstract gives the high-level task and evaluation setting.
- Output / endpoint: Trained on FFPE melanoma samples with matched DNA, FFixR leverages allele-specific read counts, variant features, and mutational signature probabilities.  FFixR removed up to 98% of artefactual mutations while maintaining ~92% recall of true variants.
- Expected clinical or biological impact: Improves mutation calling from clinically common FFPE RNA-seq cancer specimens.

### Methods

- Method type: Machine learning, FFPE RNA-seq, Somatic mutation calling
- Key input: Input material requires full text review.
- Core processing step: The PubMed abstract supports the high-level method classification; full algorithmic and implementation details still require article/PDF review.
- Comparator / baseline: Formalin-fixed paraffin-embedded (FFPE) tissues are widely used in clinical and research settings, yet their use for detecting somatic mutations from RNA sequencing (RNA-seq) is hindered by artefactual mutations introduced by cytosine deamination and strand-specific damage.  Existing FFPE noise-filtering tools are tailored to DNA-seq and rely on strand bias, rendering them unsuitable for RNA-seq.
- Output: Trained on FFPE melanoma samples with matched DNA, FFixR leverages allele-specific read counts, variant features, and mutational signature probabilities.  FFixR removed up to 98% of artefactual mutations while maintaining ~92% recall of true variants.
- Why this differs from prior methods: Trained on FFPE melanoma samples with matched DNA, FFixR leverages allele-specific read counts, variant features, and mutational signature probabilities.  FFixR removed up to 98% of artefactual mutations while maintaining ~92% recall of true variants.

### Figures / Tables

- PDF/figure 확인 필요. Current local note does not include figure panels, captions, table rows, supplementary figures, or benchmark tables.

### Results

#### Dataset / cohort results

- Dataset or cohort: Dataset and benchmark details require full text review.
- Purpose: Evaluate the paper's contribution to Somatic mutation calling.
- Scale: Exact sample size, benchmark count, and parameter settings require full text review unless stated in the abstract summary.
- Baseline / comparator: Formalin-fixed paraffin-embedded (FFPE) tissues are widely used in clinical and research settings, yet their use for detecting somatic mutations from RNA sequencing (RNA-seq) is hindered by artefactual mutations introduced by cytosine deamination and strand-specific damage.  Existing FFPE noise-filtering tools are tailored to DNA-seq and rely on strand bias, rendering them unsuitable for RNA-seq.
- Metric / endpoint: Full metric extraction requires article/PDF review; current endpoint is summarized as: Trained on FFPE melanoma samples with matched DNA, FFixR leverages allele-specific read counts, variant features, and mutational signature probabilities.  FFixR removed up to 98% of artefactual mutations while maintaining ~92% recall of true variants.
- Main quantitative result: Exact quantitative result requires full text review.
- Qualitative result: Trained on FFPE melanoma samples with matched DNA, FFixR leverages allele-specific read counts, variant features, and mutational signature probabilities.  FFixR removed up to 98% of artefactual mutations while maintaining ~92% recall of true variants.
- How this supports the paper's claim: The PubMed abstract states the main method or resource contribution and supports this taxonomy placement.

#### Overall result pattern

- Repeated pattern: This paper proposes a computational method, model, database, or workflow that improves a specific omics, protein, drug, population-genetics, or literature-curation task.
- Strongest result: Trained on FFPE melanoma samples with matched DNA, FFixR leverages allele-specific read counts, variant features, and mutational signature probabilities.  FFixR removed up to 98% of artefactual mutations while maintaining ~92% recall of true variants.
- Result caveat: This note is generated from PubMed abstract metadata, so detailed validation strength and failure modes still require full text extraction.

### Limitations

- Author-stated limitations: Full text 확인 필요.
- Analyst-judged limitations: Current evidence is abstract-level; exact benchmarks, ablations, runtime, dataset leakage checks, and implementation constraints are not fully verified.
- Missing validation: Independent cohorts, external benchmarks, cross-platform replication, and prospective clinical validation status require paper-specific full text review.
- Weak link between evidence and claim: The local note records the claimed contribution, but does not yet prove it with extracted figures or benchmark tables.

### Final Takeaways

- Main takeaway: Trained on FFPE melanoma samples with matched DNA, FFixR leverages allele-specific read counts, variant features, and mutational signature probabilities.  FFixR removed up to 98% of artefactual mutations while maintaining ~92% recall of true variants.
- Why this matters for healthcare: Improves mutation calling from clinically common FFPE RNA-seq cancer specimens.
- Next-paper idea: Retrieve the full article and extract benchmark datasets, baselines, metrics, ablations, runtime, and practical failure modes.
- Reusable idea for this vault: Use this paper in the Cancer genomics -> Somatic mutation calling branch, then refine the branch after full text extraction.

## Source

- Journal: Bioinformatics
- DOI: https://doi.org/10.1093/bioinformatics/btag405
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42340671/
- Oxford Academic: https://academic.oup.com/bioinformatics
- Oxford Academic advance articles: https://academic.oup.com/bioinformatics/advance-articles
