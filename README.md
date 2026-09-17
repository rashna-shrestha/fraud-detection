# Fraud Detection

A machine learning project for analyzing and detecting fraudulent transactions using Python and scikit-learn.

## Project Overview

The goal of this project is to explore transaction data, identify patterns associated with fraudulent transactions, and build machine learning models for fraud classification.

The project covers the complete machine learning workflow:

- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Train-test splitting
- Feature selection
- Feature engineering
- Data preprocessing
- Handling class imbalance with SMOTE
- Model training
- Hyperparameter tuning
- Model evaluation

## Dataset

The dataset contains transaction-related information used to classify transactions as fraudulent or legitimate.

The target variable is the fraud indicator.

> Note: The dataset is included in this repository for reproducibility.

## Machine Learning Models

The following classification algorithms were explored:

- Logistic Regression
- Decision Tree
- Random Forest

## Techniques Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Imbalanced-learn
- SMOTE
- Mutual Information
- ANOVA / statistical feature analysis
- Cross-validation
- GridSearchCV
- ROC-AUC evaluation

## Project Structure

```text
fraud-detection/
│
├── fraud.ipynb
├── fraud_data.csv
├── requirements.txt
├── .gitignore
└── README.md
