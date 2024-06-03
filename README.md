# Module 20 Challenge - credit-risk-classification

## Overview of the Analysis
The data was analyzed using models created by machine learning algorithms. The source dataset consisted of lending historical data, which contained the necessary information to generate the risk-analysis data model to determine lending to borrowers.

The dataset included: loan amount, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt, and loan status. 

The purpose of the created data model is to predict if the loan is a "healthy loan" or "high-risk loan." 

The data model was two dimensional with a y variable containing the "loan_status" and a x variable containing the features. After the x and y variables were set, the value_counts function was used to check the balance.

Using the established variables the data was then fit into two datasets-training and testing. Based on the nature of the dataset a logical regression model was used for training and testing the model.

Resources used for the evaluation of the model were "confusion_matrix" and "classification_report."

## Results
* Machine Learning Model 1
Precision: (Healthy Loan(0)) - 1.00; (High-Risk Loan(1)) - 0.87 • Recall: (Healthy Loan(0)) - 1.00; (High-Risk Loan(1)) - 0.89 • F1-Score: (Healthy Loan(0)) - 1.00; (High-Risk Loan(1)) - 0.88


## Summary
The results show the logistic regression model has perfect precision, recall, and f1-score for "Healthy Loan (0)" predictions. Whereas, the model's precision accuracy for "High-Risk Loans (1)" was just 87%. This infers the model can more accurately predict "Healthy Loans" than "High-Risk Loans". In a real application the percentage of accuracy for "Healthy Loans" is within an acceptable range. However, additional data is required for "High-Risk Loans" to increase the prediction accuracy to an acceptable range.

The recommendation to ensure the highest level of accuracy of the risk analysis would be to oversample the minority class of "high-risk loans" and then a regression model. This would ensure unbiased and balanced results. 
