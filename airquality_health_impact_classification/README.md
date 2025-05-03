# AirAware – Air Quality Health Impact Classification

## 🧠 Project Overview
This project classifies the health impact of air quality levels using machine learning techniques based on PM2.5, PM10, CO, and NO2 concentrations.

## 🎯 Objectives
- Predict health risk categories from air pollution data.
- Analyze pollutant contribution to poor air quality.
- Assist in environmental health planning and awareness.

## 🛠️ Technical Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook

## 📁 Project Structure
airquality_health_impact_classification/
│
├── data/
│   └── air_quality_health_impact_data.csv 
├── airquality_health_impact_classification.ipynb
├── images/
│   └── pollutant_correlation.png
└── README.md

## 📊 Key Features
- Pollution trend visualization and correlation analysis
- Categorical label creation for AQI-based health impact
- Classifiers: Random Forest, XGBoost, SVM
- Precision, Recall, Confusion Matrix, and AUC

## 📦 Dataset
- Source: [Air Quality Dataset - OpenAQ / Kaggle](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)

## 🔍 Results
- XGBoost achieved over 85% classification accuracy.
- PM2.5 and NO2 were major contributors to adverse health effects.

## 🚀 Usage
```bash
git clone https://github.com/sriharshabsprasad/data-science-portfolio.git
cd data-science-portfolio/airquality_health_impact_classification
jupyter notebook
```