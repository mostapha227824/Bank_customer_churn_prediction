# Bank Customer Churn Prediction

This repository contains an end-to-end project to predict customer churn in the banking industry using machine learning. The workflow includes data preprocessing, clustering, individual and ensemble models, and handling imbalanced datasets.

## Table of Contents
1. [Dataset](#dataset)
2. [Features](#features)
3. [Project Workflow](#project-workflow)
4. [Technologies Used](#technologies-used)
5. [Setup](#setup)
6. [Results](#results)
7. [Contributors](#contributors)

## Dataset
The dataset includes customer demographic and account information to predict churn (whether the customer left the bank).  
- **Target**: `Exited` (1 = churned, 0 = retained).

## Features
Key attributes:
- **Numerical**: `Credit Score`, `Age`, `Balance`, `Estimated Salary`.
- **Categorical**: `Geography`, `Gender`, `HasCrCard`, `IsActiveMember`.

## Project Workflow
1. **Data Exploration and Preprocessing**:
   - Handle missing values, outliers, and scaling.
2. **Clustering**:
   - Identify customer groups using K-Means or DBSCAN.
3. **Modeling**:
   - Train individual models (SVM, Logistic Regression, Random Forest).
   - Build ensembles (Bagging, Boosting, Stacking).
4. **Imbalanced Data Handling**:
   - Methods: SMOTE, undersampling, class weighting.
5. **Evaluation**:
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC.

## Technologies Used
- **Python**: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn.
- **Clustering**: K-Means, DBSCAN.
- **Models**: SVM, Logistic Regression, Random Forest, XGBoost.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bank-customer-churn-prediction.git
   cd bank_customer_churn_prediction
# Bank_customer_churn_prediction
Predict customer churn in the banking industry using machine learning models. Includes data analysis, clustering, individual and ensemble models, and handling imbalanced data with advanced evaluation metrics like confusion matrices and ROC curves.
