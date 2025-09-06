# Telco Customer Churn Prediction

This repository contains a machine learning project that predicts customer churn for a telecommunications company. The project uses a dataset from IBM and employs a scikit-learn pipeline to preprocess the data, train and evaluate two different models (Logistic Regression and Random Forest), and save the best-performing model.

## Project Overview
The primary goal of this project is to build a classification model that can accurately predict whether a customer will churn (leave the service). The process involves:

- Data Loading and Exploration: Reading the dataset and performing an initial analysis to understand its structure and identify missing values.
- Data Preprocessing: Cleaning the data by handling missing values and converting categorical features into a numerical format suitable for machine learning algorithms.
- Model Training: Building and training a scikit-learn pipeline with two different classifiers:
- Logistic Regression: A simple but effective baseline model.
- Random Forest Classifier: A more complex ensemble model, often with higher predictive power.
- Model Evaluation: Comparing the performance of both models using a classification report, accuracy, and AUC (Area Under the Receiver Operating Characteristic Curve) score.
- Hyperparameter Tuning: Using `GridSearchCV` to find the optimal hyperparameters for the Random Forest model to improve its performance.
- Model Saving: Saving the final, best-performing model as a `.pkl` file for future use.

## Results
The project compares Logistic Regression and Random Forest classifiers. The final hyperparameter-tuned Random Forest model achieved a test AUC of approximately 0.83, demonstrating a strong ability to predict customer churn. The classification report and other metrics are available within the notebook.
