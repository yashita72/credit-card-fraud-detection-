💳 Credit Card Fraud Detection using Logistic Regression
📌 Project Overview

Credit card fraud is a critical financial problem where fraudulent transactions are rare but highly impactful.
This project aims to detect fraudulent credit card transactions using Logistic Regression, with a strong focus on handling highly imbalanced data and using appropriate evaluation metrics.

🎯 Problem Statement

The dataset contains a very small percentage of fraudulent transactions compared to genuine ones.
The challenge is to correctly identify fraud cases while minimizing false negatives, as missing a fraud transaction can be costly.

📂 Dataset Information

Source: European Credit Card Transactions Dataset

Total Transactions: 284,807

Fraudulent Transactions: 492

Features:

V1 to V28 (PCA-transformed features)

Time, Amount

Class (0 = Genuine, 1 = Fraud)

Due to confidentiality, original feature names are anonymized.

🧠 Model Used

Logistic Regression

Chosen for:

Interpretability

Efficiency

Industry relevance in fraud detection

Class imbalance handled using:

class_weight = 'balanced'

🔄 Project Workflow

Data loading and exploration

Handling missing values

Stratified train-test split to preserve class distribution

Feature scaling using StandardScaler

Model training using Logistic Regression

Model evaluation using suitable metrics

📊 Evaluation Metrics

Since the dataset is highly imbalanced, accuracy is not a reliable metric.

The model is evaluated using:

Precision

Recall (important to reduce missed fraud cases)

F1-Score

ROC–AUC Score

Confusion Matrix

💡 Key Insights

Accuracy alone is misleading for imbalanced datasets

Recall is more important than precision in fraud detection

Logistic Regression performs well as a baseline model when evaluated correctly

Proper data splitting and evaluation strategy matter more than complex models

🛠 Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib# credit-card-fraud-detection-
