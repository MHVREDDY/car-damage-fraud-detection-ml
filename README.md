# Car Damage Fraud Detection Using Machine Learning

## 📌 Project Overview

This project implements a machine learning system to detect fraudulent claims related to physical damage in car insurance. It processes a real-world dataset, performs data cleaning and feature engineering, and compares multiple classification algorithms to accurately predict fraudulence in claims.

## 🧠 Objective

To build an efficient and reliable model that helps insurance companies automatically identify suspicious car damage claims and reduce fraud-related losses.

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy for data handling  
- Scikit-learn for machine learning algorithms  
- Matplotlib, Seaborn for data visualization  

## 📂 Dataset

- Dataset includes features such as driver demographics, claim details, vehicle info, and claim metadata.  
- Data preprocessing includes handling missing values and encoding categorical variables.  

## ⚙️ Methodology

1. **Data Cleaning:** Imputing missing values using KNN and SimpleImputer.  
2. **Feature Engineering:** Label encoding of categorical variables.  
3. **Data Splitting:** Train-test split (70%-30%).  
4. **Feature Scaling:** MinMax scaling applied.  
5. **Model Training:** Logistic Regression, Decision Tree, Random Forest, Extra Trees, and K-Nearest Neighbors.  
6. **Model Evaluation:** Accuracy, Precision, Recall, F1-Score, ROC AUC, and ROC Curve visualization.  
7. **Model Comparison:** Select best model based on ROC AUC.  
