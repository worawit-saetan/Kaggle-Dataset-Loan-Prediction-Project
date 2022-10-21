# Kaggle-Dataset-Loan-Prediction-Project

The dataset we used in this project came from the Kaggle website as the following URL :

https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset

This project is a classification problem, given information about the application we have to predict whether the they'll be to pay the loan or not.

The information about the application

  Loan_ID : Unique Loan ID

  Gender : Male/Female

  Married : Applicant married (Yes/No)

  Dependents : Number of dependents

  Education : Education of Applicant (Graduate/ Not Graduate)

  Self_Employed : Self employed (Yes/No)

  ApplicantIncome : Applicant income

  CoapplicantIncome : Co-applicant income

  LoanAmount : Loan amount in thousands

  Loan_Amount_Term : Term of loan in months

  Credit_History : Credit history meets guildlines

  Property_Area : Urban/ Semi Urban/ Rural

  Loan_Status : (Target) Loan approved (Yes/No)

The outline of this project :

- Load data and divide the dataset (prevent from seeing the test data)
- Explore the data
- Feature Engineering
  - Deal with missing values in categorical and numerical columns
  - Drop unnecessary column
  - Encode the categorical columns with Ordinal and One hot encoder
  - Encode the target column using Label encoder
  - Drop some original categorical columns
- Develop models
  - GaussianNB
  - XGBoost using Grid Search CV
  - Random Forest using Randomized Search
- Select and save the model



