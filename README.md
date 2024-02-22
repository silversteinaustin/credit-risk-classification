# Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this analysis was to utilize machine learning to predict credit risk in lending, i.e., identifying the credit risk of borrowers. We analyzed financial data and aimed to predict the likelihood of a loan defaulting. Using different training methods, I compared the performances to determine the better-performing model. The `loan_status` variable was critical, with a `0` indicating a healthy loan and a `1` representing a high-risk loan. Our analysis involved several stages, including:

- Reading in loan data and preparing it for modeling.
- Splitting the data into training and testing sets.
- Applying logistic regression to predict loan status.
- Evaluating model performance through metrics such as accuracy, precision, and recall.

## Results

### Healthy Loan (Label 0)
* Precision Score: 1.00
* Recall Score: 1.00
* F1-Score: 1.00

### High-Risk Loan (Label 1)
* Precision Score: 0.87
* Recall Score: 0.95
* F1-Score: 0.91

### Overall Model Performance
* Accuracy Score: 99%
* Balanced Accuracy Score: 97.21%


## Summary

The logistic regression model demonstrates excellent performance, particularly in identifying healthy loans with a perfect F1-score. While it also performs well in predicting high-risk loans, there is potential for further improvement, particularly in precision. Given its high overall accuracy and strong recall for high-risk loans, I would recommend this model for use by the company. The ability to accurately predict high-risk loans is crucial for a lending institution, and the high recall score indicates that the model is highly capable of identifying most of the high-risk loans, which is essential for minimizing credit risk.
