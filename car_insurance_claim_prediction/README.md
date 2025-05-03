# Driven to Predict – Car Insurance Claim Prediction

## 🧠 Project Overview
This project predicts the likelihood of a car insurance claim based on vehicle specifications, policyholder information, and accident history using classification models.

## 🎯 Objectives
- Identify potential high-risk policyholders.
- Enhance underwriting and pricing strategies.
- Reduce fraudulent claims through predictive modeling.

## 🛠️ Technical Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook

## 📁 Project Structure
car_insurance_claim_prediction/
│
├── data/
│   └── train.csv 
├── car_insurance_claim_prediction.ipynb
├── images/
│   └── feature_importance_chart.png
└── README.md

## 📊 Key Features
- Feature engineering and data preprocessing
- Class balancing and model tuning with GridSearchCV
- Classification models: Logistic Regression, Random Forest, XGBoost, LightGBM
- Evaluation: ROC-AUC, F1-Score, Confusion Matrix

## 📦 Dataset
- Source: [Car Insurance Claim Dataset - Kaggle](https://www.kaggle.com/datasets/sagnik1511/car-insurance-claim)

## 🔍 Results
- LightGBM achieved an AUC score of 0.92.
- Age, Driving experience, and Vehicle age were key predictors.

## 🚀 Usage
```bash
git clone https://github.com/sriharshabsprasad/data-science-portfolio.git
cd data-science-portfolio/car_insurance_claim_prediction
jupyter notebook
```