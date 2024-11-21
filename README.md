Report

1- An overview of the analysis 

The purpose of this analysis was to develop a machine learning model to predict loan risk status, splitting that in two categories "Heathy Loan", and "High-Risk Loan". The dataset has financial information including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, total debt, derogatory marks, and a binary target variable for loan status. 
0 represents a healthy loan and 1 indicates a high-risk loan. 

We first started by cleaning and normalizing the data, the data was split into features (X) and target (y). We applied a logistic regression model due to its simple and effective approach in binary classification problems. We then used evaluation metrics using accuracy, precision, recall anf F1-score metrics 

2- Results 

Healthy Loans (Label 0):
Precision: 1.00
Recall: 0.99
F1-Score: 1.00
Support: 18,765 loans

High-Risk Loans (Label 1):
Precision: 0.84
Recall: 0.94
F1-Score: 0.89
Support: 619 loans

Overall Metrics:

Accuracy: 99%

This shows us that the model is highly effective in predicting Healthy Loans with perfect precision and near-perfect recall.

3- Summary 

The logistic regression model performed exceptionally well with an accurary of 99%. We found almost perfect performance for prediciting "Healthy Loans" and robust results for "High-Risk Loans"

The model is good for this application because of its high precision and recall for both labels. However, there’s some room to improve its precision for "High-Risk Loans" (currently 0.84) to make it even better at avoiding false positives.

With regular monitoring—especially to ensure fairness for the smaller "High-Risk Loan" group—this model is ready to be used.

