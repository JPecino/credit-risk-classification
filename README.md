# credit-risk-classification

Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
Split the data into training and testing datasets by using train_test_split.
Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).
Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
Evaluate the model’s performance by doing the following: a. Generate a confusion matrix. b. Print the classification report.
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
Credit Risk Analysis Report
Overview of analysis: The goal of this analysis is to create a model that predicts the risk on whether to lend loans to reliable/unreliable borrowers.

Credit Risk Analysis Report
Overview of analysis: The goal of this analysis is to create a model that predicts the risk on whether to lend loans to reliable/unreliable borrowers.

Results: image
Balanced Accuracy Score: 0.995
Precision Score: 1.00
Recall Score: 1.00
F1-Score: 1.00
Summary: The model predicts the 0 (healthy loan) with 99% accuracy and the 1 (high-risk loan) with 91% accuracy.  The model is better at predicting the 0 (healthy loan) than the 1 (high-risk loan).  The model is the same as the original model.