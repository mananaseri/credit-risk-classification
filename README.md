# credit-risk-classification

In this project , we are using machine learning models to predict credit risk for loans. 
The dataset contains columns such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. In derogatory marks that contains 1 or 0 . 1 represent High Risk and 0 represent Healthy and no risk . 
we are building a model to predict the accuracy and different attributes of our data .


steps

1) Getting data from cvs and using panda to make it to data frame. 
2) Creating the labels set (`y`)  from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns.
3) Splitting the data into training and testing datasets by using `train_test_split`.
4) Creating a Logistic Regression Model with the Original Data
5) Fitting a logistic regression model by using the training data (`X_train` and `y_train`)
6) Saving the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model
7) Evaluating the model’s performance by Generating a confusion matrix and printing the classification report


Logistic Regression Model:
Accuracy Score: 0.99

Precision Score for Healthy Loan - 0 is 1.00
Precision Score for High-Risk Loan -1 is 0.85

Recall Score for Healthy Loan : 0.99
Recall Score for High-Risk Loan : 0.91

support score shows 18765 for Healthy loan and only 619 High-Risk Loan which shows more people could afford loans which is great 
support is the number of occurrences of each particular class in the true responses 
The logistic regression model illustrates to be one of the best performing model for this task. As Accuracy Score is 0.99 and Precision Scores are 85 % and 100 % .
Recall score is a  metric that measures how often a machine learning model correctly identifies positive instances (true positives) from all the actual positive samples in the dataset . And as we see the Prediction for recall , both Healthy Loan and High-Risk Loan have high percentages which demonstrates 99 % of true positives for Healthy Loans and 91 % of true positives for High-Risk Loan. 
with this result , we observed that Logistic Regression Model was the best model for credit-risk classification and minimising risk default. 



