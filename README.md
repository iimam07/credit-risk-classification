# credit-risk-classification


Various techniques were used to train and evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. 

Based of the models, a credit analysis report will be created to show a summary and analysis of the performance of the machine learning models used through this model.

# CREDIT ANALYSIS REPORT:

## 1. ANALYSIS: 
The purpose of this analysis was look at credit risk, which is associated with the possibility of losing a lender holds due to a risk of default on a debt that may arise from a borrower failing to make required payments. In this analysis, supervised machine learning was used to look at a dataset of historical lending actvity to see the type of risk for loans. 

The logistic regression model is used for predictive analysis, and describes the data and explain the relationship between two variables. 

## 2. RESULTS: 
The data shows that that healthy (low-risk) by far exceeds the unhealthy (high-risk) loans. 18668 were predicted correctly as health, low-risk loans, and 623 predicted correctly as high risk loans. 

- The logistic regression model with both datasets (normal and oversampled) showed the accuracy score as 99.5%
- For the given data set, the precision score for the low risk loans is 1.00, and for high risk it is 0.87. The precision score means how well the qualifier predicts the positive class. The closer a score is to 1, the better balance it has. Thus the score for low risk loans is well-balanced, and belongs where it needs to. For the oversampled data, the low risk loans remains 1.00, and high risk loans also remains 0.87.
-For the recall score, the closer to 1 is better, and means that it does not have false negatives. For low risk loans, the score was 1.00 for both, and for high risk loans, the it changes from 0.89 to 1.00 in the oversampled data.

## 3. SUMMARY:
The logistic regression model is a good model to use when working on this credit risk data. The accuracy score remains high, and close to 100% for both data sets, and the precision is high, especially for the low-risk. The recall score is also high, and rises for the over-sampled data, which is the main area where the data changes for the tests. Otherwise the tests to not change very much results wise. I would then recommend the logistic regression model to be used by the company.
