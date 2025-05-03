# Diabetes Analyzer in R

## 🧠 Project Overview
This R-based project analyzes health data to predict the risk of diabetes using logistic regression, decision trees, and exploratory data analysis.

## 🎯 Objectives
- Build predictive models to classify diabetes risk.
- Analyze clinical and lifestyle features.
- Visualize health trends and feature importance.

## 🛠️ Technical Stack
- **Language:** R  
- **Libraries:** tidyverse, caret, ggplot2, rpart, e1071

## 📁 Project Structure
diabetes_risk_analysis_R/
│
├── data/
│   └── diabetes_012_health_indicators_BRFSS2015.csv  
│   └── diabetes_binary_5050split_health_indicators_BRFSS2015.csv 
│   └── diabetes_binary_health_indicators_BRFSS2015.csv 
├── diabetes_analyzer.Rmd
├── images/
│   └── decision_tree_plot.png
└── README.md

## 📊 Key Features
- EDA: histograms, boxplots, and pairwise correlation
- Logistic Regression, Decision Tree, Naive Bayes classifiers
- Confusion matrix and ROC-AUC evaluation

## 📦 Dataset
- Source: [Pima Indians Diabetes Dataset - UCI](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

## 🔍 Results
- Decision Tree achieved 78% accuracy.
- BMI, Glucose, and Age were key indicators of diabetes risk.
