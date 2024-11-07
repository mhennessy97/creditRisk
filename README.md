# creditRisk

#Overview
- The purpose of this notebook is to use a regression model to predict the risk of loans. Within this analysis, the following steps were taken.
    -Prepared and reviewed the data
    -Separated the  data into labels (loan_status) and features (X Variable)
    -Used SKLearn to split the data into training and testing datasets
    -Used LogisticRegression to fit and test the model
    -Used the model to make predictions with the test data

-value_counts:
    0: 75036
    1: 2500

#Results
-accuracy: 0.99
-precision class 0 (healthy loans): 1.00
-precision class 1 (high-risk loans): 0.85
-recall class 0 (healthy loans): 0.99
-recall class 1 (high-risk loans): 0.91

#Summary
Overall, the logistic regression model did a good job at predicting healthy loans with a precision of 1 meaning it was almost correct every time. It didn't do as well with predicting the high-risk loans because the precision was 85% meaning it was incorrect about 15% of the time. The recall was higher with high-risk loans so it did do a good job at indentifying incorrect predictions. 