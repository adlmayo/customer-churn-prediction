# Customer churn prediction

## Overview
This project predicts whether a customer is likely to leave a telecom service using Machine Learning. It includes data preprocessing, exploratory data analysis (EDA), feature encoding, handling class imbalance with SMOTE, model training, hyperparameter tuning, and model evaluation.

## Dataset
The dataset contains customer demographic information, account details, and service usage data.

## Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Label Encoding for categorical variables
- Feature scaling using StandardScaler
- Handling class imbalance using SMOTE
- Training and comparing multiple ML models
- Hyperparameter tuning
- Model evaluation and prediction
- Saving the best model and scaler using Pickle

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Pickle

## Project Workflow
1. Load and explore the dataset.
2. Clean and preprocess data.
3. Perform EDA and visualize distributions.
4. Encode categorical variables.
5. Scale numerical features.
6. Handle class imbalance using SMOTE.
7. Split data into training and testing sets.
8. Train and tune machine learning models.
9. Evaluate model performance.
10. Save the best model for future use.

## Files
- `Customer churn prediction.ipynb` — Complete notebook.
- `best_model.pkl` — Trained model.
- `scaler.pkl` — Feature scaler.
- `Customer-churn-prediction.csv` — Dataset.

## Results
The project compares multiple machine learning models and selects the best-performing model based on evaluation metrics.

## Author
Muhammad Adeel Qasim
