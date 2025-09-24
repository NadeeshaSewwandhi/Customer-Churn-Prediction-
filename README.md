# Customer-Churn-Prediction-

Project Overview

The Customer Churn Prediction System is a machine learning-based application designed to help businesses identify customers who are likely to leave (churn). By analyzing customer demographics, account information, and service usage patterns, the system predicts whether a customer will churn, enabling companies to take proactive measures to improve retention.
This project demonstrates how data preprocessing, feature engineering, machine learning model training, and deployment can be combined to solve real-world business problems.

Motivation

Customer churn is a critical issue for subscription-based businesses, telecom companies, and service providers. Predicting churn early allows organizations to implement targeted retention strategies, reduce revenue loss, and improve customer satisfaction. This project was developed to apply machine learning techniques to a practical business scenario and enhance predictive analytics skills.

Features

1. Predicts customer churn using Random Forest, Decision Tree, and XGBoost classifiers
2. Handles data preprocessing, including missing values, encoding categorical variables, and scaling numerical features
3. Balances imbalanced datasets using SMOTE
4. Provides model evaluation using cross-validation, accuracy, confusion matrix, and classification reports
5. Saves trained models and encoders for future predictions

Technologies Used

1. Programming Language: Python 3.11
2. Libraries: Pandas, NumPy, scikit-learn, imbalanced-learn (SMOTE), XGBoost, Matplotlib, Seaborn
3. Tools: Jupyter Notebook, Pickle (for saving models and encoders)

Workflow

1. Data Loading & Cleaning: Removed unnecessary columns, handled missing or erroneous values, and converted data types.
2. Exploratory Data Analysis (EDA): Visualized distributions, boxplots, and correlations to understand feature importance.
3. Feature Encoding: Used LabelEncoder for categorical variables and saved encoders for later use.
4. Handling Imbalance: Applied SMOTE to balance the target classes for better model training.
5. Model Training & Evaluation: Trained Decision Tree, Random Forest, and XGBoost classifiers with cross-validation and selected the best-performing model.
6. Model Saving: Saved the trained model and encoders using Pickle for future predictions.
7. Prediction: Prepared a sample input, applied saved encoders, and predicted churn probability and class.

Learning Outcomes

This project enhanced my understanding of data preprocessing, handling imbalanced datasets, and model evaluation. I gained experience in training and deploying machine learning models, encoding categorical data, and implementing an end-to-end ML pipeline. Additionally, it strengthened my analytical, problem-solving, and Python programming skills while providing practical insights into business decision-making through predictive analytics.
