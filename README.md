# Credit_risk_classification
## Overview of the Analysis
The analysis aimed to create a machine learning model for credit risk assessment based on financial information. The data contained information regarding loan applications, including attributes such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status (0 for healthy loans and 1 for high-risk loans).
The variable of prediction is Loan status. Value counts of the given data showed 18,759 healthy loans and 625 high-risk loans.
Stages of the machine learning process: The analysis involved data preprocessing, splitting the data into training and testing sets, and building a logistic regression model using LogisticRegression from scikit-learn.

## Technology
* Machine learning logistic regression model
* scikit-learn
* Jupiter notebook
  
## Results
Logistic Regression Model result for healthy loans:
- Precision:    1.00 
- Recall:       1.00  
- f1-score:     1.00 

Logistic Regression Model result for high-risk loans:
- Precision:    0.87
- Recall:       0.89
- f1-score:     0.88
- 
Accuracy:     0.99 

## Summary
The logistic regression model performed exceptionally well in predicting healthy loans, achieving perfect precision and recall scores. The model exhibited high precision and recall for high-risk loans, albeit slightly lower than healthy loans.

The logistic regression model seems to be the best-performing model based on the provided information. It displays high accuracy in identifying healthy loans and reasonably good performance in predicting high-risk loans. The choice of the model might depend on the specific goals: If prioritizing the identification of high-risk loans is critical, further optimization or exploration of alternative models could be considered. Nonetheless, the logistic regression model is suitable for credit risk assessment, given its strong performance in distinguishing between healthy and high-risk loans.


