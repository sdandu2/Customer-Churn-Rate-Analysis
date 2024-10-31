# Customer Churn Rate Analysis

This project uses a Telco customer churn dataset to analyze and predict customer attrition. By leveraging PySpark, feature engineering, and machine learning techniques, we develop a predictive model for customer churn, aiming to provide insights into customer retention strategies.

## Project Overview
1. **Data Loading**: The dataset is downloaded from Kaggle using the Kaggle API.
2. **Data Processing**: Spark is used to ingest and preprocess the data, including handling categorical variables and feature scaling.
3. **Feature Engineering**: New features are created to enhance prediction accuracy.
4. **Modeling**: A logistic regression model is trained with cross-validation and hyperparameter tuning using Spark MLlib.
5. **Evaluation**: The model's performance is evaluated using AUC.

## Requirements
Install necessary libraries with:
```bash
pip install -r requirements.txt
