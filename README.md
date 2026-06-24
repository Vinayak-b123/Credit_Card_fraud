# Credit Card Fraud Detection

A machine learning project that predicts whether a credit card transaction is fraudulent using transaction, customer, and merchant information.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Class imbalance handling
- Model comparison across:
  - Logistic Regression
  - Linear SVC
  - Random Forest
  - KNN
  - XGBoost
  - LightGBM
- Hyperparameter tuning
- Model serialization with Pickle

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- Matplotlib

## Results

Models were evaluated using:

- Precision
- Recall
- F1 Score
- ROC-AUC
- PR-AUC

The best-performing model was selected based on its ability to detect fraudulent transactions while minimizing false positives.

Best performing: XGBoost with weights
