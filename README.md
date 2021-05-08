# Factors that affect the Loan Outcome Status
## by Suki Chang


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000),
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings


The feature of interest in this dataset is the loan status. Some of the relationships observed are:-
- Borrower APR and Prosper score has a negative correlation.
- Borrower APR and bankcard credit is negative correlated.
- The loan original amount has negative relationship with borrower APR.
- The Prosper score is postively correlated with available bankcard credit. 
- Loan original amount is positively correlated with stated monthly income.

From our multivariate analysis, we found that:- 
- The Prosper score for the high risk group is between 2.0 to 7.0.
- The borrower APR for high risk group is generally higher, at around 0.25% to 0.4%.
- The available bankcard credit for high risk group is generally below 20,000 dollar.
- The high risk group usually borrows an amount of not more than 15,000 dollar.
- The high risk group generally earns a monthly income of not more than 10,000 dollar.


## Key Insights for Presentation

1. Loan Status - 67.9% of the loan is current loan and the high risk loan is about 5,000 or 9.3%.

2. Heatmap of Correlation Matrix - to illustrate the relationship between the numerical variables. 

3. Relationship between categorical and numerical variables:- 
- The Prosper score for the high risk group is between 2.0 to 7.0.
- The borrower APR for high risk group is generally higher, at around 0.25% to 0.4%.
- The available bankcard credit for high risk group is generally below 20,000 dollar.
- The high risk group usually borrows an amount of not more than 15,000 dollar.
- The high risk group generally earns a monthly income of not more than 10,000 dollar.
