# credit-risk-classification

## Overview of the Analysis

The purpose of this analysis was to develop a predictive model that can effectively identify the creditworthiness of borrowers based on their financial information. The data used was historical lending activity from a peer-to-peer lending service company and the model used the LogisticRegression algorithm. More specifically, the dataset included the following independent variables or features: loan size, interest rate, borrower income, debt-to-income ratio, number of borrower accounts, derogatory marks against the borrower, and total borrower debt. The dependent variable is the status of the loan, of which the dataset contained 75,036 healthy loans and 2,500 high-risk loans. The information gained from this analysis is necessary for the lending company to make informed decisions regarding loan approvals and to minimize risk.

## Results

After training the model, it's performance was evaluated using accuracy, precision, recall, and F1-score metrics:

* Accuracy: 99%

* High-Risk Loans (1):
  * Precision: 85%
  * Recall: 91%
  * F1-Score: 88%

* Healthy Loans (0):
  * Precision: 100%
  * Recall: 99%
  * F1-Score: 100%

## Summary

Overall, the LogisticRegression model performed well with an accuracy of 99%, indicating that it correctly classified the majority of loans. It does well in predicting healthy loans, as shown by high precision, recall, and F1-score and relatively well in predicting high-risk loans, though with slightly lower precision, recall, and F1-score. Given the high performance of the logistic regression model, I would recommend using it for credit risk assessment. However, if the objective is avoid risky loans, then it is important to note that this model did not predict those types of loans as well as healthy ones. It may be in the bank's best interest to investigate other models that may produce more accurate high-risk loan predictions even if it means sacrificing some of the accuracy of the LogisticRegression model.
