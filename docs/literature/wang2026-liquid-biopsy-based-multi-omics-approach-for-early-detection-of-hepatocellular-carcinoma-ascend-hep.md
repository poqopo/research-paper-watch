---
type: paper
citekey: "wang2026ascendhep"
title: "Liquid biopsy-based multi-omics approach for early detection of hepatocellular carcinoma (ASCEND-Hep): a multiphase prospective development and validation study."
year: 2026
journal: "BMC Medicine"
status: bioflow-analyzed
major_topic: "Epigenome"
subtopics:
  - "Cancer liquid biopsy"
doi: "10.1186/s12916-026-05032-2"
pmid: "42410425"
url: "https://doi.org/10.1186/s12916-026-05032-2"
abstract_summary: "ASCEND-Hep prospectively evaluates cfDNA methylation, mutation, and AFP for hepatocellular carcinoma early detection. In 635 participants for model development/validation, 797 external validation subjects, and 452 community-recruited high-risk individuals, the methylation-based signal outperformed AFP and mutation-only models. The locked model integrating cfDNA methylation and AFP achieved 91.9% overall sensitivity and 98.4% specificity in independent validation, with 83.3% stage 0 sensitivity; in high-risk individuals it showed 92.9% sensitivity, 90.6% specificity, 24.1% PPV, and 99.7% NPV."
prior_limitations:
  - "Ultrasound and AFP-based HCC surveillance miss many early cancers and have imperfect adherence/performance in high-risk populations."
  - "Mutation-based cfDNA signals alone may be too sparse for sensitive early HCC detection."
solution: "Develop and validate a multi-omics early detection model centered on cfDNA methylation, with AFP integration and mutation data tested as an additional component."
differentiator: "The study is multiphase and prospective, includes external validation, and tests the locked model in community-recruited high-risk individuals rather than only case-control samples."
healthcare_relevance: "This is directly relevant to HCC surveillance because it targets high-risk populations and reports PPV/NPV in a screening-like setting."
datasets:
  - "635 participants for training/validation: 288 HCC and 347 non-HCC"
  - "797-subject external validation cohort: 160 HCC and 637 non-HCC"
  - "452 community-recruited high-risk individuals"
methods:
  - "cfDNA methylation profiling"
  - "AFP integration"
  - "Mutation signal evaluation"
  - "Prospective model development and locked validation"
topics:
  - "Epigenome"
  - "Cancer liquid biopsy"
tags:
  - paper
  - graph-topic
  - major-epigenome
  - subtopic-cancer-liquid-biopsy
---
# Liquid biopsy-based multi-omics approach for early detection of hepatocellular carcinoma (ASCEND-Hep): a multiphase prospective development and validation study.

## Healthcare relevance

HCC 고위험군 surveillance에서 기존 ultrasound/AFP의 한계를 보완할 수 있는 cfDNA methylation 중심 혈액검사 후보이다. 특히 high-risk screening-like cohort에서 PPV/NPV까지 제시해 실제 선별검사 적용 가능성을 평가하기 좋다.

## BioProject-style analysis

### Evidence level

- Source level: PubMed/E-utilities abstract and DOI metadata checked on 2026-07-07.
- Source records: PMID 42410425, DOI 10.1186/s12916-026-05032-2.
- Missing source material: Full PDF, figure panels, supplementary marker list, model coefficients, calibration plots, and subgroup tables were not extracted.

### Background

- Problem context: HCC는 암 사망의 주요 원인이고, 고위험군에서 조기 발견이 예후를 좌우한다.
- Why the problem matters: 실제 surveillance에서는 sensitivity, specificity뿐 아니라 high-risk population에서 PPV/NPV와 downstream workup burden이 중요하다.
- Prior work baseline: AFP와 imaging은 조기 병변에서 성능이 제한적이고, cfDNA mutation signal은 early-stage tumor fraction이 낮으면 불리하다.
- Gap that remains: methylation이 mutation/AFP보다 얼마나 더 안정적인 screening signal인지 prospective validation이 필요했다.

### Overview

- Core question: cfDNA methylation, mutation, AFP를 결합하면 HCC early detection에서 기존 AFP보다 실질적으로 나은 성능을 낼 수 있는가?
- Paper's framing: methylation 중심 MOED model을 개발하고 외부/고위험군 cohort에서 잠근 모델을 검증한다.
- Input / cohort / material: training/validation 635명, external validation 797명, community high-risk 452명.
- Output / endpoint: HCC detection sensitivity/specificity, stage 0 sensitivity, high-risk setting PPV/NPV.
- Expected clinical or biological impact: 고위험군 HCC surveillance에서 혈액 기반 triage 또는 보조 검사로 확장 가능하다.

### Methods

- Method type: cfDNA methylation 기반 early detection model with multi-analyte integration.
- Key input: peripheral blood cfDNA methylation, mutation data, AFP.
- Core processing step: cfDNA methylation model을 개발하고 AFP >= 400 ng/mL 통합 및 mutation 추가 효과를 비교했다.
- Comparator / baseline: AFP-only and mutation-based models.
- Output: locked MOED model.
- Why this differs from prior methods: 단일 case-control 개발이 아니라 prospective collection, external validation, community high-risk blind testing이 포함된다.

### Figures / Tables

- PDF/figure 확인 필요. PubMed abstract에서 성능 수치는 확인되지만 ROC curves, marker list, calibration, subgroup breakdown은 full text 확인이 필요하다.

### Results

- Development/validation scale: 635 participants, including 288 HCC and 347 non-HCC.
- External validation scale: 797 subjects, including 160 HCC and 637 non-HCC.
- High-risk blind test: 452 community-recruited high-risk individuals.
- Validation result: methylation+AFP MOED increased sensitivity from 87.1% to 88.8% at 95.7% specificity; mutation did not improve performance.
- Independent validation: 91.9% overall sensitivity, 83.3% stage 0 sensitivity, 98.4% specificity.
- High-risk setting: 92.9% sensitivity, 90.6% specificity, 24.1% PPV, 99.7% NPV.
- How this supports the claim: methylation is the dominant signal, AFP gives a modest additive benefit, and mutation appears less useful for this early-detection setting.

### Limitations

- Author-stated limitations: full text 확인 필요.
- Analyst-judged limitations: high-risk PPV is still modest, so positive calls would require careful downstream diagnostic routing.
- Missing validation: cost-effectiveness, ultrasound head-to-head prospective screening outcomes, and interval cancer reduction need further evidence.
- Weak link between evidence and claim: abstract-level review does not expose marker selection, threshold tuning, or locked model governance details.

### Final Takeaways

- Main takeaway: ASCEND-Hep is one of the strongest recent cfDNA methylation HCC early-detection studies because it includes external validation and high-risk population testing.
- Why this matters for healthcare: 높은 NPV는 high-risk surveillance 보조 검사로 매력적이지만, PPV와 follow-up burden이 implementation의 핵심 변수다.
- Next-paper idea: Compare methylation+AFP against ultrasound+AFP in a prospective surveillance pathway with diagnostic workup cost and false-positive burden.
- Reusable idea for this vault: `Cancer liquid biopsy` branch에서 "methylation as primary signal, protein marker as small additive signal" 패턴의 대표 예시로 사용한다.

## Source

- PubMed: https://pubmed.ncbi.nlm.nih.gov/42410425/
- DOI: https://doi.org/10.1186/s12916-026-05032-2

