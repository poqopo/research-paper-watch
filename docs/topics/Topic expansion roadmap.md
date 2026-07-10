---
type: planning-note
tags:
  - taxonomy
  - planning
---

# Topic expansion roadmap

This note is the controlled backlog for adding new paper branches. Major topics stay user-controlled; subtopics can be activated when enough papers repeatedly point to the same branch.

## Current major topics

- [[topics/Rare disease]]
- [[topics/Epigenome]]

## Activation rule

- Keep a candidate as backlog until at least three relevant papers or a clear user request supports it.
- Prefer matching a new paper to an existing active subtopic before creating a new one.
- Do not create a new major topic automatically. Add a major topic only after the user explicitly adds it to [[topics/Major topics]].
- When activating a subtopic, create `papers/topics/<Subtopic>.md`, link it under the major topic's `## Branches`, then regenerate `papers/Research Paper Explorer.html`.

## Rare disease candidate subtopics

- Structural variants and long-read genomics: SVs, repeat expansions, hard-to-map regions, phasing, and long-read clinical diagnosis.
- Noncoding and regulatory variants: promoters, enhancers, UTRs, deep intronic variation, and regulatory pathogenic mechanisms.
- Splicing and RNA diagnostics: RNA-seq diagnosis, aberrant splicing, aberrant expression, allele-specific expression, and transcriptome rescue of negative DNA tests.
- Deep phenotyping and phenotype extraction: HPO extraction, EHR NLP, facial/gestalt matching, phenotype quality control, and phenotype similarity metrics.
- Reanalysis and data sharing: periodic reanalysis, Matchmaker-style exchange, federated cohorts, and diagnosis after negative first-pass testing.
- Functional validation: CRISPR screens, cellular assays, model organisms, organoids, and experimental validation of genes or variants.
- Newborn, prenatal, and rapid diagnosis: NICU/PICU sequencing, prenatal diagnosis, turnaround time, and implementation outcomes.
- Therapeutic actionability: papers that connect diagnosis to treatment, surveillance, trial matching, or management changes.

## Epigenome candidate subtopics

- Single-cell perturbation epigenomics: perturb-seq, CRISPR perturbation, regulatory element perturbation, and causal chromatin programs.
- Epigenome editing: dCas9 methylation, acetylation, enhancer silencing, and therapeutic epigenome intervention.
- Spatial epigenomics in disease tissue: spatial ATAC, spatial methylation, spatial multiome, and tissue microenvironment mapping.
- Disease regulatory variant interpretation: linking variants to chromatin state, enhancer-gene maps, eQTL/caQTL/meQTL, and disease mechanisms.
- Chromatin foundation models: pretrained sequence or multiomic models for regulatory prediction, cell-state transfer, and variant effect prediction.
- Drug response and resistance: epigenomic predictors of treatment response, resistance states, and therapy-induced chromatin remodeling.
- Liquid biopsy fragmentomics plus methylation: cfDNA fragment patterns, methylation, tissue-of-origin, and early detection integration.
- Aging and prevention clocks: intervention-sensitive clocks, exposure timing, disease-risk prediction, and prevention endpoints.

## Possible future major topics

- Transcriptome: if RNA diagnostics, splicing, and temporal gene-expression dynamics outgrow rare disease and epigenome branches.
- Clinical genomics: if implementation, diagnosis, variant interpretation, and clinical workflow papers become the dominant thread.
- Multi-omics AI: if foundation models, multi-modal representation learning, and clinical decision support become a cross-topic center.
- Population biobank genetics: if UKB, BBJ, KoGES, MVP, and other biobank-scale analyses become a recurring paper stream.
- Proteomics and biomarkers: if plasma proteomics, metabolomics, and biomarker discovery become frequent enough to stand alone.

## Daily watch scope

- Nature Genetics should be scanned daily for new primary research papers.
- Candidate papers should be reported even when they do not fit the active major topics.
- Automatic insertion into the vault should require a semantic classification step, because title/abstract matching alone will misclassify edge cases.
