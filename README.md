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

Both models demonstrated strong performance, with Model 2 slightly outperforming due to improved recall for high-risk loans, reducing the risk of false negatives. The evaluation depends on the specific problem, where the trade-off between false positives and false negatives is critical in the context of extending credit. Model 2, with its balanced accuracy and recall improvements, is recommended for mitigating the risk of extending credit to high-risk customers inadvertently.
