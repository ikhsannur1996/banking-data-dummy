# Banking Data Overview

This document provides a detailed description of the dummy banking data generated using Python. The dataset consists of 100,000 records, each representing a customer with various attributes related to their demographics, financial status, and banking behavior.

## 1. Dataset Summary

- **Sample Size**: 100,000 customers
- **File Format**: CSV (`banking_data.csv`)

## 2. Data Attributes

Below is a list of the attributes included in the dataset, along with a brief explanation of each:

### 2.1 Customer_ID
- **Type**: Integer
- **Description**: A unique identifier for each customer. Generated as a random integer between 0 and 100,000.

### 2.2 Age
- **Type**: Integer
- **Description**: The age of the customer, randomly generated between 18 and 60 years old.

### 2.3 Gender
- **Type**: Categorical
- **Categories**:
  - **Male** (50%)
  - **Female** (50%)
- **Description**: The gender of the customer.

### 2.4 Income
- **Type**: Integer
- **Description**: The monthly income of the customer, adjusted to be in intervals of 1,000,000 IDR. It follows a normal distribution with a mean of 15,000,000 IDR and a standard deviation of 5,000,000 IDR.

### 2.5 Credit_Score
- **Type**: Float
- **Description**: The credit score of the customer, normally distributed around a mean of 700 with a standard deviation of 100.

### 2.6 Average_Account_Balance
- **Type**: Integer
- **Description**: The average account balance of the customer, adjusted to be in intervals of 1,000,000 IDR. It follows a normal distribution with a mean of 50,000,000 IDR and a standard deviation of 20,000,000 IDR.

### 2.7 Loan_Amount
- **Type**: Integer
- **Description**: The loan amount requested by the customer, adjusted to be in intervals of 1,000,000 IDR. It follows a normal distribution with a mean of 20,000,000 IDR and a standard deviation of 5,000,000 IDR.

### 2.8 Loan_Term
- **Type**: Integer
- **Description**: The term of the loan in months, randomly generated between 12 and 60 months.

### 2.9 Occupation
- **Type**: Categorical
- **Categories**:
  - **Employee** (50%)
  - **Self-Employed** (30%)
  - **Retired** (20%)
- **Description**: The occupation status of the customer.

### 2.10 Average_Transactions_Per_Month
- **Type**: Integer
- **Description**: The average value of transactions per month, adjusted to be in intervals of 1,000,000 IDR. It follows a normal distribution with a mean of 5,000,000 IDR and a standard deviation of 1,000,000 IDR.

### 2.11 Bank_Location
- **Type**: Categorical
- **Categories**:
  - **Jakarta** (10%)
  - **Surabaya** (30%)
  - **Bandung** (20%)
  - **Semarang** (20%)
  - **Bogor** (20%)
- **Description**: The location of the bank branch associated with the customer.

### 2.12 Credit_History
- **Type**: Categorical
- **Categories**:
  - **Good** (20%)
  - **Fair** (50%)
  - **Poor** (30%)
- **Description**: The credit history status of the customer.

### 2.13 Education_Level
- **Type**: Categorical
- **Categories**:
  - **High School** (20%)
  - **Bachelor's Degree** (40%)
  - **Master's Degree** (30%)
  - **Ph.D.** (10%)
- **Description**: The highest level of education attained by the customer.

### 2.14 Employment_Status
- **Type**: Categorical
- **Categories**:
  - **Employed** (80%)
  - **Unemployed** (10%)
  - **Self-Employed** (10%)
- **Description**: The current employment status of the customer.

## 3. Data Generation Process

The dataset was generated using random sampling techniques to simulate realistic distributions for each attribute. The probabilities for categorical variables were predefined to reflect common scenarios in a banking environment.

## 4. Data Usage

This dataset can be used for various purposes such as:
- **Credit Risk Analysis**: To assess the risk profiles of different customer segments.
- **Marketing**: To identify target groups for financial products.
- **Data Modeling**: For machine learning and statistical analysis.

## 5. Data File

The dataset is saved in the CSV format and can be easily imported into various data analysis tools.

## 6. Conclusion

This synthetic banking dataset provides a comprehensive simulation of customer data that can be utilized for a variety of analytical purposes. It offers a balanced distribution of demographic, financial, and behavioral attributes, making it a valuable resource for data scientists and analysts.
