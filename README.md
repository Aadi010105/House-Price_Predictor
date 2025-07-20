# 📊 House Price Prediction using Machine Learning

## 📌 Introduction

Accurate prediction of house prices is crucial for real estate investors, buyers, and policy makers. Traditional valuation methods rely heavily on manual appraisals, which can be biased and inconsistent. Our project leverages **machine learning regression models** to predict housing prices based on features like area, location, number of rooms, and more.

## 🎯 Problem Statement

Real estate pricing involves numerous variables and market dynamics. Manual price prediction can lead to inaccuracies, causing financial losses. This project aims to develop a **data-driven, ML-based regression system** that:

- Predicts house prices from structured data.
- Compares performance across **multiple regression models**.
- Selects the best-fit model for optimal price estimation.

## 🏆 Objectives

- Analyze key features influencing house prices.
- Train and evaluate **multiple regression algorithms**.
- Use **cross-validation and hyperparameter tuning**.
- Compare model performance based on **R² scores**.

## 📊 Dataset Description

The dataset contains various features that impact house prices, such as:

- Lot Area, Overall Quality, Year Built
- Garage Area, Number of Bathrooms, etc.

### ✅ Data Preprocessing

- **Handling missing values** using imputation.
- **Encoding categorical features** using one-hot encoding.
- **Feature scaling** for numeric attributes using StandardScaler.

## 🏗️ Methodology

### 🔹 Models Trained

We trained and compared the following regression models:

1. **Linear Regression**
2. **Ridge Regression**
3. **Lasso Regression**
4. **Random Forest Regressor**
5. **XGBoost Regressor**

> **Note:** SVR was listed but **not implemented** in the final code. Also, **ElasticNet** was written incorrectly in the initial version and is now corrected.

### 🔹 Model Evaluation

Each model was evaluated using **cross-validation** and scored using **R² metric**. Below is the comparison:

| Model                   | R² Score                      |
|------------------------|-------------------------------|
| Linear Regression       | 0.5497                        |
| Ridge Regression        | 0.5497                        |
| Lasso Regression        | 0.5497                        |
| Random Forest Regressor | 0.1723                        |
| XGBoost Regressor ✅     | **0.9798** (on training data) |

## 🚀 Results

- **XGBoost Regressor** gave the best results on the training set with an R² of **0.9798**.
- Linear models performed equally with moderate accuracy (~0.55 R²).
- Random Forest underperformed on the given dataset.

## 🔮 Future Work

- Implement **SVR and Gradient Boosting** for full comparison.
- Apply **feature selection techniques** to improve performance.
- Prevent **overfitting** by tuning tree-based models.
- Deploy the best model using **Flask or Streamlit**.

## 👥 Contributors

- **Aaditiya Jain** (Manipal University Jaipur)
