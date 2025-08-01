# DEVELOPERS_HUB_INTERNSHIP_ASSIGNMENT1
## 🔹 Tasks Overview

This repository contains internship project submissions for Developers Hub AI/ML Internship, showcasing work on regression and classification tasks using real-world datasets.

---
# Task 2: Predict Future Stock Prices

## 🔍 Objective
Use historical stock data to predict the next day's closing price using regression models.

## 📈 Stock Used
- Apple Inc. (AAPL)

## 📂 Dataset
- Source: Yahoo Finance (via yfinance API)
- Timeframe: 2020-01-01 to 2025-08-01

## 📊 Features Used
- Open Price
- High Price
- Low Price
- Volume

## 🎯 Target Variable
- Next Day's Closing Price

## 🛠️ Models Applied
- Linear Regression
- Random Forest Regressor

## 🔢 Evaluation Metrics
| Model              | Mean Squared Error (MSE) | R² Score |
|-------------------|---------------------------|------------|
| Linear Regression | 18.19                     | 0.92       |
| Random Forest     | 548.53                    | -1.38      |

## 📉 Visualization
The following plot compares actual vs predicted closing prices using Random Forest:

![AAPL Actual vs Predicted](5ee3883e-3425-4b2c-809f-9455bd3fa25c.png)

## 💪 Tech Stack
- Python
- yfinance
- pandas, numpy
- scikit-learn
- matplotlib, seaborn



## 🔹 Task 3: Heart Disease Prediction

**Objective:**  
To build a classification model to predict whether a person is likely to have heart disease based on various medical attributes.

**Dataset Used:**  
- UCI Heart Disease dataset consisting of 14 features and 303 records.

**Features:**
- Numerical: `age`, `trestbps` (resting blood pressure), `chol` (serum cholesterol), `thalach` (max heart rate), `oldpeak` (ST depression)
- Categorical: `sex`, `cp` (chest pain type), `fbs` (fasting blood sugar), `restecg`, `exang`, `slope`, `ca`, `thal`
- Target: `target` (0 = No disease, 1 = Heart disease)

**Steps Performed:**
- Data Cleaning (handled missing values using KNN Imputer)
- Exploratory Data Analysis (correlation heatmap, target distribution)
- Feature scaling using StandardScaler
- Model training using Logistic Regression and Decision Tree
- Model evaluation using:
  - Accuracy
  - Confusion Matrix
  - ROC-AUC Curve
- Feature importance analysis to highlight the most impactful features

**Results:**
- Accuracy (Logistic Regression): ~...
- Accuracy (Decision Tree): ~...
- Key Features: `cp`, `thalach`, `oldpeak`, `ca`, `thal`

---


### Task 6: House Price Prediction

**Objective:**  
To build a regression model that can predict house prices based on several features such as area, number of bedrooms, bathrooms, presence of amenities, and furnishing status.

**Dataset Used:**  
- A dataset of 545 residential houses with 13 features including both numerical and categorical variables.

**Features:**
- Numerical: `price`, `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
- Categorical: `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`

**Steps Performed:**
- Data cleaning and preprocessing
- Categorical encoding using OneHotEncoder
- Feature scaling using StandardScaler
- Model training using Linear Regression
- Model evaluation using RMSE and R² score

**Results:**
- RMSE: ~...
- R² Score: ~...
- Insights: The model shows good generalization on test data and identifies key influential features in price prediction.

---

## 👤 Developer Info
- Internship: Developers Hub - AI/ML Track Assignemt_1
- Duration: Summer 2025
- ----
