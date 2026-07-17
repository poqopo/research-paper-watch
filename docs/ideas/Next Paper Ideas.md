# Next Paper Ideas

- Generated: 2026-07-17T23:00:11.014Z
- Source papers: 283
- Latest year in vault: 2026
- Minimum references per idea: 6
- Minimum overall score: 95
- Score labels: Overall = final priority score; Trend = recent topic momentum; Novelty = gap/newness; Feasibility = reference/data/method support.
- Display rule: the current idea list only shows Overall 95+ ideas.

## High-priority Ideas

### Cross-cohort Spatial transcriptomics enhancement atlas for disease-relevant cell-state prediction

- Topic: Single-cell and spatial omics / Spatial transcriptomics enhancement
- References used: 6
- Overall: 98; trend 100; novelty 98; feasibility 95
- Question: Can Spatial transcriptomics enhancement be made reproducible across tissues, platforms, and disease cohorts?
- Why now: 6 recent paper(s) since 2025 and 6 total paper(s) in this branch suggest active movement around spatial, transcriptomics, attention, framework.
- Gap: However, integrating transcriptomic profiles and pathology images remains a challenge.
- Contribution: Create a platform-aware integration and validation workflow that separates robust cell-state signals from cohort-specific artifacts.
- Data needed: spatial transcriptomics, H&E-stained histology images, matched single-cell or spatial profiles, disease annotations, and held-out tissue cohorts.
- Method: Spatial transcriptomics, Bidirectional attention transformer, Cell segmentation
- Evidence:
  - [[literature/wang2026-genot-generative-optimal-transport-enables-spatiotemporal-interpolation-and-generation-in|GenOT: generative optimal transport enables spatiotemporal interpolation and generation in cross-platform spatial transcriptomics.]] (2026, Genome Biology)
  - [[literature/wang2026-micnet-integrating-spatially-resolved-transcriptomes-and-pathology-images-by-contrastive|MicNet: integrating spatially resolved transcriptomes and pathology images by contrastive deep neural network.]] (2026, Genome Biology)
  - [[literature/liu2026-ressat-enhancing-spatial-transcriptomics-prediction-from-h-and-e-stained|ResSAT: enhancing spatial transcriptomics prediction from H&E-stained histology images with an interactive spot transformer.]] (2026, Genome Biology)
  - [[literature/ma2026-segjointgene-joint-cell-segmentation-and-spatial-gene-prioritization|SegJointGene: joint cell segmentation and spatial gene prioritization by information entropy guided convolutional neural networks]] (2026, Bioinformatics)
  - [[literature/zhang2026-sinter3d-continuous-3d-reconstruction-of-spatial-transcriptomics-via-implicit-neural|SINTER3D: continuous 3D reconstruction of spatial transcriptomics via implicit neural representations.]] (2026, Genome Biology)

### Phenotype-aware Gene ranking framework for unresolved rare disease diagnosis

- Topic: Rare disease / Gene ranking
- References used: 17
- Overall: 98; trend 100; novelty 94; feasibility 100
- Question: Can Gene ranking be improved by combining phenotype context, variant evidence, and literature-derived disease mechanisms?
- Why now: 11 recent paper(s) since 2025 and 17 total paper(s) in this branch suggest active movement around variants, gene, allelic, individuals.
- Gap: 기존 Gene ranking 연구는 대규모 데이터, 재현 가능한 benchmark, 또는 임상/생물학적 해석 연결이 충분하지 않았다.
- Contribution: Build a clinically interpretable ranking workflow that links patient phenotype, variant/gene evidence, and disease mechanism priors instead of treating each evidence source separately.
- Data needed: Undiagnosed rare disease cohorts with HPO terms, WGS or exome variants, curated disease genes, and orthogonal evidence such as methylation episignatures when available.
- Method: Disease-gene association analysis, Hedgehog responsiveness assay, Human rare-disease cohort aggregation
- Evidence:
  - [[literature/lambton2026-bi-allelic-atg12-variants-impair-autophagy-and-cause-a-neurodevelopmental|Bi-allelic ATG12 variants impair autophagy and cause a neurodevelopmental disorder.]] (2026, The American Journal of Human Genetics)
  - [[literature/chan2026-bi-allelic-loss-of-function-variants-in-tmem63b-cause-syndromic|Bi-allelic loss-of-function variants in TMEM63B cause syndromic surfactant dysfunction disorder.]] (2026, The American Journal of Human Genetics)
  - [[literature/smith2026-bi-allelic-missense-variants-in-human-gpn2-result|Bi-allelic missense variants in human GPN2 result in Perrault syndrome.]] (2026, The American Journal of Human Genetics)
  - [[literature/lemire2026-bi-allelic-variants-in-cdk20-cause-a-severe-ciliopathy-with-midline-brain-and-facial-anomalies|Bi-allelic variants in CDK20 cause a severe ciliopathy with midline brain and facial anomalies.]] (2026, The American Journal of Human Genetics)
  - [[literature/tan2026-bi-allelic-variants-in-ndufa5-cause-a-mitochondriopathy-with-complex|Bi-allelic variants in NDUFA5 cause a mitochondriopathy with complex I deficiency.]] (2026, The American Journal of Human Genetics)

### Translational Cancer liquid biopsy model linking epigenomic state to healthcare endpoints

- Topic: Epigenome / Cancer liquid biopsy
- References used: 18
- Overall: 98; trend 100; novelty 93; feasibility 100
- Question: Can Cancer liquid biopsy move from descriptive maps toward patient-level prediction, stratification, or diagnosis?
- Why now: 9 recent paper(s) since 2025 and 18 total paper(s) in this branch suggest active movement around methylation, cancer, cfdna, early.
- Gap: A promising methylation classifier still needed independent validation closer to screening-test use.
- Contribution: Train and benchmark an interpretable epigenomic model that connects regulatory state, disease relevance, and external validation across cohorts.
- Data needed: 114 healthy controls, 12 neoadjuvant chemotherapy monitoring patients, 130 healthy controls, paired clinical labels, disease-associated variants, and external validation cohorts.
- Method: cfDNA methylation profiling, 40 CpG-region panel, AFP integration
- Evidence:
  - [[literature/bacolod2026-a-neural-network-enabled-enzymatic-cfdna-methylation-assay-for-colorectal-cancer-early-detection|A Neural Network-Enabled, Enzymatic cfDNA Methylation Assay for Colorectal Cancer Early Detection.]] (2026, Cancer Prevention Research)
  - [[literature/lin2026-cell-free-dna-methylation-biomarkers-for-the-early-detection-and-tumor-burden-monitoring-of-gastric-cancer|Cell-free DNA methylation biomarkers for the early detection and tumor burden monitoring of gastric cancer.]] (2026, NPJ Precision Oncology)
  - [[literature/zhu2026-clinical-validation-of-a-multi-model-blood|Clinical validation of a multi-model blood cfDNA methylation assay for early-stage gastrointestinal cancer screening]] (2026, Journal of Advanced Research)
  - [[literature/jeong2026-enhanced-multicancer-cfdna|Enhanced multicancer screening assay through whole-genome methylation sequencing-based multimodal cell-free DNA analysis]] (2026, Exp Mol Med)
  - [[literature/usrof2026-evaluating-circulating-tumor-dna-methylation-patterns-of-a-multi-gene-panel-for-colorectal-cancer-diagnosis|Evaluating circulating tumor DNA methylation patterns of a multi-gene panel for colorectal cancer diagnosis: A pilot study.]] (2026, Clinica Chimica Acta)

### Translational Rare disease episignatures model linking epigenomic state to healthcare endpoints

- Topic: Epigenome / Rare disease episignatures
- References used: 13
- Overall: 98; trend 100; novelty 95; feasibility 96
- Question: Can Rare disease episignatures move from descriptive maps toward patient-level prediction, stratification, or diagnosis?
- Why now: 8 recent paper(s) since 2025 and 13 total paper(s) in this branch suggest active movement around methylation, episignature, dna, diagnostic.
- Gap: Array-based episignatures are powerful but can be costly or too broad for targeted confirmation in known syndromes.
- Contribution: Train and benchmark an interpretable epigenomic model that connects regulatory state, disease relevance, and external validation across cohorts.
- Data needed: long-read sequencing, Progeria syndrome caused by gain-of-function DNMT3A mutations, paired clinical labels, disease-associated variants, and external validation cohorts.
- Method: DNA methylation pathology analysis, DNA methylation profiling, Long-read sequencing analysis
- Evidence:
  - [[literature/wang2026-a-next-generation-episignature-for-kabuki-syndrome-enables-fine-mapping|A next-generation episignature for Kabuki syndrome enables fine mapping of the impact of KMT2D variants to inform precision medicine.]] (2026, The American Journal of Human Genetics)
  - [[literature/sarni2026-a-progeria-syndrome-links-dna-hypermethylation-to-age|A progeria syndrome links DNA hypermethylation to age-related pathology]] (2026, Nature Genetics)
  - [[literature/quarello2026-dna-methylation-episignature-as-a-novel-diagnostic|DNA Methylation Episignature as a Novel Diagnostic Tool for Diamond-Blackfan Anemia Syndrome]] (2026, American J Hematol)
  - [[literature/van-der-laan2026-dna-methylation-episignature-for-smith-magenis-and|DNA methylation episignature for Smith-Magenis and Potocki-Lupski syndromes: a mirror perspective]] (2026, Eur J Hum Genet)
  - [[literature/tkemladze2026-evaluating-dna-methylation-episignatures-as-a-first|Evaluating DNA methylation episignatures as a first-tier diagnostic test in individuals with suspected genetic disorders]] (2026, Eur J Hum Genet)

### Function-aware GWAS disease genetics model for ancestry-robust genetic discovery

- Topic: Statistical genetics / GWAS disease genetics
- References used: 6
- Overall: 97; trend 100; novelty 98; feasibility 91
- Question: Can GWAS disease genetics improve genetic discovery by adding regulatory, functional, and ancestry-aware priors?
- Why now: 6 recent paper(s) since 2025 and 6 total paper(s) in this branch suggest active movement around wide, ancestry, association, multi.
- Gap: Alzheimer disease (AD) risk differs across ancestral populations, yet most genetic studies have focused on non-Hispanic White (NHW) cohorts.
- Contribution: Combine association evidence with functional annotations and cross-population calibration to reduce false prioritization and improve portability.
- Data needed: GWAS summary statistics, GWAS summary statistics, functional annotations, ancestry labels, and replication cohorts.
- Method: GWAS, Genome-wide association analysis, Single-cell analysis
- Evidence:
  - [[literature/kang2026-a-flexible-and-unified-framework-for-single-and-multi-outcome|A flexible and unified framework for single- and multi-outcome Mendelian randomization using summary statistics.]] (2026, The American Journal of Human Genetics)
  - [[literature/ruan2026-discodivas-leveraging-genetic-ancestry-continuum-information-to-interpolate-prs-for|DiscoDivas: Leveraging genetic-ancestry continuum information to interpolate PRS for admixed populations.]] (2026, The American Journal of Human Genetics)
  - [[literature/shi2026-genome-wide-analysis-implicates-inner-ear-development-in-meniere-disease|Genome-wide analysis implicates inner ear development in Ménière disease.]] (2026, The American Journal of Human Genetics)
  - [[literature/li2026-genome-wide-association-study-and-predictors-of-neonatal-blood-cell|Genome-wide association study and predictors of neonatal blood cell traits in Hispanic newborns.]] (2026, The American Journal of Human Genetics)
  - [[literature/alkhairo2026-linkage-disequilibrium-and-allelic-heterogeneity-explain-variation-in-coronary-artery|Linkage disequilibrium and allelic heterogeneity explain variation in coronary artery disease risk at 9p21 across populations and reduced effect in Africans.]] (2026, The American Journal of Human Genetics)

### Phenotype-aware Variant ranking framework for unresolved rare disease diagnosis

- Topic: Rare disease / Variant ranking
- References used: 13
- Overall: 95; trend 92; novelty 95; feasibility 100
- Question: Can Variant ranking be improved by combining phenotype context, variant evidence, and literature-derived disease mechanisms?
- Why now: 3 recent paper(s) since 2025 and 13 total paper(s) in this branch suggest active movement around variant, variants, rare, phenotype.
- Gap: Although expert oversight remains essential and tool use adds cost, these results show that contextual guidance can compensate for limited model capacity.
- Contribution: Build a clinically interpretable ranking workflow that links patient phenotype, variant/gene evidence, and disease mechanism priors instead of treating each evidence source separately.
- Data needed: Undiagnosed rare disease cohorts with HPO terms, WGS or exome variants, curated disease genes, and orthogonal evidence such as methylation episignatures when available.
- Method: Data augmentation, Large language model, Polygenic score modeling
- Evidence:
  - [[literature/mialland2026-fitness-translocation-improving-variant-effect-prediction-with-biologically|Fitness translocation: improving variant effect prediction with biologically-grounded data augmentation]] (2026, Bioinformatics)
  - [[literature/baya2026-individuals-who-deviate-from-polygenic-expectation-are-enriched-for-damaging|Individuals who deviate from polygenic expectation are enriched for damaging variants in genes linked to rare disease.]] (2026, The American Journal of Human Genetics)
  - [[literature/everton2026-marrvel-mcp-an-agentic-interface-for-mendelian-disease-discovery-via|MARRVEL-MCP: An agentic interface for Mendelian disease discovery via tool-augmented context engineering.]] (2026, The American Journal of Human Genetics)
  - [[literature/stenton2024-critical-assessment-variant-prioritization-rare-genomes|Critical assessment of variant prioritization methods for rare disease diagnosis within the rare genomes project]] (2024, Hum Genomics)
  - [[literature/althagafi2024-embedpvp-neuro-symbolic-variant-prioritization|Prioritizing genomic variants through neuro-symbolic, knowledge-enhanced learning]] (2024, Bioinformatics)

