# 💰 InsureIQ

### 🤖 AI-Powered Medical Insurance Cost Prediction using XGBoost

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge\&logo=python)
![XGBoost](https://img.shields.io/badge/XGBoost-Regressor-green?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-MachineLearning-orange?style=for-the-badge\&logo=scikitlearn)
![Streamlit](https://img.shields.io/badge/Streamlit-WebApp-red?style=for-the-badge\&logo=streamlit)

</p>

<p align="center">
  <b>Predict personalized medical insurance charges using Machine Learning and advanced regression models.</b>
</p>

---

## 🚀 Live Demo

🌐 **Try the application here:**

https://supremeinferno-insurance-app.streamlit.app

---

## 📌 Project Overview

InsureIQ is a Machine Learning-powered insurance analytics application that estimates an individual's annual medical insurance charges based on demographic, lifestyle, and health-related factors.

The project leverages **XGBoost Regressor** optimized using **GridSearchCV** to generate accurate insurance cost predictions through a modern and interactive Streamlit dashboard.

The application helps users understand how factors such as age, BMI, smoking habits, region, and family size influence insurance costs.

> ⚠️ Disclaimer: Predictions are generated using a Machine Learning model and are intended for educational and analytical purposes only.

---

## 📸 Application Preview

### 🏠 Dashboard

<p align="center">
  <img src="assets/home.png" width="900">
</p>

### 📊 Prediction Results

<p align="center">
  <img src="assets/prediction.png" width="900">
</p>

---

## ✨ Features

✅ Medical Insurance Cost Prediction

✅ AI-Powered Risk Assessment

✅ XGBoost Regression Model

✅ Hyperparameter Optimization using GridSearchCV

✅ Real-Time Predictions

✅ Interactive Streamlit Dashboard

✅ BMI Category Analysis

✅ Insurance Cost Insights

✅ Modern Dark-Themed User Interface

✅ Responsive User Experience

---

## 📊 Dataset Information

The model was trained on a medical insurance dataset containing:

| Attribute       | Value   |
| --------------- | ------- |
| Records         | 1338    |
| Features        | 6       |
| Target Variable | Charges |

### 📋 Features Used

* Age
* Gender
* BMI
* Number of Children
* Smoking Status
* Region

### 🎯 Target Variable

* Insurance Charges

---

## 🧹 Data Preprocessing

The following preprocessing pipeline was implemented:

* Data Cleaning
* Categorical Variable Encoding
* Feature Engineering
* BMI Category Generation
* Feature Scaling using StandardScaler
* Train-Test Split (80:20)
* Model Optimization using GridSearchCV

---

## 🤖 Models Evaluated

Multiple regression algorithms were tested:

| Model             | Purpose                 |
| ----------------- | ----------------------- |
| Linear Regression | Baseline Model          |
| XGBoost Regressor | Advanced Ensemble Model |

---

## 🏆 Final Model

The deployed application uses:

```python
XGBRegressor()
```

### Why XGBoost?

XGBoost was selected because it:

* Captures complex feature relationships
* Handles non-linear patterns effectively
* Provides strong predictive performance
* Performs well on tabular datasets
* Supports advanced hyperparameter optimization

---

## ⚙️ Hyperparameter Optimization

GridSearchCV was used to identify the best model configuration.

### Best Cross-Validation Score

```text
0.8603
```

### Best Parameters

```python
{
    'colsample_bytree': 1.0,
    'learning_rate': 0.01,
    'max_depth': 3,
    'n_estimators': 300,
    'subsample': 0.8
}
```

---

## ⚙️ Technology Stack

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Joblib

### Framework

* Streamlit

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Feature Engineering
   ↓
Categorical Encoding
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
GridSearchCV Optimization
   ↓
XGBoost Regression
   ↓
Streamlit Deployment
```

---

## 📈 Prediction Factors

The estimated insurance charges are influenced by:

* Age
* Body Mass Index (BMI)
* Smoking Status
* Number of Children
* Geographic Region
* Gender

Among these factors, smoking status and BMI often have the most significant impact on insurance costs.

---

## 📂 Project Structure

```text
insurance-risk-prediction/
│
├── insurance.py
├── insurance.ipynb
├── insurance.csv
├── xgb_model.joblib
├── scaler.joblib
├── columns.joblib
├── requirements.txt
├── README.md
│
└── assets/
    ├── home.png
    └── prediction.png
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/supremeinferno/insurance-risk-prediction.git
```

### Navigate to Project Directory

```bash
cd insurance-risk-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Streamlit Application

```bash
streamlit run insurance.py
```

---

## 🔮 Future Improvements

* SHAP Explainability Integration
* Insurance Cost Breakdown Analysis
* Feature Importance Visualization
* Comparative Premium Analysis
* User Authentication System
* Historical Prediction Tracking
* Cloud Database Integration

---

## 👨‍💻 Author

### Pranav Garg

Passionate about:

* Machine Learning

🔗 GitHub: https://github.com/supremeinferno
