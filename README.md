# credit-risk-classification
Module 20 Challenge 

Credit Risk Analysis Report

Overview
The purpose of this analysis is to use a logistic regression model to evaluate the creditworthiness of borrowers based on previous lending data. By helping predict loan risk, the model can assist companies in making informed lending decisions, minimizing financial risk, and improving profitability overall. 
The dataset includes financial information such as the borrower’s: loan size, interest rate, income, debt to income ratio and total debt. However, the target variable in this analysis is loan status which indicates whether a loan is healthy (labeled 0) or high-risk (labeled 1). The distribution of loan status in the dataset is imbalanced as most loans are healthy. 
The analysis required splitting the dataset into separate training and testing datasets using “train_test_split,” fitting a logistic regression model from sklearn, and evaluating its performance using key metrics such as: accuracy, precision, recall, F1-score, and confusion matrix. These metrics provide insight into the model’s ability to accurately classify healthy loans and high-risk loans. 

Results
- Accuracy score: 99% 
* The model accurately classified 99% of loans in the test dataset. 
- Precision:
* Label 0 (Healthy Loan): 1.00
* Label 1 (High-Risk Loan): 0.84
- Recall:
* Label 0 (Healthy Loan): 0.99
* Label 1 (High-Risk Loan): 0.94
- F1-Score:
* Label 0 (Healthy Loan): 1.00
* Label 1 (High-Risk Loan): 0.89
- Confusion Matrix:
* Predicted Healthy, Actual Healthy (True Negatives): 18,655
* Predicted Healthy, Actual High-Risk (False Negatives): 36
* Predicted High-Risk, Actual Healthy (False Positives): 110
* Predicted High-Risk, Actual High Risk (True Positives): 583

Summary
The logistic regression model demonstrates strong performance in predicting healthy loans achieving nearly perfect scores in precision, recall, and F1-score. It also performs well in predicting high-risk loans, with 84% accuracy, a recall of 94%, and an F-1 score of 89%. However, the slightly lower result for high-risk loans indicates the model is more effective in predicting healthy loans over high-risk loans. 

Recommendations
Given the overall accuracy and ability to identify loans effectively, the logistic regression model is well-suited for this lending company to use as a tool to identify borrowers’ creditworthiness. However, if precision of high-risk loans is necessary, the model may require adjustments to help optimize the results and reduce false positives. Overall, the model offers a strong foundation for informed decision making, improving profitability, and minimizing financial risk associated with lending. 
