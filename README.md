# 🚀 Predictive Insurance Pricing System

An end-to-end Machine Learning project that predicts medical insurance charges using statistical analysis, feature engineering, and Linear Regression.

The application is deployed using Streamlit and allows users to estimate insurance charges in real time based on healthcare and financial attributes.

---

## 🌐 Live Demo

https://predictive-insurance-pricing-system-qnmpk5cxusutnndxyfsknk.streamlit.app/

---

## 📌 Problem Statement

Insurance providers must accurately estimate medical insurance charges based on various customer attributes such as claim amount, hospital expenditure, annual salary, smoking habits, and family details.

The objective of this project is to build a predictive system capable of estimating insurance charges using historical healthcare-related data and machine learning techniques.

---

## 🎯 Project Objectives

* Analyze healthcare and insurance-related data
* Identify significant factors influencing insurance charges
* Build a predictive regression model
* Evaluate model performance and reliability
* Deploy the model for real-time predictions

---

## 📊 Exploratory Data Analysis (EDA)

Performed comprehensive exploratory data analysis to understand:

* Data distributions
* Missing values
* Feature relationships
* Outlier behavior
* Correlation patterns

---

## 🧹 Data Cleaning & Preprocessing

### Missing Value Handling

Applied:

* Mean Imputation
* Median Imputation
* Mode Imputation

Analyzed skewness and used Median Imputation for skewed features to maintain data stability.

---

## 📈 Outlier Detection & Treatment

Implemented:

### Box Plot Analysis

### Interquartile Range (IQR) Method

Used IQR analysis to identify and handle extreme values that could negatively impact model performance.

---

## 🔍 Correlation & Multicollinearity Analysis

Performed:

### Correlation Matrix Analysis

to understand linear relationships among variables.

Applied:

### Variance Inflation Factor (VIF)

to detect and reduce multicollinearity.

---

## 📊 Statistical Hypothesis Testing

Conducted:

* T-Test
* ANOVA

These statistical tests helped identify significant features contributing to insurance charge prediction.

---

## ⚙️ Feature Engineering

Implemented:

* Feature Selection
* Feature Encoding
* Data Transformation
* Feature Scaling (Standardization)

Created an optimized preprocessing pipeline for model training.

---

## 🤖 Model Building

Algorithm Used:

### Linear Regression

Workflow:

1. Data Preprocessing
2. Train-Test Split
3. Model Training
4. Model Testing
5. Model Evaluation
6. Bias-Variance Assessment

---

## 📉 Model Evaluation

Evaluated model performance using:

* Regression Metrics
* Prediction Analysis
* Bias-Variance Assessment

These evaluations helped validate the model's predictive capability.

---

## 🚀 Deployment

The trained model was:

* Saved using Joblib
* Integrated with Streamlit
* Deployed using GitHub and Streamlit Cloud

Users can provide input values and receive real-time insurance charge predictions in:

* USD
* INR

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Statistical Analysis
* T-Test
* ANOVA
* VIF
* Linear Regression
* Joblib
* Streamlit
* GitHub

---

## 📁 Project Structure

```text
Predictive-Insurance-Pricing-System/
│
├── app.py
├── linear_regression_model.joblib
├── scaler.pkl
├── new_insurance_data.csv
├── Processed_Insurance_data.csv
├── requirements.txt
└── README.md
```

---

## 📂 Dataset Files

### new_insurance_data.csv

Raw insurance dataset used for data exploration, preprocessing, and feature analysis.

### Processed_Insurance_data.csv

Cleaned and preprocessed dataset after handling missing values, outliers, feature engineering, and data transformations used for model development.

---

## 💡 Key Learnings

* Practical application of statistical analysis in machine learning
* Missing value treatment strategies
* Outlier detection using IQR
* Multicollinearity analysis using VIF
* Feature engineering and scaling
* Linear Regression model development
* Model deployment using Streamlit
* End-to-end machine learning workflow

---

## 👨‍💻 Author

Daniel J

LinkedIn: https://www.linkedin.com/in/daniel-j77

GitHub: https://github.com/daniel-j77

---

## ⭐ Future Improvements

* Ensemble Regression Models
* XGBoost Regression
* Random Forest Regression
* Advanced Feature Selection Techniques
* Cloud-Based Deployment
* Model Monitoring and Performance Tracking
