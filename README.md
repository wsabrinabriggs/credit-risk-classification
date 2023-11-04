# credit-risk-classification

CREDIT RISK ANALYSIS REPORT
## Overview of the Analysis
Various techniques were used to train and evaluate a model based on loan risk. Provided with a dataset of historical lending activity from a peer-to-peer lending services company, a model was built that can identify the creditworthiness of borrowers. The dataset was split into training and testing sets. The training set was used to build an logistic regression model with the original data (Model 1). This model determined the risk (high or low) of a loan to the borrower in the testing set.,The original dataset was resampled with the RandomOverSampler module from imbalanced-learn to make a new logistic regression model (Model 2). Model 2 helped to determine the rist (high or low) of a a loan to the borrower in the testing set.

## Results
For both models, the average of precision scores between low-risk and high-risk were about 93.5% 
Machine Learning Model 1:
  * Precision Scores:The model was 100% precise for low-risk loans and 87% precise in predicting high-risk loans
  * Accuracy Score: 94%
  * Recall Score: The model had 100% recall in predicting low-risk loans and 89% recall in predicting high-risk loans

Machine Learning Model 2:
  * Precision Scores: The model was 100% precise for low-risk loans and 87% precise in predicting high-risk loans
  * Accuracy Score: 100%
  * Recall Score: 100%

## Summary

Logistic Regression Model 2 is better at avoiding missed high-risk loans, but it does produce more errors by calling low-risk loans as high-risk compared to Model 1. However, when determining risky loans, both models do not hit the 90% precision mark. Still, Model 2 does a better job overall, making fewer mistakes in the test data and having high accuracy and recall/ Consequently, Model 2 is a better model to use.

Resources Used (in addition to teacher-provided notes and AskBCS):
1. Code Sources
   https://github.com/hfattor/credit-risk-classification/blob/main/Credit_Risk/credit_risk_classification.ipynb
   
