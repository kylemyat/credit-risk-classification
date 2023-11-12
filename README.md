# credit-risk-classification
The machine learning technique of Logistic Regression Modeling is use to analyze a dataset of lending activity and create a model that identifies the creditworthiness of borrowers.

## Overview of the Analysis
The created Model analyzes the following factors:
* Loan Size
* Interest Rate
* Borrower Income
* Debt to Income Ratio
* Number of Accounts
* Deragatory Marks
* Total Debt
* Loan Status

## Results
* Low Risk Loans
    * Precision: 100%
    * Recall: 100%
    * F1-Score: 100%

* High Risk Loans
    * Precision: 87%
    * Recall: 89%
    * F1-Score: 88%

* Overall Balanced Accuracy: 94%

## Summary
The Model predicts low risk loans with 100% accuracy, but only 88% accuracy with high risk loans. Due to the possibility of predicting false positives, I would reccomend this model to be used to support a decision in offering a loan, but not as a deciding factor of whether a loan should be offered.