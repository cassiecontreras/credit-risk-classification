# Module 20 Report Template

## Overview of the Analysis

The purpose of Module 20's credit-risk-classification analysis was to train and evaluate a model based on loan risk. Using a dataset of historical lending activity from a peer-to-peer lending services company we can identify the creditworthiness of borrowers. Dependant variable (y value) in this analysis was the "loan status" indicating if a loan is healthy or at risk. Independent Variables (x values) were loan size, interest rate, borrower income, debt to income ratio, number of accounts and derogatory marks.

In this analysis, we split our data to traning and test sets. Secondly, we defined our dependent and independent variables. We then created logistic regression model and fit our original data to this model. Trained model is used to make predictions. Lastly, we evaluated the model's performance.


 

## Results

* Machine Learning Model 1: Logistic Regression Model with Original Data

  
 The balanced accuracy score of the model is: 0.9520479254722232
 

                                precision   recall  f1-score   support

                       0       1.00      0.99      1.00     18765
                       1       0.85      0.91      0.88       619

                accuracy                           0.99     19384
               macro avg       0.92      0.95      0.94     19384
            weighted avg       0.99      0.99      0.99     19384



* Machine Learning Model 2: Logistic Regression Model with Randomly Oversampled Data

  
  The balanced accuracy score of the model is: 0.9945026387334079
  
                             precision    recall  f1-score   support

                       0       0.99      0.99      0.99     75036
                       1       0.99      0.99      0.99     75036

                accuracy                           0.99    150072
               macro avg       0.99      0.99      0.99    150072
            weighted avg       0.99      0.99      0.99    150072
 
  

## Summary

Our Analysis show that collected data can be effectively used to train and test the Machine Learning Classification Model. Machine Learning Model 2: Logistic Regression Model with Randomly Oversampled Data resulted in a higher balanced accuracy and recall scores.  With higher recall value, model can predict risky loans more accurately.  

With incorrect predictions we have two issues:
False positives (where users are flagged as risky, but are actually healthy)
False negatives (where users are not flagged as risky but are actually risky)








