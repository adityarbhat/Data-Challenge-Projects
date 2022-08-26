# Project solutions for Data Challenge

## Loan charge-off prediction

Objective: The goal of the project was to predict the probability of a loan charge-off based on the given features
The dataset consisted of over 148 variables related to the borrower along with the target variable that indicated if the loan was "fully paid" or "charged off". After dropping sparse and unknown features I was left with 16 independent variables that was used to predict the loan status. A logistic and random forest classifiers were built and had an average ROC_AUC value of 0.95 indicating a good model fit. The most important features that affected the predictions were the fico scores, home ownership, credit history and credit utilization percentage and the debt to income ratio. The solution codebook and dataset related to this data challenge can be found in the PatientFi folder of this repo. 

##### Data Science techniques used : data manipulation, feature selection, exploratory analysis, machine learning model building and prediction.


## Denver Hotel Performance

Objective: The goal of the project was to merge hotel datasets from multiple sources to analyze the performance of hotels in the Denver, CO region to help a client with their plans for opening a hotel in the region. The first dataset contained information on the hotel in terms of its location, price and type of hotel and whether it belonged to a chain or run by an independent management. The second dataset consisted of hotel performance related information such as scores for food, room and service etc. With no unique identifying id columns in the two dataset, fuzzy matching was used to match the hotels by their name across the dataset. After filtering the dataset based on the best_matched_score and duplicate rows, the final dataset was used for exploratory analysis to understand the types of hotels and their pricing. Finally, I built a random forest regressor to identify the the important features affecting the overall score that a hotel gets. The recommendations and insights can ve found under the Mogul folder of this repo. 

##### Data Science techniques used : recordlinkage, fuzzymatching, data cleaning, exploratory analysis, machine learning model building and feature importances

