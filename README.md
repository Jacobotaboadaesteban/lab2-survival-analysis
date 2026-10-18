# Lab II: Survival Analysis

Survival analysis of pediatric bone marrow transplant patients using the UCI Bone Marrow Transplant Children dataset.

## Contents

- Exploratory data analysis
- Missing-value treatment
- PCA dimensionality reduction
- K-means clustering
- Kaplan-Meier survival analysis
- Cox proportional hazards regression

## Main results

- 187 patients and 37 original variables.
- 3 clusters were identified using K-means.
- Kaplan-Meier curves did not show significant differences between clusters.
- Log-rank test: p = 0.89.
- Cluster-based Cox model concordance: 0.52.
- Stratified clinical Cox model concordance: 0.69.

## Repository structure

- `data/`: dataset
- `notebooks/`: analysis notebook
- `report/`: final report