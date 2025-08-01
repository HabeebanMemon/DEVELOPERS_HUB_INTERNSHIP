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
|-------------------|---------------------------|----------|
| Linear Regression | 18.19                     | 0.92     |
| Random Forest     | 548.53                    | -1.38    |

## 📉 Visualization
The following plot compares actual vs predicted closing prices using Random Forest:

![AAPL Actual vs Predicted](5ee3883e-3425-4b2c-809f-9455bd3fa25c.png)

## 💪 Tech Stack
- Python
- yfinance
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---
# Task 3: Heart Disease Prediction

## 🔍 Objective
Build a classification model to predict whether a person is likely to have heart disease based on various medical attributes.

## 📂 Dataset
- UCI Heart Disease dataset with 14 features and 303 records.

## 📊 Features Used
- **Numerical:** `age`, `trestbps`, `chol`, `thalach`, `oldpeak`
- **Categorical:** `sex`, `cp`, `fbs`, `restecg`, `exang`, `slope`, `ca`, `thal`
- **Target:** `target` (0 = No disease, 1 = Heart disease)

## 🧪 Steps Performed
- Data cleaning (KNN Imputer for missing values)
- Exploratory Data Analysis
- Feature scaling using StandardScaler
- Model training using Logistic Regression and Decision Tree
- Model evaluation:
  - Accuracy
  - Confusion Matrix
  - ROC-AUC Curve
- Feature importance analysis

## ✅ Results
- Accuracy (Logistic Regression): ~...
- Accuracy (Decision Tree): ~...
- Key Features: `cp`, `thalach`, `oldpeak`, `ca`, `thal`

---
# Task 6: House Price Prediction

## 🔍 Objective
Build a regression model to predict house prices using various structural and location-based features.

## 📂 Dataset
- 545 residential houses with 13 numerical and categorical features.

## 📊 Features Used
- **Numerical:** `price`, `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
- **Categorical:** `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`

## 🧪 Steps Performed
- Data cleaning and preprocessing
- Categorical encoding using OneHotEncoder
- Feature scaling using StandardScaler
- Model training using Linear Regression
- Model evaluation using RMSE and R² score

## ✅ Results
- RMSE: ~...
- R² Score: ~...
- Insights: The model generalizes well and identifies key features impacting house prices.

---
## 👤 Developer Info
- Internship: Developers Hub - AI/ML Track Assignment_1
- Duration: Summer 2025
