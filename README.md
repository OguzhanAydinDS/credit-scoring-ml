# 💳 Credit Scoring Using Machine Learning

This project focuses on predicting credit risk using supervised machine learning algorithms. Based on real-world financial data, it aims to classify applicants into “creditworthy” or “not creditworthy” categories.

## 📌 Problem Statement

Credit scoring is a crucial task for banks and financial institutions to assess the risk of lending. This project applies classification algorithms to predict credit default using features like income, credit history, employment status, and more.

## 📊 Dataset

- Source: [UCI Credit Approval Dataset](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))
- Size: 1000 entries
- Features: 20
- Target: Credit risk (Good/Bad)

## 🧪 Preprocessing

- Categorical feature encoding (LabelEncoding)
- Handling outliers
- Scaling numerical features (StandardScaler)
- Train-test split (80–20)

## 🤖 Models Applied

- Support Vector Machine (SVM)
- Random Forest Classifier
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
  - ROC-AUC Curve

## 🏆 Results

| Model         | Accuracy | F1 Score |
|---------------|----------|----------|
| Random Forest | **83.3%** | **0.81** |
| SVM           | 78.0%    | 0.76     |

The Random Forest model performed best overall and is recommended for this classification task.

## 📘 Thesis Context

This project is part of my MSc Data Analytics thesis, titled *"Evaluating Machine Learning Algorithms for Credit Scoring: Accuracy, Bias Mitigation, and Practical Trade-offs"*  
It includes secondary research, preprocessing strategies, and model benchmarking.


