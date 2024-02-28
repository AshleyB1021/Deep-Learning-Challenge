# Credit Risk Analysis

## Overview

In this assignment, you will perform credit risk analysis using logistic regression. The goal is to predict the risk of default for loans based on certain features. You will split the data into training and testing sets, create a logistic regression model, and evaluate its performance. Finally, you will write a credit risk analysis report summarizing your findings.

## Split the Data into Training and Testing Sets

* Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
* Create the labels set (y) from the “loan_status” column and create the features (X) DataFrame from the remaining columns.
* Split the data into training and testing datasets using train_test_split.

## Create a Logistic Regression Model

* Fit a logistic regression model using the training data (X_train and y_train).
* Save the predictions on the testing data labels using the testing feature data (X_test) and the fitted model.
* Evaluate the model’s performance by generating a confusion matrix and a classification report.


## Write a Credit Risk Analysis Report

* Overview: Explain the purpose of the analysis.
* Results: Describe the accuracy score, precision score, and recall score of the machine learning model using a bulleted list.
* Summary: Summarize the results from the machine learning model and provide justification for recommending or not recommending the model for use by the company.




