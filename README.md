# Binary Classification with a Bank Churn Dataset

This project aims to predict whether a customer will leave a bank (churn) based on various customer attributes. We built and trained a binary classification model, achieving an accuracy of 87%.

## Project Overview

Customer churn prediction helps banks identify customers at risk of leaving, allowing them to take preventive measures to retain valuable clients. This project uses supervised learning techniques to create a binary classification model that predicts customer churn.

## Dataset Description

The dataset used for this project contains various features that represent customer information, including demographics, account data, and behavioral metrics. Each row represents a customer.

### Input Features

The following columns are included in the dataset:

- **CustomerID**: Unique identifier for each customer.
- **Surname**: Customer’s surname.
- **CreditScore**: Customer's credit score, an important indicator of financial health.
- **Geography**: Customer's country of residence.
- **Gender**: Customer's gender.
- **Age**: Customer's age.
- **Tenure**: Number of years the customer has been with the bank.
- **Balance**: Customer's bank account balance.
- **NumOfProducts**: Number of bank products the customer is using.
- **HasCrCard**: Indicates whether the customer has a credit card (1 = Yes, 0 = No).
- **IsActiveMember**: Indicates whether the customer is an active bank member (1 = Yes, 0 = No).
- **EstimatedSalary**: Customer's estimated salary.

### Target Variable

- **Exited**: Binary variable indicating whether the customer exited (1 = Customer exited, 0 = Customer retained).

## Model Training

- **Model Type**: Binary Classification
- **Algorithm**: Neural Network
- **Training Process**: The dataset was split into training and testing sets (80-20 split). Preprocessing steps included encoding categorical variables (e.g., **Geography** and **Gender**), scaling numerical features, and handling missing values.

## Performance

The model achieved the following accuracy on the test set:

- **Accuracy**: 87%

Additional metrics such as precision, recall, and F1-score were also calculated to assess model performance further.
