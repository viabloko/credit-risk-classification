# credit-risk-classification
Module 20
## Overview of the Analysis

* The goal of this exercise was to build a predictive model to identify the creditworthiness of borrowers.
* a dataset of historical lending activity from a peer-to-peer lending services company was used.
* The data included the financial background of borrowers (such as borrower income, number of accounts, etc) and the loan conditions (loan size, interest rate). Our model was focused on the loan status (0 - healthy, 1 - high-risk).
* First step is to separate dependent and independent variables. Then, we split the data into training and testing groups, and then applied a logistic regression model to the training dataset. Subsequently, the predicted model was used on the testing groups, and classification reports&confusion matrix were generated
* In this exercise, I used one method only, called `LogisticRegression`.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.
* Machine Learning Model 1:
  * The accuracy score of the model is 95%, which is a very good result. The precision, recall and f1-score are outstanding (1.00) for predicting healthy loans. However, lower precision (0.84) was revealed in high-risk loan assessment, while the recall and f1-score are above 0.90.


* Machine Learning Model 2:
  * Per home assignment's instruction, those steps weren't mentioned to be done.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The model predicts perfectly the healthy loans, while less precise to inform high-risk loans. Note that the number of healthy loans outnumbered drastically the latter ones. This may affect the model to have lower precision to predict a high-risk loan application.
