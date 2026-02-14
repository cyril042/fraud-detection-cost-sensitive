# Cost-Sensitive Fraud Detection System

## Overview
This project develops a machine learning system for detecting fraudulent financial transactions under extreme class imbalance using cost-sensitive modeling.

Instead of optimizing accuracy, the model minimizes expected financial loss by assigning different costs to false negatives and false positives.

The final Random Forest model reduced expected fraud-related cost by 87% compared to baseline.

## Dataset
Kaggle Credit Card Fraud Detection Dataset  
284,807 transactions  
Fraud rate ≈ 0.17%

## Modeling Approach
- Stratified train / validation / test split
- Logistic Regression baseline
- Random Forest model
- Cost-sensitive threshold optimization
- Operational decision policy simulation

## Results

| Model | Test Cost | PR-AUC | ROC-AUC |
|------|-----------|--------|--------|
| Baseline | 49,000 | — | — |
| Logistic Regression | 6,890 | 0.742 | 0.968 |
| Random Forest | 6,205 | 0.876 | 0.976 |

Cost reduction: 87%

## Operational Policy
Approve / Review / Block decision framework implemented.

Test results:
- False negatives: 5
- False positives: 41
- Reviews: 2,624

## Tools
Python, scikit-learn, Pandas, NumPy, Matplotlib


## Author
Cyril Udeani
