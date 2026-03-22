# Visa Approval Prediction

Predicting US work visa approval outcomes using supervised machine learning.

## Overview
Built classification models to predict whether a visa application will be **Certified or Denied** based on applicant education, experience, wage, and employer data.

## Dataset
- 25,480 visa applications
- 12 features including education, wage, experience, region
- Binary target: Certified (1) / Denied (0)

## Models Used
- Decision Tree
- Bagging
- Random Forest
- AdaBoost
- Gradient Boosting

## Key Result
**Bagging on Undersampled data** selected as final model with **Denied Recall of 0.73**

## Tech Stack
`Python` `Scikit-learn` `XGBoost` `Pandas` `Seaborn` `Matplotlib` `Imbalanced-learn`

## Project Report
[Download Report](U.S.-Visa-Approval-Prediction.docx)

## Notebook
[View Notebook](visa-approval-prediction.ipynb)
