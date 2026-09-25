# AI-Powered Insurance Risk Prediction and Premium Optimization System

## 📌 Project Overview

Insurance companies face a major challenge in balancing profitability with fair pricing. Charging low premiums to high-risk customers can result in claim losses, while charging high premiums to low-risk customers can lead to customer churn and reduced market competitiveness.

This project develops an **AI-Powered Insurance Risk Prediction and Premium Optimization System** that predicts insurance claim costs, assesses customer risk levels, recommends personalized premiums, and helps insurance companies make data-driven decisions while maintaining profitability and customer satisfaction.

---

## 🎯 Problem Statement

Insurance companies must accurately estimate customer risk to determine fair and profitable premiums.

- **Underpricing high-risk customers** can lead to significant claim losses.
- **Overpricing low-risk customers** can cause customers to switch to competitors.

The objective of this project is to leverage Machine Learning techniques to predict expected claim costs, classify customer risk, recommend optimized insurance premiums, and support profitable business decisions.

---

## 🚀 Project Objectives

### 1. Risk Assessment
Predict customer risk levels based on demographic, health, and lifestyle factors.

### 2. Claim Cost Prediction
Estimate the expected insurance claim amount for individual customers.

### 3. Customer Segmentation
Group customers into risk-based segments using clustering techniques.

### 4. Premium Recommendation Engine
Recommend personalized insurance premiums based on predicted risk and expected claim costs.

### 5. Explainable AI
Provide model interpretability using SHAP to explain the factors influencing predictions.

### 6. Business Profitability Analysis
Estimate expected profit and support data-driven insurance pricing strategies.

---

## 📊 Dataset Information

**Dataset:** Health Insurance Dataset (Suresh Gupta)

### Features

| Feature | Description |
|----------|------------|
| age | Customer age |
| sex | Gender |
| weight | Weight |
| bmi | Body Mass Index |
| hereditary_diseases | Family medical history |
| no_of_dependents | Number of dependents |
| smoker | Smoking status |
| bloodpressure | Blood pressure level |
| diabetes | Diabetes status |
| regular_ex | Regular exercise status |
| job_title | Occupation |
| claim | Insurance claim amount (Target Variable) |

---

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records
- Removed unnecessary `city` column
- Handled missing values
- Converted data types
- Encoded categorical variables
- Feature engineering
- Prepared dataset for machine learning

---

## 📈 Exploratory Data Analysis (EDA)

Performed analysis on:

- Age Distribution
- BMI Distribution
- Blood Pressure Distribution
- Claim Amount Distribution
- Smoking vs Claim Analysis
- Diabetes vs Claim Analysis
- Hereditary Disease Analysis
- Correlation Analysis
- Risk Factor Identification

---

## 🤖 Machine Learning Models

### Claim Cost Prediction

Models evaluated:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- CatBoost Regressor

### Evaluation Metrics

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## ⚠️ Risk Scoring System

Customers are categorized into risk groups:

| Risk Score | Risk Category |
|------------|--------------|
| 0 – 30 | Low Risk |
| 31 – 70 | Medium Risk |
| 71 – 100 | High Risk |

---

## 👥 Customer Segmentation

K-Means Clustering is used to identify customer segments such as:

- Low-Risk Customers
- Moderate-Risk Customers
- High-Risk Customers

---

## 💰 Premium Recommendation Engine

The system recommends premiums using predicted claim costs.

### Formula

```text
Recommended Premium =
Predicted Claim Cost
+ Operational Cost
+ Profit Margin
```

### Expected Loss

```text
Expected Loss =
Claim Probability × Predicted Claim Amount
```

---

## 🔍 Explainable AI

SHAP (SHapley Additive exPlanations) is used to:

- Explain individual predictions
- Identify important risk factors
- Improve model transparency
- Support business decision-making

---

## 📊 Dashboard Features

### Executive Dashboard

- Total Customers
- Average Claim Cost
- Average Recommended Premium
- Expected Profit

### Risk Dashboard

- Risk Distribution
- High-Risk Customers
- Claim Trends

### Premium Dashboard

- Customer-wise Premium Recommendation
- Profitability Analysis

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- CatBoost
- SHAP

### Visualization
- Power BI

### Development Environment
- Jupyter Notebook
- Google Colab

---



## 📌 Business Impact

This project helps insurance companies:

- Reduce claim-related losses
- Improve risk assessment
- Recommend fair premiums
- Increase profitability
- Enhance customer retention
- Support data-driven decision-making

---

## 👨‍💻 Author

**Ashish Jaiswal**

Machine Learning | Data Science | Analytics

---

## ⭐ Future Enhancements

- Real-time premium prediction
- Fraud detection module
- Deep Learning-based risk prediction
- Cloud deployment
- MLOps integration
- Automated underwriting system
