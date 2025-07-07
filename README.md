# Bank Customer Churn Prediction

A machine learning classification project aimed at predicting whether a customer will churn (i.e., leave the bank) based on various demographic and account-related features.

## 📌 Overview

Customer churn is a significant issue for businesses, especially in the banking sector where retaining existing customers is often more cost-effective than acquiring new ones. This project builds and evaluates multiple machine learning models to accurately predict churn using historical customer data.

## 🔍 Objectives

- Build a classification model to predict customer churn.
- Handle class imbalance using SMOTE.
- Evaluate and compare different ML algorithms.
- Optimize model performance with hyperparameter tuning and cross-validation.

## 🛠️ Technologies & Tools

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **SMOTE** from imbalanced-learn

## 📊 Algorithms Used

- Random Forest
- K-Nearest Neighbors
- Decision Tree

## ⚙️ Methodology

1. **Exploratory Data Analysis (EDA)**  
   - Analyzed feature distributions, correlations, and outliers.

2. **Preprocessing**  
   - Handled missing values, encoded categorical variables, and scaled numerical features.

3. **Class Imbalance Handling**  
   - Applied **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset.

4. **Model Training and Evaluation**  
   - Trained models using **Random Forest**, **KNN**, and **Decision Tree**.
   - Performed **K-Fold Cross-Validation**.
   - Conducted **hyperparameter tuning** for optimal performance.

5. **Results**  
   - Achieved a maximum prediction accuracy of **86%**.
   - Best model: **Random Forest**
   - SMOTE improved minority class prediction significantly
   - K-Fold CV ensured model robustness and reduced overfitting

## ✅ Future Improvements

- Add more features related to customer behavior
- Use ensemble techniques like XGBoost or LightGBM
- Deploy the model via Flask or Streamlit for real-time prediction

## 📚 Keywords

`Classification` · `Churn Prediction` · `SMOTE` · `Random Forest` · `K-Fold Cross Validation`

