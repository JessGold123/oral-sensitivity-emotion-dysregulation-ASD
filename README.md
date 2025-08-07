# The Taste of Regulation: Oral Sensitivity, Selective Eating, and Emotion Dysregulation in Autism

## Overview

This repository contains the proposal, documentation, and planned analysis code for a project exploring how oral sensory sensitivity contributes to emotion dysregulation in children with autism spectrum disorder (ASD). Drawing on data from the NIH Data Archive (NDA), the project tests a mediation model with selective eating as a pathway and examines how parental mental health moderates these effects. The goal is to better understand sensory-emotional pathways in autism and how they interact with family context.

---

## Project Aims

**Aim 1**: Test whether oral sensory sensitivity (taste, texture, smell) is associated with increased emotion dysregulation in autistic children.  
> _Hypothesis_: Greater oral sensitivity will predict higher scores on CBCL emotion dysregulation subscales.

**Aim 2**: Test whether selective eating mediates the relationship between oral sensory sensitivity and emotion dysregulation.  
> _Hypothesis_: The effect of oral sensitivity on dysregulation will be partially explained by selective eating behaviors.

**Aim 3**: Test whether parental mental health moderates the relationship between selective eating and emotion dysregulation.  
> _Hypothesis_: The selective eating–dysregulation link will be stronger when parental mental health challenges are higher.

---

## Data Sources

Analyses will use data from the following NDA datasets, both of which include relevant measures:

- [NDA Study #2804](https://nda.nih.gov/edit_collection.html?id=2804)
- [NDA Study #3005](https://nda.nih.gov/edit_collection.html?id=3005)

Due to NDA data sharing policies, raw data are **not included** in this repository.

---

## Measures

| Construct               | Instrument                                |
|------------------------|--------------------------------------------|
| Oral Sensory Sensitivity | Sensory Profile (SP), Oral Processing items |
| Selective Eating        | Child Eating Behavior Questionnaire (CEBQ) |
| Emotion Dysregulation   | Child Behavior Checklist (CBCL) subscales  |
| Parental Mental Health  | Adult Behavior Checklist (ABCL)            |
| Covariates              | Age, Sex, IQ, ASD Severity (SRS)           |


---

## Methods Summary

- Sensory dimensions (taste, texture, smell) derived via PCA.
- Emotion dysregulation modeled via linear regression (Aim 1), mediation (Aim 2), and moderation (Aim 3).
- False Discovery Rate (FDR) correction applied across outcome subscales within each modality.
- Bootstrapped indirect effects and interaction plots used for interpretation.

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

