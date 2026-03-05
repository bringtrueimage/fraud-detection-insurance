# Insurance Fraud Detection (ML Project)

Machine learning project for detecting fraudulent insurance claims using classification models.

## Overview
This project builds a binary classifier to identify potentially fraudulent insurance claims.  
The dataset contains 15,420 insurance claim records with 33 variables describing accident details, policy information, and claimant characteristics. :contentReference[oaicite:0]{index=0}

The goal is to support insurance companies in prioritizing suspicious cases for further investigation.

## Methods
- Data preprocessing and feature engineering
- Handling class imbalance using class weights
- Model comparison:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Model interpretation with SHAP values

## Final Model
The best performing model was **XGBoost**, optimized with a workload-based threshold to balance fraud detection and investigation capacity.

Key results:
- Recall: ~62.5%
- Accuracy: ~76%
- AUC: ~0.81

## Business Impact
Even with moderate precision, the model can generate significant financial savings by detecting fraudulent claims before payout.

## Dataset
Vehicle insurance claims dataset (Kaggle).

## Authors
Veronika Nozdrenkova
Daniel Petr Jašek
David Bárta  
