# credit-risk-classification

# Module 12 Report Template

## Overview of the Analysis
Factors considered in the analysis included data on:

- the size of the loan
- its interest rate
- the borrower's income
- the debt to income ratio
- the number of accounts the borrower held
- derogatory marks against the borrower
- the total debt
- loan status

The dataset was split into training and testing sets. The training set was used to build an initial logistic regression model using the LogisticRegression module from scikit-learn. Logistic Regression Model was then applied to the testing dataset. The purpose of the model was to determine whether a loan to the borrower in the testing set would be low- or high-risk and results are summarized below.

## Results
Logistic Regression Model 1:

- Precision: 100% `0` (healthy loan) and 87%  `1` (high-risk loan)
- Accuracy: 94% 
- Recall: 100% `0` (healthy loan) and 95% `1` (high-risk loan)

## Summary

The recommendation would be to go with this model. The logisitic regression model predicts a healthy, low-risk loan with 100% precision. It predicts a high-risk loan with lower precision at 87%. The balanced accuracy of the model is 94%. The accuracy score is 99%, this model performs exceptionally well.
