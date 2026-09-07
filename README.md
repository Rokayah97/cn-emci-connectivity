# CN vs EMCI Connectivity Classification

Code for "Connectivity-Based Classification of Cognitively Normal and Early
Mild Cognitive Impairment Subjects" (ICECER 2026).

## Overview
Resting-state fMRI connectivity classification of CN vs EMCI on a 432-subject
ADNI cohort, using AAL-116 tangent-space connectivity and a linear SVM, under
a leakage-free evaluation protocol.

## Pipeline
1. `notebooks/01_registration_step1.ipynb` — ANTs registration to MNI space.
2. `notebooks/02_classification_pipeline.ipynb` — feature extraction,
   leakage-free cross-validation, and all reported results.
   

## Data
Data are from ADNI and are **not** included. See `docs/data_access.md`.

## Requirements
See `requirements.txt`. Developed in Google Colab.

## Citation
See `CITATION.cff`.

## License
MIT — see `LICENSE`.
