# ALS Segments – Clustering ALS Patient Profiles

## 🧠 Project Overview
This project identifies distinct patient clusters in ALS (Amyotrophic Lateral Sclerosis) cases using unsupervised learning techniques to help medical professionals tailor treatment strategies.

## 🎯 Objectives
- Perform patient segmentation using clustering algorithms.
- Analyze symptoms, progression patterns, and demographics.
- Support personalized healthcare interventions.

## 🛠️ Technical Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib  
- **Tools:** Jupyter Notebook

## 📁 Project Structure
als_segments_clustering/
│
├── data/
│   └── als_data.csv  
├── als_clustering.ipynb
├── images/
│   └── clusters_visualization.png
└── README.md

## 📊 Key Features
- K-Means and Hierarchical clustering
- PCA for dimensionality reduction and visualization
- Silhouette score and elbow method for optimal cluster evaluation

## 📦 Dataset
- Source: Simulated ALS dataset for educational analysis

## 🔍 Results
- Identified 3 distinct clusters indicating varying progression stages and treatment responses.
- PCA visualization showed clear separation among segments.

## 🚀 Usage
```bash
git clone https://github.com/sriharshabsprasad/data-science-portfolio.git
cd data-science-portfolio/als_segments_clustering
jupyter notebook
```