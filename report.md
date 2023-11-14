# Module 12 Report Template

## Overview of the Analysis

Purpose of the Analysis
The analysis aimed to develop machine learning models for predicting loan default probability based on historical lending data. The goal was to assess borrowers' creditworthiness by categorizing loans as either 'healthy' (0) or 'high-risk' (1) based on financial information and other relevant features.

Financial Information and Prediction Target
The dataset likely included attributes such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. The prediction target was the loan status, with 0 indicating a healthy loan and 1 representing a high-risk loan (potentially indicating default).

Basic Information about Predictive Variables
Understanding the distribution of loan statuses in the dataset (value_counts) would reveal the balance between healthy loans (0) and high-risk loans (1).

Stages of the Machine Learning Process
Data Preprocessing: Handling missing values, encoding categorical variables, and addressing class imbalance using resampling techniques if necessary.
Feature Engineering/Selection: Identifying significant features and preparing the dataset for modeling.
Model Selection and Training: Utilizing various classification algorithms (e.g., Logistic Regression, Random Forest, Gradient Boosting) to build predictive models.
Model Evaluation: Assessing model performance using metrics such as balanced accuracy, precision, recall, and F1-score.

Interpretation of Metrics:
Class 0 (Healthy Loans):
Precision (Class 0): 100%

The model correctly predicted all instances labeled as healthy loans (0). Precision indicates that every prediction made for class 0 was accurate.
Recall (Class 0): 100%

The model identified all actual healthy loans. Recall indicates that every actual instance of class 0 was captured by the model.
F1-score (Class 0): 100%

The harmonic mean of precision and recall for class 0 is perfect, indicating an ideal balance between precision and recall for healthy loans.
Support (Class 0): 15001

The number of instances belonging to class 0 (healthy loans).
Class 1 (High-Risk Loans):
Precision (Class 1): 86%

The model correctly predicted around 86% of instances labeled as high-risk loans (1). Precision indicates the accuracy of the predictions for class 1.
Recall (Class 1): 91%

The model identified around 91% of actual high-risk loans. Recall signifies the model's ability to capture actual instances of class 1.
F1-score (Class 1): 88%

The harmonic mean of precision and recall for class 1 is good, demonstrating a reasonable balance between precision and recall for high-risk loans.
Support (Class 1): 507

The number of instances belonging to class 1 (high-risk loans).
Overall Metrics:
Accuracy: 99%

The overall accuracy of the model in correctly predicting both healthy and high-risk loans.
Macro Avg (macro-average) F1-score: 94%

The unweighted average of the F1-scores for both classes, giving equal importance to each class.
Weighted Avg (weighted-average) F1-score: 99%

The weighted average of the F1-scores, considering the number of instances for each class.
Summary:
The Logistic Regression model shows outstanding performance in correctly identifying healthy loans (0) with perfect precision and recall.
For high-risk loans (1), the model demonstrates good performance with high precision and recall, albeit slightly lower than for healthy loans.
Overall, the model achieves high accuracy, demonstrating its effectiveness in classifying both healthy and high-risk loans.
The macro-average and weighted-average F1-scores suggest strong model performance across both classes.