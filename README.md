# MIRA-Net: Modality-Invariant Residual Adversarial Network for Cross-Cohort Parkinson's Disease Detection

Official implementation of **MIRA-Net**, a framework for cross-cohort representation learning using acoustic speech and beta-band MEG biomarkers for Parkinson's disease detection.

---

## Overview

MIRA-Net (Modality-Invariant Residual Adversarial Network) is a cross-cohort representation learning framework for Parkinson's disease detection that integrates acoustic speech and beta-band MEG biomarkers acquired from independent participant cohorts. The framework learns modality-invariant and participant-independent latent representations through residual representation learning, adversarial domain adaptation, and supervised contrastive alignment. MIRA-Net is designed to mitigate cross-cohort and cross-modality variability while preserving disease-discriminative information, resulting in improved generalization across heterogeneous biomedical datasets.

The framework integrates:
- Acoustic speech biomarkers
- Beta-band MEG biomarkers
- Cross-cohort representation learning
- Residual latent encoder
- Gradient Reversal Layer (GRL)
- Supervised Contrastive Learning (SupCon)
- RF-SHAP feature selection

---

## Repository Contents

- Codes
- Figures

---

## Datasets

This work uses publicly available datasets:

- Parkinson's Dataset (Max Little, 2008)
- Parkinson's Speech Dataset with Multiple Sound Types (2013)
- Parkinson's Dataset with Replicated Acoustic Features (2019)
- Parkinson's Telemonitoring Dataset (2009)
- NatMEG-PD Dataset v1.1


---

## Requirements

- Python 3.10+
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- SHAP
- Matplotlib
- SciPy

---

## Citation

If you use this repository in your research, please cite the following preprint:

> **MIRA-Net: A Cross-Cohort Representation Learning Framework for Parkinson's Disease Detection Using Acoustic Speech and Beta-Band MEG Biomarkers.**
>
> **DOI:** https://doi.org/10.64898/2026.07.03.26357258


---

## License

This repository is intended for academic and research purposes.
