# Module 12 
Repository
---
    -README.md
    - Credit_Risk Folder
        - Data: lending_data.csv
        - Notebook for challenge: credit_risk_classification.ipynb

## Overview of the Analysis


* The purpose of this analysis is to determine if the model used is effective in determining healthy and high-risk loans.

* The data used is from historical lending activity from peer-to-peer lending services companies.  This data will help in building a model to identify credit worthiness of a potential borrower.

* That data needed for predictions:
---
    - loan_tatus (y variable- labels )
    - Features(X variable)
        - The rest of the numerical columns in the DataFrame, minus the status column.
        - The more important columns:
          - loan_size
          - interest_rate	
          - borrower_income
          - debt_to_income	
          - total_debt


* The stages of the machine learning process:
---
    - 1 Reading the data
    - 2 Separate the data into labels and features
    - 3 Using train_test_split to split the data into training and testing datasets.
    - 4 Using Logistic Regression model: 
        - Fitting the model with the training data
    - 5 Making a prediction using the testing data.
    - 6 Evaluation the model 



## Results

* Machine Learning Model:
---
    * Model: Logistic Regression Model
        - Accuracy 99%(99)
        - Precision:
            - Health loans 100%(1)
            - high-risk loans 87%(.87)

        - Recall:
            - Health loans 100%(1)
            - high-risk loans 95%(.95)
        

## Summary
For healthy loans(0), the precision is 1(100%), indicating the sample predictions were accurate. The recall is 1(100%), indicating that all the actual positive instances were accurate. 
For high-risk loans (1), the precision is .87(87%), indicating 87% of predictions were accurate. The recall is .95(95%), indicating that 95% of all actual positive instances were accurate. 
Overall the accuracy of the model is 99(99%).
The model is highly effective in detecting health loans and pretty good in detecting high-risk loans.  The model is well-balanced and should be a good source for identifying healthy loans and high-risk loans.
