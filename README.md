# credit-risk-classification

## Overview of the Analysis

The analysis aimed to assess the creditworthiness of potential customers using supervised learning models, specifically Logistic Regression. The target variable was Loan Status (Healthy or High Risk), with features including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory remarks, and total debt.

The Original Data comprised 75,036 healthy loans and 2,500 high-risk loans, leading to a class imbalance. The process involved splitting the data, training a Logistic Regression model, making predictions, and evaluating accuracy.

We implemented the described procedure on a Logistic Regression model, utilizing both the Original Data and Resampled data to rectify the imbalance in the counts of healthy and high-risk loans in our dataset.

## Results

* Machine Learning Model 1:Logistic Regression with Original Data
  Balanced Accuracy: 95.20%
    
  Accuracy: 99%
    
  Precision (Healthy Loans): 100%
    
  Recall (Healthy Loans): 99%
    
  Precision (High Risk Loans): 85%
    
  Recall (High Risk Loans): 91%



* Machine Learning Model 2:Logistic Regression with Resampled Data
 
  Balanced Accuracy: 99.37%
 
  Accuracy: 99%
 
  Precision (Healthy Loans): 100%
 
  Recall (Healthy Loans): 99%

  Precision (High Risk Loans): 84%

  Recall (High Risk Loans): 99%
  

## Summary

Both models demonstrate strong explanatory capabilities, with Model 2 exhibiting a marginal overall improvement, attributed to the dataset's imbalance between healthy and high-risk loans. Despite a modest 1% decrease in precision for high-risk loans in Model 2, there is a notable 8% increase in recall, minimizing the risk of false negatives and erroneous credit extension to high default risk individuals.

The assessment of model performance is context-dependent, emphasizing the importance of accurately predicting healthy versus high-risk loans. The 1% lower precision in high-risk loans for Model 2 may carry significance, particularly if minimizing false positives is a priority. False positives, entailing misclassification of creditworthy customers as high default risks, could impact sales. Ultimately, the model's efficacy is contingent on the specific problem it addresses.
