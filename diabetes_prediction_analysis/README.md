# Glucose Guardian – Diabetes Prediction and Analysis

## 🧠 Project Overview
This project aims to diagnostically predict whether a patient has diabetes using the **Pima Indian Diabetes dataset**. The dataset contains diagnostic measurements from female patients of at least 21 years of age. The analysis includes descriptive statistics, visualizations, hypothesis testing, and multiple regression techniques.

## 🎯 Objectives
- Understand the relationships among health-related variables.
- Perform hypothesis testing to explore factors associated with diabetes.
- Build predictive models using linear regression (simple & multiple).

## 🛠️ Technical Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, scikit-learn, statsmodels

## 📁 Project Structure
diabetes_prediction_analysis/ │ ├── data/ │ └── diabetes.csv ├── diabetes_analysis_prediction.ipynb ├── images/ │ └── correlation_heatmap.png ├── README.md


## 📊 Key Features
- Descriptive statistical analysis and data cleaning
- Hypothesis testing using `scipy.stats`
- Correlation analysis with heatmaps
- Linear regression (one and multiple variables)
- Evaluation metrics like R² and RMSE

## 📦 Dataset
- Source: [Pima Indians Diabetes Database - Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

## 🔍 Results
- Found that features like Glucose, BMI, and Age are significantly correlated with diabetes outcome.
- Regression models show promising accuracy in predicting diabetes status.
