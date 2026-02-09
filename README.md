# Customer Churn Prediction

## Overview
This project builds a supervised machine learning model to predict customer churn using the Telco Customer Churn dataset.

## Dataset
- Source: Kaggle (Telco Customer Churn Dataset)
- Target Variable: Churn (Yes/No)

## Features Used
- tenure
- MonthlyCharges
- Contract
- InternetService
- PaymentMethod
- TotalCharges

## Model
- Logistic Regression
- Feature scaling using StandardScaler

## Evaluation Metrics
- Accuracy: ~79%
- Precision, Recall, F1-score
- Confusion Matrix

## Key Insights
- Customers on month-to-month contracts churn more
- Higher monthly charges increase churn risk
- Short-tenure customers are more likely to churn

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

