# Popcorn Picks – Movie Recommendation System

## 🧠 Project Overview
This project builds a hybrid movie recommendation system by combining collaborative filtering and content-based filtering techniques. By analyzing user behavior and movie metadata from the MovieLens dataset, it generates dynamic and personalized movie suggestions.

## 🎯 Objectives
- Recommend movies based on user preferences and item similarity.
- Compare collaborative, content-based, and hybrid approaches.
- Enhance user engagement through personalized content delivery.

## 🛠️ Technical Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Surprise, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook

## 📁 Project Structure
movie_recommendation_systems/
│
├── data/
│   └── movies.csv  
│   └── ratings.csv  
├── movie_recommender_systems.ipynb
├── images/
│   └── recommendation_flowchart.png
└── README.md

## 📊 Key Features
- Collaborative filtering using user-item rating matrix (Surprise library)
- Content-based filtering using TF-IDF and cosine similarity
- Hybrid recommendation combining both methods
- Evaluation using RMSE, precision@k, and recall@k

## 📦 Dataset
- Source: [MovieLens Dataset - GroupLens](https://grouplens.org/datasets/movielens/)

## 🔍 Results
- The hybrid model improved accuracy and relevance of recommendations.
- Users received better suggestions by blending rating history with movie attributes.

## 🚀 Usage
```bash
git clone https://github.com/sriharshabsprasad/data-science-portfolio.git
cd data-science-portfolio/movie_recommendation_systems
jupyter notebook
```