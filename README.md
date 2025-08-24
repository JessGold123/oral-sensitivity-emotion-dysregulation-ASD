# The Taste of Regulation: Oral Sensitivity, Emotion Dysregulation, and Family Context in Autism

## Overview

This repository contains the proposal, documentation, and planned analysis code for a project exploring how oral sensory sensitivity contributes to emotion dysregulation in children with autism spectrum disorder (ASD). The study leverages large-scale data from the NIH Data Archive (NDA) and applies a systems-level perspective by examining both child traits and family context.

Novel aspects of this project include:
- **Data-driven measurement**: Harmonizing oral/taste/smell items across multiple Sensory Profile variants using exploratory factor analysis (EFA).
- **Focus on emotion regulation**: Positioning oral sensory sensitivity as a regulatory trait, moving beyond feeding behavior alone.
- **Family systems perspective**: Testing parental mental health as a moderator of child outcomes.
- **Exploratory pathways**: Evaluating selective eating as a potential mediator between sensory sensitivity and dysregulation.

---

## Project Aims

**Aim 1** (Direct Effects): Test whether oral sensory sensitivities is associated with increased emotion dysregulation in autistic children.  
> _Hypothesis_: Greater oral sensitivity will predict higher scores on the CBCL Dysregulation Profile.

**Aim 2** (Moderation): Test whether parental mental health moderates the relationship between selective eating and emotion dysregulation. 
> _Hypothesis_: Associations will be stronger when parental mental health challenges are higher.

**Aim 3** (Exploratory Mediation): Test whether selective eating mediates the relationship between oral sensory sensitivity and emotion dysregulation.   
> _Hypothesis_: Selective eating will account for part of the association. Analyses will be framed as hypothesis-generating.

---

## Data Sources

Analyses will use data from the following NDA datasets, all of which include relevant measures:
- [NDA Study #2021](https://nda.nih.gov/edit_collection.html?id=2021)
- [NDA Study #2804](https://nda.nih.gov/edit_collection.html?id=2804)
- [NDA Study #2828](https://nda.nih.gov/edit_collection.html?id=2828)
- [NDA Study #2834](https://nda.nih.gov/edit_collection.html?id=2834)
- [NDA Study #3005](https://nda.nih.gov/edit_collection.html?id=3005)

Selective eating data (CEBQ) are only available in #2804 and #3005.
Due to NDA data sharing policies, raw data are **not included** in this repository.

---

## Measures

| Construct               | Instrument                                |
|------------------------|--------------------------------------------|
| Oral Sensory Sensitivity | Variations of the Sensory Profile (AASP, SP, SSP), Oral Processing items |
| Selective Eating        | Child Eating Behavior Questionnaire (CEBQ) |
| Emotion Dysregulation   | Child Behavior Checklist Dysregulation Profile (CBCL-DP) |
| Parental Mental Health  | Adult Behavior Checklist (ABCL)            |
| Covariates              | Age, Race, Sex, ASD Severity (SRS)           |


---

## Methods Summary
- Harmonization: Oral/taste/smell items will be reverse-scored as necessary to ensure higher scores indicate greeater sensitivity; EFA used to derive modality-level sensitivity scores.
- Aim 1: Linear regressions testing direct effects of oral sensitivity modalities on CBCL-DP.
- Aim 2: Moderation models testing oral sensitivity modalities × parental mental health interactions.
- Aim 3: Exploratory mediation models testing selective eating as a pathway.
- Controls: Age, sex, race, ASD severity (SRS).
- Statistical rigor: False Discovery Rate (FDR) corrections for multiple testing; bootstrap resampling (5,000 resamples) for mediation; interaction plots for moderation.

---

## Proposal Updates
- Version 2 uplodaed on August 18, 2025. Due to surprisingly small sample sizes from the two datasets originally selected, we pivoted to include all datasets from the NDA archive that collected data from autistic individuals via the CBCL and a variation of the Sensory Profile (SP, SSP, AASP).
- Version 3 uploaded on August 24, 2025. 5 of the 10 initially selected datasets (#2026, #2251, #2253, #2281, #2900) were excluded due to missing data. Of the five included, #2828 did not report CBCL item scores, so the 80% item completeness rule could not be applied to this dataset. #2834 only reported 10 of 12 oral sensory processing items but was included to increase sample size. EFA decisions were added.
  
---

## License

- **Code and analysis scripts** are licensed under the [MIT License](https://opensource.org/licenses/MIT).
- **Proposal and documentation** (in `proposal/`) are licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

Please cite this work if used for academic purposes.

---

## Author

Jess Goldschlager  
Postbaccalaureate Research Fellow  
National Institutes of Health (NIH) – Sensory Science and Metabolism Lab  
[jess.goldschlager@gmail.com](mailto:jess.goldschlager@gmail.com)

