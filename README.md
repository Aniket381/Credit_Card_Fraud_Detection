# 🕵️‍♂️ Credit Card Fraud Detection – Machine Learning Project

This project focuses on identifying fraudulent credit card transactions using a highly imbalanced dataset. It uses a logistic regression model as a baseline to detect anomalies in anonymized transaction features.

## 📁 Files

- `Fraud_Detection.ipynb` – Contains the complete process from data loading and preprocessing to model training and evaluation.
- Dataset used: [Credit Card Fraud Detection – Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## 📊 Dataset Overview

- **284,807** transactions
- Only **492** are labeled as fraud (Class = 1), making up just **0.17%** of the data
- Features `V1` to `V28` are principal components from PCA for confidentiality
- Additional fields include `Time`, `Amount`, and `Class` (target variable)

## 🧠 Techniques Used

- Logistic Regression (baseline model)
- Data splitting using `train_test_split`
- Accuracy evaluation using `accuracy_score`

## 📈 Key Challenges

- **Class imbalance**: The minority fraud class makes up less than 1% of the dataset, which can lead to misleading accuracy scores.
- The current model sets the foundation for further exploration using advanced classification strategies and evaluation metrics.

## 🚀 Future Improvements

- Apply advanced models: Random Forest, XGBoost, and Neural Networks
- Handle imbalance with:
  - SMOTE (Synthetic Minority Oversampling Technique)
  - Class weights in models
  - Undersampling majority class
- Evaluate with:
  - Confusion Matrix
  - ROC-AUC Curve
  - Precision, Recall, and F1 Score
- Deploy a real-time Streamlit dashboard for fraud alerting

## 🧠 Insight

> Accuracy is **not enough** when dealing with imbalanced data. The focus should be on **recall and precision** to minimize false negatives in fraud detection.

## 🔗 Project Link

[https://github.com/Aniket381/Credit_Card_Fraud_Detection](https://github.com/Aniket381/Credit_Card_Fraud_Detection)
