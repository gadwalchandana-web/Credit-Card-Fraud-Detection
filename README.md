# Credit Card Fraud Detection

Machine Learning project to detect fraudulent credit card transactions.

## Project Overview

This project uses Machine Learning to classify credit card transactions as:

- Normal
- Fraudulent

The dataset contains 10,000 transactions with transaction details such as amount, transaction hour, merchant category, foreign transaction status, location mismatch, device trust score, transaction velocity, and cardholder age.

## Dataset

- Total transactions: 10,000
- Normal transactions: 9,849
- Fraudulent transactions: 151
- Fraud rate: 1.51%

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab
- GitHub

## Machine Learning Models

### Random Forest
- Accuracy: 99.15%
- Fraud Precision: 1.00
- Fraud Recall: 0.43
- Fraud F1 Score: 0.60

### Logistic Regression
- Accuracy: 96.00%
- Fraud Precision: 0.26
- Fraud Recall: 0.97
- Fraud F1 Score: 0.41

The two models show a trade-off between detecting more fraudulent transactions and reducing false alerts.

## Features

- Transaction Amount
- Transaction Hour
- Merchant Category
- Foreign Transaction
- Location Mismatch
- Device Trust Score
- Velocity in Last 24 Hours
- Cardholder Age

## Results

The Random Forest model achieved high overall accuracy and fraud precision, while Logistic Regression detected a larger proportion of fraudulent transactions.

## Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── Credit_Card_Fraud_Detection.ipynb
└── README.md
