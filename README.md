# 🫀 Heart Disease Prediction using Machine Learning

This project explores and compares multiple machine learning models to predict the presence of heart disease using clinical features.

## 📚 Project Overview

- **Dataset**: Heart Disease Dataset (Kaggle/UCI)
- **Objective**: Predict whether a patient has heart disease (binary classification)
- **Models Used**:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)

## 📈 Model Evaluation Summary

| Model                | Accuracy | F1-Score | Precision | Recall | AUC    |
|---------------------|----------|----------|-----------|--------|--------|
| Logistic Regression | 0.5870   | 0.5468   | 0.5730    | 0.5870 | 0.8173 |
| Random Forest       | 0.5707   | 0.5669   | 0.5866    | 0.5707 | 0.8289 |
| SVM                 | 0.5924   | 0.5487   | 0.5526    | 0.5924 | 0.8273 |
| KNN                 | 0.5598   | 0.5392   | 0.5638    | 0.5598 | 0.7925 |

> ✅ **Conclusion**: Random Forest had the highest AUC; SVM had the highest accuracy. Model selection should be based on your use-case (e.g. recall vs precision).

## 📌 Features Used

- Age
- Sex
- Chest pain type
- Resting BP
- Cholesterol
- Fasting Blood Sugar
- Rest ECG
- Max Heart Rate
- Exercise-induced Angina
- ST depression, etc.

