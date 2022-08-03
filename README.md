# Project solutions for Data Challenge

## Loan charge-off prediction

Objective: The goal of the project was to predict the probability of a loan charge-off based on the given features
The dataset consisted of over 148 variables related to the borrower along with the target variable that indicated if the loan was "fully paid" or "charged off". After dropping sparse and unknown features I was left with 16 independent variables that was used to predict the loan status. A logistic and random forest classifiers were built and had an average ROC_AUC value of 0.95 indicating a good model fit. The most important features that affected the predictions were the fico scores, home ownership, credit history and credit utilization percentage and the debt to income ratio. The solution codebook and dataset related to this data challenge can be found in the PatientFi folder of this repo. 
