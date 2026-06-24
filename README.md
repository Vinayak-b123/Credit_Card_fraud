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
              feature  importance
16  night_transaction    0.469992
2                 amt    0.269410
1            category    0.072955
17           high_amt    0.025779
11               hour    0.025085
14                age    0.021902
7            city_pop    0.014422
4               state    0.012420
3                city    0.011428
10         merch_long    0.010171
13              month    0.009910
8                 job    0.009826
6                long    0.009760
5                 lat    0.008635
0            merchant    0.007565
15        distance_km    0.007302
9           merch_lat    0.006895
12                day    0.006542

Accuracy: 0.9986455051382468

              precision    recall  f1-score   support

           0       1.00      1.00      1.00     67596
           1       0.81      0.94      0.87       326

    accuracy                           1.00     67922
    macro avg       0.91      0.97      0.93     67922
    weighted avg       1.00      1.00      1.00     67922



<img width="666" height="547" alt="image" src="https://github.com/user-attachments/assets/d2cffe40-b619-44c1-8eed-973d07237494" />



