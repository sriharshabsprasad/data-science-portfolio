# LendSense – Loan Disbursal Risk Prediction

## 🧠 Project Overview
This project uses machine learning models to predict the risk of loan default based on borrower information, income, credit history, and loan terms.

## 🎯 Objectives
- Predict loan approval and identify risky applicants.
- Analyze financial and demographic indicators.
- Assist financial institutions in risk mitigation.

## 🛠️ Technical Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook

## 📁 Project Structure
loan_disbursal_risk_prediction/
│
├── data/
│   └── Loan_Train.csv
├── loan_disbursal_prediction.ipynb
├── images/
│   └── feature_importance.png
└── README.md

## 📊 Key Features
- Exploratory Data Analysis (EDA) and feature engineering
- Imputation, encoding, and scaling pipelines
- Classifiers: Logistic Regression, Random Forest, XGBoost
- ROC-AUC, Precision-Recall curves, Confusion Matrix

## 📦 Dataset
- Source: [Loan Prediction Dataset - Kaggle](https://www.kaggle.com/datasets/itsmesunil/bank-loan-modelling)

## 🔍 Results
- XGBoost achieved the highest AUC of 0.88.
- "Credit history", "Income", and "Loan amount" were top predictors.

## 🚀 Usage
```bash
git clone https://github.com/sriharshabsprasad/data-science-portfolio.git
cd data-science-portfolio/loan_disbursal_risk_prediction
jupyter notebook
```