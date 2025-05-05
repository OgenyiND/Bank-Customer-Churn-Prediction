🏦 Bank Customer Churn Prediction
This project aims to predict customer churn in a bank using machine learning classification algorithms. The goal is to identify customers who are likely to leave the bank, helping the business take proactive retention actions.

📌 Project Overview
Dataset: Customer data from a bank, including demographics, account information, and transactional behavior.

Objective: Predict whether a customer will churn (exit the bank) based on historical data.

🔧 Key Steps
Data Preprocessing

Handled missing and duplicate values

Encoded categorical variables (e.g., Gender, Geography)

Feature scaling using StandardScaler

Feature selection based on importance and domain relevance

Exploratory Data Analysis

Visualized churn distribution across demographics

Identified key trends using seaborn and matplotlib

Modeling

Trained and evaluated multiple classification models:

Logistic Regression

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Random Forest

Gradient Boosting Classifier

Used train_test_split for validation and evaluated models using:

Accuracy Score

Confusion Matrix

Classification Report

Results

Compared model performance across metrics

Best Model: Gradient Boosting Classifier – highest overall accuracy and balance between precision and recall.

📈 Tools & Technologies
Python, NumPy, Pandas

Scikit-learn, Seaborn, Matplotlib

📊 Outcome
This project showcases the use of multiple ML models for binary classification and highlights the importance of feature engineering and model evaluation in improving predictive performance.
