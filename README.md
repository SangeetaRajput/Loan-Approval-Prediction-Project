# Loan-Approval-Prediction-Project

# project Overview

This project builds a Loan Approval Prediction system using Python and Machine Learning. The dataset contains various applicant attributes such as income, employment type, credit score, and asset values, and the goal is to predict whether a loan application will be Approved or Rejected.

Dataset Link: https://drive.google.com/file/d/1n1I3hEcgN-YKycu174QRVXcqW2xmQk99/view

# Project Workflow

1. Data Loading & Exploration

• Load data using pandas.

• Check for missing values and basic data stats.

• Handle missing values by filling with median (numeric) and mode (categorical).

2. Encoding Categorical Variables

• Convert education, self_employed, and loan_status into numeric using LabelEncoder.

3. Feature Engineering

• Drop irrelevant columns (loan_id).

• Set loan_status as target variable y, and remaining columns as features X.

4. Data Preprocessing

• Train-test split (80-20).

• Standardize numerical features using StandardScaler.

5. Model Training

• Use Random Forest Classifier for prediction.

• Train on X_train, y_train.

6. Model Evaluation

• Predict on X_test.

• Evaluate using:

• Accuracy Score

• Classification Report

• Confusion Matrix

# Evaluation Metrics

• Accuracy: Measures how many predictions are correct.

• Confusion Matrix: Shows TP, FP, FN, TN.

• Classification Report: Provides precision, recall, f1-score.

# Key Python Libraries Used

• pandas:Data loading and preprocessing

• numpy:Numerical operations

• matplotlib & seaborn:Visualization

• sklearn:Model training, encoding, scaling, and evaluation
