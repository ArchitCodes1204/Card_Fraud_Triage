# Card Fraud Triage via Gaussian Mixture Density Scoring and Autoencoder Anomaly Detection

**Team ID:** T047  
**Section:** A  
**Course Areas:** Applied Machine Learning (Phase 1) & Deep Learning (Phase 2)  
**Project Number:** Project 26  

---

## 1. Project Overview
This project investigates whether unsupervised anomaly-detection models trained exclusively on legitimate card transactions can rank suspicious transactions effectively in an operational triage setup. 

- **Phase 1 (AML):** Gaussian Mixture Model (GMM) with component selection via AIC/BIC and scoring via negative log-likelihood (NLL).
- **Phase 2 (DL):** Autoencoder anomaly detection using reconstruction error, ablation studies, and an optional hybrid ranking experiment.

---

## 2. Directory Structure

```text
aml project/
├── configs/             # Configuration files (hyperparameters, paths, split configs)
├── data/
│   ├── raw/             # Raw dataset (excluded from Git)
│   └── processed/       # Preprocessed and split data (excluded from Git)
├── notebooks/           # Milestone-specific Jupyter notebooks
├── reports/             # LaTeX / IEEE reports, notes, presentation decks
├── results/
│   ├── figures/         # Generated plots (PR curves, distributions, AIC/BIC curves)
│   └── metrics/         # Saved metrics and experiment logs
├── src/                 # Reusable Python modules
├── .gitignore           # Git ignore rules for data, checkpoints, and environment files
├── README.md            # Project documentation and reproduction guide
└── requirements.txt     # Python dependencies
```

---

## 3. Team Members & Roles (Provisional)
1. **Naveen Kumar:** Project coordination, research design, experimental protocol, and pipeline integration.
2. **Aditya Raj:** Dataset provenance, data quality checks, EDA, and preprocessing review.
3. **Shagun Vishnoi:** GMM statistical foundations, EM algorithm, and AIC/BIC model selection.
4. **Archit Mamodiya:** Autoencoder architecture design, regularisation, and training experiments.
5. **Ritik Ranjan:** Evaluation metrics (PR AUC, fixed-budget recall), threshold tuning, and reporting.

---

## 4. Setup Instructions
*(To be detailed in Milestone 1)*
