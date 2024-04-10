# credit-risk-classification
## Overview of the Analysis

* In this activity, lending data from loan applications was reviewed in order to find a way to predict whether an application's credit risk would be classified as a "Healthy Loan", or a "High Risk Loan".
* The financial dataset provided consisted of historical loan applications classified as either "Healthy Loan" or "High Risk Loan". Each application included essential details that influenced the loan status such as loan size, interest rate, borrower income, debt-to-income ratio, derogatory marks (reflecting the health of the applicant's credit history), and total debt.
* A logistic regression model was selected to predict the loan application status. Logistic regression models are specifically designed for binary classification tasks, making them ideal for distinguishing between "Healthy Loan" and "High Risk Loan" categories based on the provided data. Using the essential details that influence loan status included in each application, the logistic regression model was executed to predict the loan status.

## Results

* Logistic Regression Model Analysis Results:
    * Accuracy Score of 99: indicates model correctly identifies the credit risk for 99% of the instances.
    * Precision of 100% for "Healthy Loans":  indicates that 100% of the applications identifed as "Healthy Loans" by the model were actually "Healthy Loans".
    * Precision of 85% for "High Risk Loans": indicates that 85% of applications identified as "High Risk Loan" by the model were actually "High Risk".
    * Recall for "Healthy Loans" of 99%:  indicates 99% of the actual healthy loans were correctly predicted.
    * Recall for "High Risk Loans" of 91%: indicates 91% of actual high risk loans were correctly predicted. 

## Summary

The model has an overall accuracy rate of 99%, indicating that it correctly identifies the credit risk for 99% of the data. In terms of precision, the model correctly predicts "Healthy Loan" for 100% of the actual "Healthy Loan" applications. However, the model is less precise in predicting "High Risk Loan", as only 85% of the loans it deems "High Risk" are actually "High Risk". A financial institution could implement this model to identify "High Risk" loans but should consider implementing a second look at all "High Risk" loan applications to rectify instances where applications are denied incorrectly and should have been considered "Healthy Loan".





