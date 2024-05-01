
# Loan Approval Prediction

This project aims to predict loan approval status based on various features using machine learning techniques. The dataset used contains information such as the number of dependents, education level, self-employment status, income, loan amount, loan term, credit score (CIBIL score), and asset values.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Dataset](#dataset)
3. [Data Preprocessing](#data-preprocessing)
4. [Modeling](#modeling)
5. [Evaluation](#evaluation)
6. [Feature Importance](#feature-importance)
7. [Dependencies](#dependencies)

## Getting Started

To run the code, ensure you have Python and the required libraries installed. You can install the dependencies using pip


## Dataset

The dataset used in this project is stored in a CSV file named `loan_approval_dataset.csv`. It contains the following columns:

- `loan_id`: Unique identifier for each loan application
- `no_of_dependents`: Number of dependents of the applicant
- `education`: Education level of the applicant (Graduate or Not Graduate)
- `self_employed`: Employment status of the applicant (Yes or No)
- `income_annum`: Annual income of the applicant
- `loan_amount`: Amount of loan requested
- `loan_term`: Term of the loan (in months)
- `cibil_score`: Credit score (CIBIL score) of the applicant
- `residential_assets_value`: Value of residential assets
- `commercial_assets_value`: Value of commercial assets
- `luxury_assets_value`: Value of luxury assets
- `bank_asset_value`: Value of assets in bank accounts
- `loan_status`: Approval status of the loan application (Approved or Rejected)

## Data Preprocessing

The data preprocessing steps include:

- Scaling numerical features using Min-Max scaling.
- Handling missing values.
- Encoding categorical features using one-hot encoding.

## Modeling

Two machine learning models are used for prediction:

1. Logistic Regression
2. Random Forest Classifier

## Evaluation

Model performance is evaluated using accuracy, classification report, and confusion matrix. 

## Feature Importance

Feature importance is determined using the Random Forest classifier to identify the top 3 features affecting loan status.

## Dependencies

- pandas
- numpy
- scikit-learn
- matplotlib

