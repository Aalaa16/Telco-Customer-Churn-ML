📌 Telco Customer Churn Prediction – Machine Learning Project
📄 Project Overview

This project aims to predict customer churn for a telecom company using advanced machine learning techniques.
The goal is to identify customers who are likely to leave the service and understand the key drivers behind churn.

The workflow includes:

Data cleaning & preprocessing

Exploratory data analysis

Feature engineering

Handling data imbalance using SMOTE

Model training & evaluation

Feature importance & SHAP explainability

Saving the best model using a full ML pipeline

🗂️ Dataset

The dataset contains customer demographic information, service subscriptions, billing behavior, and a churn label.

Rows: 7043

Features: 20+

Target: Churn (Yes/No)

🔧 Technologies Used

Python

Pandas, NumPy

Scikit-Learn

imbalanced-learn (SMOTE)

Matplotlib / Seaborn

SHAP

XGBoost

Pickle

🧹 Data Preprocessing

The following steps were applied:

Handling missing values

Converting TotalCharges to numeric

One-hot encoding for categorical variables

Scaling numerical features

Train-test split

Balancing the training set using SMOTE

📊 Modeling

Five ML models were tested:

Logistic Regression

Decision Tree

Random Forest

XGBoost

SVM

Logistic Regression delivered the best overall performance.

📌 Best Model Performance (Logistic Regression)
Metric	Value
Accuracy	0.78
Precision	0.58
Recall	0.62
F1 Score	0.60
ROC-AUC	0.83

🔍 Feature Importance (Key Insights)

Top predictors of churn include:

Low tenure

Payment method (Electronic check)

Not using value-added services (Tech Support, Online Security)

High monthly/total charges

Contract type (Month-to-month customers churn the most)

Visualizations included:

Barplot of logistic regression coefficients

SHAP summary plots

🧠 Model Explainability (SHAP)

SHAP was used to interpret model predictions and identify the most influential features.
This helps the business understand why customers churn.
