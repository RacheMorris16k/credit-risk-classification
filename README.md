# credit-risk-classification
# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to build a machine learning model that can predict whether a loan applicant poses a high credit risk (i.e., likely to default). This prediction is essential for financial institutions that want to minimize losses by identifying risky loan candidates early in the decision-making process.

The dataset contained financial data about individual loan applicants, including:

*Loan size

*Interest rate

*Borrower income

*Debt-to-income ratio

Our goal was to predict the loan_status, where:

*0 represents a healthy loan

*1 represents a high-risk loan

The target variable loan_status was imbalanced, with far more 0s than 1s. This class imbalance made it particularly important to pay attention to recall and precision for the minority class.

Machine Learning Process
We followed these main steps in the machine learning workflow:

*Data Preprocessing: Loaded the CSV, separated the feature set (X) and target (y).

*Train-Test Split: Used train_test_split() to split the data into training and testing sets.

*Model Training: Applied a LogisticRegression model on the training data.

*Evaluation: Assessed the model using confusion_matrix and classification_report.

## Results

Machine Learning Model 1: Logistic Regression
Accuracy: 0.98

Precision:

*Class 0 (healthy): 1.00

*Class 1 (high-risk): 0.84

Recall:

*Class 0 (healthy): 0.99

*Class 1 (high-risk): 0.94

## Summary

The logistic regression model performed well overall, particularly for predicting healthy loans (class 0). It showed strong accuracy and recall scores for high-risk loans (class 1) as well, which is critical for avoiding bad credit decisions.

*Recommendation: We recommend using this model because it achieves a good balance between detecting high-risk loans and minimizing false positives.
-Rache Morris
-15/05/2025
