# Brick by Brick – Real Estate Price Prediction

## 🧠 Project Overview
This project builds multiple machine learning models to predict real estate housing prices based on various property features. The dataset contains information about area, number of bedrooms, stories, amenities, and furnishing status.

## 🎯 Objectives
- Analyze and visualize key drivers of housing prices.
- Build and compare models for price prediction.
- Use insights for decision-making in real estate markets.

## 🛠️ Technical Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, XGBoost, LightGBM

## 📁 Project Structure
realestate_price_prediction/ │ ├── data/ │ └── housing.csv ├── real_estate_housing_price_prediction.ipynb ├── images/ │ └── feature_importance.png ├── README.md


## 📊 Key Features
- Data visualization and correlation heatmaps
- Handling missing data and encoding categorical variables
- Multiple regression models: Linear, Random Forest, SVM, Gradient Boosting
- Model performance comparison (MAE, RMSE, R²)

## 📦 Dataset
- Source: [Housing Prices Dataset - Kaggle](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)

## 🔍 Results
- The Gradient Boosting model yielded the best performance.
- Identified "Area", "Number of bedrooms", and "Furnishing status" as top predictors.
