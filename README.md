# credit-risk-classification
## Overview of the Analysis

Purpose of the analysis - 
The purpose of the analysis is to identify the creditworthiness of borrowers based on loan risk. 
The dataset contains historical lending activity from peer to peer lending services company. The model needs to predict high risk loans and healthy loans. The input variables are all columns in the dataset except the loan_status column. The output variable is the loan_status column.
The input and output features are split into training and testing data using train_test_split.
This code uses Logistic Regression model to come up with the prediction. We use the training data to fit to the model and test data to predict.
The confusion matrix and classification report are printed.

## Results

* Logistic Regression Model:
    * With this model, the helathy loan had a precision score of 100%, recall score of 100% and f1 score of 100%. The high risk loan had a precision score of 87%, recall score of 89% and f1 score of 88%. There were about 18759 data for the healthy loan and about 625 data for high risk loan. 
	
## Summary

The scores we see from training this model, this model seems to do a fairly good job at predicting the healthy loan and high risk loan. This model seems to solve the problem we have. This model has an accuracy of 99% which says that it is able to predict both healthy loans and the high risk loan pretty accurately. It is important to predict both 0 and 1 accurately since inaccuracy in either one of them will cost the business pretty heavily.