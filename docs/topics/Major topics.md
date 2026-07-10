---
type: controlled-vocabulary
tags:
  - taxonomy
  - major-topic
---

# Major topics

Predefined major topics for paper classification.

## Active major topics

- [[topics/Rare disease]]
- [[topics/Epigenome]]
- [[topics/Cancer genomics]]
- [[topics/Statistical genetics]]
- [[topics/Single-cell and spatial omics]]
- [[topics/Plant genomics]]
- [[topics/Microbiome genetics]]
- [[topics/Functional genomics]]
- [[topics/Metabolomics and proteomics]]
- [[topics/Biomedical knowledge engineering]]
- [[topics/Protein bioinformatics]]
- [[topics/Computational drug discovery]]
- [[topics/Bioimage informatics]]
- [[topics/Genome assay design]]
- [[topics/Omics workflow tools]]
- [[topics/Comparative genomics]]
- [[topics/Genome sequencing methods]]
- [[topics/Genomic medicine and policy]]

## Classification rule

- Match a new paper to the closest existing major topic first.
- If a paper clearly falls outside active major topics and the user has approved expansion, create a new major topic here.
- After the major topic is selected, match the paper to the closest existing subtopic under that major topic.
- If no subtopic fits, create a new subtopic note and link it from the major topic note.
- Daily watch jobs may report candidates automatically, but paper insertion should preserve this topic -> subtopic -> paper graph shape.
