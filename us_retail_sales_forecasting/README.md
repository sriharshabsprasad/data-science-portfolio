# Retail Radar – U.S. Retail Sales Forecasting

## 🧠 Project Overview
This project uses time series forecasting techniques to analyze and predict retail sales trends in the United States, helping businesses optimize inventory and pricing strategies.

## 🎯 Objectives
- Forecast monthly retail sales using historical data.
- Evaluate model performance and forecast accuracy.
- Visualize trends and seasonality.

## 🛠️ Technical Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Statsmodels, Scikit-learn, XGBoost  
- **Tools:** Jupyter Notebook

## 📁 Project Structure
us_retail_sales_forecasting/
│
├── data/
│   └── us_retail_sales.csv  
├── us_retail_time_series_analysis.ipynb
├── images/
│   └── forecast_plot.png
└── README.md

## 📊 Key Features
- Time series decomposition (trend, seasonality, residual)
- ARIMA, SARIMA, and XGBoost regressors
- Rolling forecast and model diagnostics

## 📦 Dataset
- Source: [FRED Economic Data - U.S. Census Bureau](https://fred.stlouisfed.org/series/RSXFS)

## 🔍 Results
- SARIMA model yielded the most accurate forecasts.
- Clear seasonality patterns identified in sales cycles.

## 🚀 Usage
```bash
git clone https://github.com/sriharshabsprasad/data-science-portfolio.git
cd data-science-portfolio/us_retail_sales_forecasting
jupyter notebook
```