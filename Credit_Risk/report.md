# Module 12 Report Template

## Overview of the Analysis

The purpose of  this analysis was to create and train a model that predicts the creditworthiness of borrowers based on a dataset of lending activity from a peer-to-peer lending company, then evaluate the accuracy of the model. The data used included variables such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable, loan_status, indicates whether a loan is healthy (0) or high-risk (1). The machine learning process included the following stages:
* Data preprocessing: Splitting the data into features (x) and labels (y), and further splitting into training and testing sets.
* Model creation: A Logistic Regression model was used to fit the training data and make predictions using the testing data.
* Model evaluation: The model was evaluated using a confusion matrix and printing a classification report

## Results

Logistic Regression Model:
* Accuracy: 99%
* Precision:
    * Healthy loans (0): 100%
    * High-risk loans (1): 84%
* Recall:
    * Healthy loans (0): 99%
    * High-risk loans (1): 94%
* F1-Score:
    * Healthy loans (0): 100%
    * High-risk loans (1): 89%

The confusion matrix showed:
* True Positives (TP): 583 
* True Negatives (TN): 18,655
* False Positives (FP): 110
* False Negatives (FN): 36

## Summary
The Logistic Regression model performed well, achieving a 99% accuracy rate in predicting loan status. Key observations include:
Healthy loans (0) were predicted with near-perfect precision and recall.
High-risk loans (1) had slightly lower precision (84%) but very high recall (94%), indicating the model effectively identifies most high-risk loans.
In this case, the Logistic Regression model can be recommended because it was high performing in its prediticons but could be a little risky considering it having lower precision in the classification of high-risk loans. 
