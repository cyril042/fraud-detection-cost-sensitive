# Cost-Sensitive Fraud Detection System

This project develops a machine learning model to detect fraudulent financial transactions under extreme class imbalance using cost-sensitive modeling.

The model minimizes expected financial loss by optimizing classification thresholds instead of maximizing accuracy.

## Results

| Model | Test Cost | PR-AUC | ROC-AUC |
|------|-----------|--------|--------|
| Baseline | 49,000 | — | — |
| Logistic Regression | 6,890 | 0.742 | 0.968 |
| Random Forest | 6,205 | 0.876 | 0.976 |

Cost reduction: 87%

## Key Features
- Cost-sensitive learning
- Threshold optimization
- Random Forest modeling
- Operational decision policy simulation

## Dataset
Kaggle Credit Card Fraud Detection dataset.

## Notebook
See fraud_detection_cost_sensitive_modeling.ipynb
