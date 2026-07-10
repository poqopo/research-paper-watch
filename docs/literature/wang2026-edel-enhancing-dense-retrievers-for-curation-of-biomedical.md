---
type: paper
citekey: "wang2026edel"
title: "EDEL: Enhancing Dense Retrievers for Curation of Biomedical Knowledge Bases"
year: 2026
journal: "Bioinformatics"
status: bioflow-analyzed
major_topic: "Biomedical knowledge engineering"
subtopics:
  - "Knowledge-base literature retrieval"
doi: "10.1093/bioinformatics/btag490"
pmid: "42391609"
url: "https://doi.org/10.1093/bioinformatics/btag490"
abstract_summary: "MOTIVATION: Retrieval of relevant papers from the literature is the first step in curating high-quality biomedical knowledge bases. While BM25 has long been the method of choice, dense retrieval models achieved improved accuracy by embedding queries and documents into dense vector representations. Existing knowledge bases provide a natural source for deriving query-document pairs for training such models."
prior_limitations:
  - "Retrieval of relevant papers from the literature is the first step in curating high-quality biomedical knowledge bases. While BM25 has long been the method of choice, dense retrieval models achieved improved accuracy by embedding queries and documents into dense vector representations."
solution: "We propose EDEL, a novel dense bi-encoder for biomedical knowledge base curation to enable curators to find relevant papers for annotation faster. It introduces a loss function using graded relevance scores instead of binary labels to facilitate learning from partially grounded examples, together with a structured sampling strategy that exposes the model to diverse and hard negative examples during training."
differentiator: "We propose EDEL, a novel dense bi-encoder for biomedical knowledge base curation to enable curators to find relevant papers for annotation faster. It introduces a loss function using graded relevance scores instead of binary labels to facilitate learning from partially grounded examples, together with a structured sampling strategy that exposes the model to diverse and hard negative examples during training."
healthcare_relevance: "Can reduce manual burden in precision oncology and biomedical knowledge-base curation."
datasets: []
methods:
  - "Dense retrieval"
  - "Biomedical knowledge-base curation"
  - "Structured negative sampling"
topics:
  - "Biomedical knowledge engineering"
  - "Knowledge-base literature retrieval"
tags:
  - "paper"
  - "graph-topic"
  - "major-biomedical-knowledge-engineering"
  - "subtopic-knowledge-base-literature-retrieval"
---

# EDEL: Enhancing Dense Retrievers for Curation of Biomedical Knowledge Bases

## Healthcare relevance

Can reduce manual burden in precision oncology and biomedical knowledge-base curation.

## Analysis

- Abstract: MOTIVATION: Retrieval of relevant papers from the literature is the first step in curating high-quality biomedical knowledge bases.  While BM25 has long been the method of choice, dense retrieval models achieved improved accuracy by embedding queries and documents into dense vector representations.  Existing knowledge bases provide a natural source for deriving query-document pairs for training such models.
- Prior limitation: Retrieval of relevant papers from the literature is the first step in curating high-quality biomedical knowledge bases.  While BM25 has long been the method of choice, dense retrieval models achieved improved accuracy by embedding queries and documents into dense vector representations.
- Differentiator: We propose EDEL, a novel dense bi-encoder for biomedical knowledge base curation to enable curators to find relevant papers for annotation faster.  It introduces a loss function using graded relevance scores instead of binary labels to facilitate learning from partially grounded examples, together with a structured sampling strategy that exposes the model to diverse and hard negative examples during training.

## BioProject-style analysis

### Evidence level

- Source level: PubMed record (https://pubmed.ncbi.nlm.nih.gov/42391609/), DOI landing page (https://doi.org/10.1093/bioinformatics/btag490), and Bioinformatics journal pages (https://academic.oup.com/bioinformatics; https://academic.oup.com/bioinformatics/advance-articles).
- Missing source material: Full PDF, figures, tables, supplementary benchmarks beyond PubMed abstract, and exact implementation details were not extracted in this pass.

### Background

- Problem context: MOTIVATION: Retrieval of relevant papers from the literature is the first step in curating high-quality biomedical knowledge bases.  While BM25 has long been the method of choice, dense retrieval models achieved improved accuracy by embedding queries and documents into dense vector representations.  Existing knowledge bases provide a natural source for deriving query-document pairs for training such models.
- Why the problem matters: Can reduce manual burden in precision oncology and biomedical knowledge-base curation.
- Prior work baseline: Retrieval of relevant papers from the literature is the first step in curating high-quality biomedical knowledge bases.  While BM25 has long been the method of choice, dense retrieval models achieved improved accuracy by embedding queries and documents into dense vector representations.
- Gap that remains: Retrieval of relevant papers from the literature is the first step in curating high-quality biomedical knowledge bases.  While BM25 has long been the method of choice, dense retrieval models achieved improved accuracy by embedding queries and documents into dense vector representations.

### Overview

- Core question: How does this paper advance Knowledge-base literature retrieval within the broader Biomedical knowledge engineering topic?
- Paper's framing: MOTIVATION: Retrieval of relevant papers from the literature is the first step in curating high-quality biomedical knowledge bases.  While BM25 has long been the method of choice, dense retrieval models achieved improved accuracy by embedding queries and documents into dense vector representations.
- Input / cohort / material: Dataset details require full text review; PubMed abstract gives the high-level task and evaluation setting.
- Output / endpoint: We propose EDEL, a novel dense bi-encoder for biomedical knowledge base curation to enable curators to find relevant papers for annotation faster.  It introduces a loss function using graded relevance scores instead of binary labels to facilitate learning from partially grounded examples, together with a structured sampling strategy that exposes the model to diverse and hard negative examples during training.
- Expected clinical or biological impact: Can reduce manual burden in precision oncology and biomedical knowledge-base curation.

### Methods

- Method type: Dense retrieval, Biomedical knowledge-base curation, Structured negative sampling
- Key input: Input material requires full text review.
- Core processing step: The PubMed abstract supports the high-level method classification; full algorithmic and implementation details still require article/PDF review.
- Comparator / baseline: Retrieval of relevant papers from the literature is the first step in curating high-quality biomedical knowledge bases.  While BM25 has long been the method of choice, dense retrieval models achieved improved accuracy by embedding queries and documents into dense vector representations.
- Output: We propose EDEL, a novel dense bi-encoder for biomedical knowledge base curation to enable curators to find relevant papers for annotation faster.  It introduces a loss function using graded relevance scores instead of binary labels to facilitate learning from partially grounded examples, together with a structured sampling strategy that exposes the model to diverse and hard negative examples during training.
- Why this differs from prior methods: We propose EDEL, a novel dense bi-encoder for biomedical knowledge base curation to enable curators to find relevant papers for annotation faster.  It introduces a loss function using graded relevance scores instead of binary labels to facilitate learning from partially grounded examples, together with a structured sampling strategy that exposes the model to diverse and hard negative examples during training.

### Figures / Tables

- PDF/figure 확인 필요. Current local note does not include figure panels, captions, table rows, supplementary figures, or benchmark tables.

### Results

#### Dataset / cohort results

- Dataset or cohort: Dataset and benchmark details require full text review.
- Purpose: Evaluate the paper's contribution to Knowledge-base literature retrieval.
- Scale: Exact sample size, benchmark count, and parameter settings require full text review unless stated in the abstract summary.
- Baseline / comparator: Retrieval of relevant papers from the literature is the first step in curating high-quality biomedical knowledge bases.  While BM25 has long been the method of choice, dense retrieval models achieved improved accuracy by embedding queries and documents into dense vector representations.
- Metric / endpoint: Full metric extraction requires article/PDF review; current endpoint is summarized as: We propose EDEL, a novel dense bi-encoder for biomedical knowledge base curation to enable curators to find relevant papers for annotation faster.  It introduces a loss function using graded relevance scores instead of binary labels to facilitate learning from partially grounded examples, together with a structured sampling strategy that exposes the model to diverse and hard negative examples during training.
- Main quantitative result: Exact quantitative result requires full text review.
- Qualitative result: We propose EDEL, a novel dense bi-encoder for biomedical knowledge base curation to enable curators to find relevant papers for annotation faster.  It introduces a loss function using graded relevance scores instead of binary labels to facilitate learning from partially grounded examples, together with a structured sampling strategy that exposes the model to diverse and hard negative examples during training.
- How this supports the paper's claim: The PubMed abstract states the main method or resource contribution and supports this taxonomy placement.

#### Overall result pattern

- Repeated pattern: This paper proposes a computational method, model, database, or workflow that improves a specific omics, protein, drug, population-genetics, or literature-curation task.
- Strongest result: We propose EDEL, a novel dense bi-encoder for biomedical knowledge base curation to enable curators to find relevant papers for annotation faster.  It introduces a loss function using graded relevance scores instead of binary labels to facilitate learning from partially grounded examples, together with a structured sampling strategy that exposes the model to diverse and hard negative examples during training.
- Result caveat: This note is generated from PubMed abstract metadata, so detailed validation strength and failure modes still require full text extraction.

### Limitations

- Author-stated limitations: Full text 확인 필요.
- Analyst-judged limitations: Current evidence is abstract-level; exact benchmarks, ablations, runtime, dataset leakage checks, and implementation constraints are not fully verified.
- Missing validation: Independent cohorts, external benchmarks, cross-platform replication, and prospective clinical validation status require paper-specific full text review.
- Weak link between evidence and claim: The local note records the claimed contribution, but does not yet prove it with extracted figures or benchmark tables.

### Final Takeaways

- Main takeaway: We propose EDEL, a novel dense bi-encoder for biomedical knowledge base curation to enable curators to find relevant papers for annotation faster.  It introduces a loss function using graded relevance scores instead of binary labels to facilitate learning from partially grounded examples, together with a structured sampling strategy that exposes the model to diverse and hard negative examples during training.
- Why this matters for healthcare: Can reduce manual burden in precision oncology and biomedical knowledge-base curation.
- Next-paper idea: Retrieve the full article and extract benchmark datasets, baselines, metrics, ablations, runtime, and practical failure modes.
- Reusable idea for this vault: Use this paper in the Biomedical knowledge engineering -> Knowledge-base literature retrieval branch, then refine the branch after full text extraction.

## Source

- Journal: Bioinformatics
- DOI: https://doi.org/10.1093/bioinformatics/btag490
- PubMed: https://pubmed.ncbi.nlm.nih.gov/42391609/
- Oxford Academic: https://academic.oup.com/bioinformatics
- Oxford Academic advance articles: https://academic.oup.com/bioinformatics/advance-articles
