# Stay or Leave? – Telecom Customer Churn Prediction

## 🧠 Project Overview
This project addresses the problem of customer attrition (churn) in the telecom industry by building predictive models. It uses customer demographic and service usage data to predict whether a customer is likely to churn.

## 🎯 Objectives
- Identify patterns and signals associated with customer churn.
- Build predictive models to reduce churn and retain customers.
- Recommend retention strategies based on insights.

## 🛠️ Technical Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, XGBoost, imbalanced-learn

## 📁 Project Structure
telecom_customer_churn_prediction/ │ ├── data/ │ └── Customer Churn.csv ├── customer_churn_prediction.ipynb ├── images/ │ └── churn_distribution.png ├── README.md

## 📊 Key Features
- Exploratory Data Analysis (EDA) & SMOTE for handling class imbalance
- Tree-based models: Decision Tree, Random Forest, XGBoost
- Feature importance and SHAP value visualization
- Model evaluation using Confusion Matrix, Precision, Recall, F1-Score

## 📦 Dataset
- Source: [Iranian Churn Dataset - UCI](https://archive.ics.uci.edu/dataset/563/iranian+churn+dataset)

## 🔍 Results
- XGBoost achieved the highest accuracy and F1-score.
- Service usage patterns and payment type were strong churn indicators.

