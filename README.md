# Credit-risk-classification

<img width="502" alt="Screen Shot 2024-07-18 at 9 53 55 AM" src="https://github.com/user-attachments/assets/0049c925-8119-49fc-add8-f11ce079e472">

## Overview of the Analysis

In this analysis we have different loan requests and based on following informations provided to us in dataset we have to determine if it is healty loan (0) or high-risk loan (1). 

Information provided to us are: loan size, interest rate, borrower income, debt to income, number of accounts, derogatory_marks and total debt. Goal is to predict loan_status to be healty(0) or high-risk loan(1).

Stages of the machine learning process:
I.Splitting the data into training and testing datasets
II.Create a Logistic Regression Model with the Original Data
    1.Fit a logistic regression model by using the training data (`X_train` and `y_train`).
    2.Save the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model.
    3.Evaluate the model’s performance by doing the following: Generate a confusion matrix & print the classification             report.

## Results

<img width="565" alt="Screen Shot 2024-07-18 at 10 31 28 AM" src="https://github.com/user-attachments/assets/82e0dac3-7ba2-4bad-b920-a48664e0f580">

### Label 0 - Healthy loan

Precision 1.00 - indicating 100% correct in predicting healthy loan.

Recall 1.00 - means that the model is highly sensitive to identify healthy loans. 

f1-score 1.00 - implies a perfect model preformance. This means that model has achieved both perfect precision and pefrect recall. 

### Label 1 - High risk loan

Precision 0.87 - indicating 87% correct in predicting high-risk loan.

Recall 0.89 - means that the model is correctly identifing 89% of high risk loans but misses 11%.

f1-score 0.88 - indicates a well preforming model for predicting high risk loans with some potential areas for improvement. 

## Summary

The logistic regression model performs very well in predicting both healty loan and high-risk loan implying that it is reliable model for management to use. While in healthy loan f1-score is 1.00 showing perfect model performance, in high risk loan f1-score of 0.88 which shows well preforming model in identifying high risk loans with a good balance between precision and recall. Model is effective in identifying high risk loans, and it is useful tool for management in decision making. Still there are some potential areas for improving (there might be some loans incorrectly identifies ad high risk) in precision and recall. 




