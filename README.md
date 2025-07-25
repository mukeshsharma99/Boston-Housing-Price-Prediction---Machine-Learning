# 🏡 Boston Housing Price Prediction - Machine Learning
   
## 📘 Overview

This project focuses on building a **machine learning model** that predicts **house prices in Boston** based on various features such as number of rooms, crime rate, accessibility to highways, and more.

We use the classic **Boston Housing dataset** available in **Scikit-learn** to train and evaluate multiple regression models.

---

## 🎯 Problem Statement

Given a set of attributes describing homes in various suburbs of Boston, the goal is to predict the **median house price**.

This is a **supervised regression problem**, and we'll approach it using different machine learning algorithms to identify the best-performing model.

---

## 🔍 Dataset Details

- 📦 Source: `sklearn.datasets.load_boston()` *(Note: Deprecated in newer versions)* 
- 📌 Features include:
  - CRIM – Crime rate
  - RM – Number of rooms
  - LSTAT – % lower status of the population
  - DIS – Distance to employment centers
  - PTRATIO – Pupil-teacher ratio
  - ...and more
- 🎯 Target: Median value of owner-occupied homes (in $1000s)

---

## 🧠 Workflow

1. **Load Dataset**  
2. **Data Preprocessing & Cleaning**
   - Handle missing values (if any)
   - Feature normalization/scaling
3. **Exploratory Data Analysis (EDA)**
   - Feature correlation heatmaps
   - Price trends with respect to features
4. **Model Building**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
5. **Model Evaluation**
   - Metrics: RMSE, MAE, R² Score
   - Cross-validation for robustness
6. **Model Comparison & Selection**

------------------------------------------------------
