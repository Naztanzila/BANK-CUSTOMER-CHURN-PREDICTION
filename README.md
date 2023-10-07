# BANK-CUSTOMER-CHURN-PREDICTION
# Bank Customer Churn Analysis

## Overview

This project analyzes customer churn in a bank using a dataset containing customer information. We aim to understand the factors that contribute to customer churn and create visualizations to present our findings.

## Dataset

The dataset used in this project is "Bank Churn Modelling.csv," which includes the following columns:
- CustomerId
- Surname
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- Num Of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Churn (Target Variable: 0 for not churned, 1 for churned)

## Code

### Data Preprocessing

- Imported the necessary libraries, including pandas, numpy, matplotlib, and seaborn.
- Read the dataset into a pandas DataFrame.
- Processed and cleaned the data, including handling missing values and converting categorical variables into numerical form.

### Data Visualization

- Created various visualizations to explore and understand the dataset:
  - Churn distribution (bar chart)
  - Gender distribution (bar chart)
  - Age distribution (box plot)
  - Distribution of other features (bar charts)

### Data Resampling

- Utilized the imbalanced-learn library to perform random under-sampling and random over-sampling to balance the dataset.

### Machine Learning Model (Random Forest)

- Trained a Random Forest Classifier on both the under-sampled and over-sampled datasets.
- Evaluated the model's performance using accuracy and classification reports.

## Results

- Foundings and insights from the data analysis.
- Model performance metrics for both under-sampled and over-sampled datasets.
