# Review Rater – Sentiment Analysis on Movie Reviews

## 🧠 Project Overview
This project performs sentiment analysis on movie reviews to classify them as positive or negative using NLP techniques and classification models.

## 🎯 Objectives
- Preprocess and vectorize text data.
- Train machine learning models to classify sentiment.
- Evaluate and visualize model performance.

## 🛠️ Technical Stack
- **Language:** Python  
- **Libraries:** NLTK, Scikit-learn, Pandas, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook

## 📁 Project Structure
sentiment_analysis_movie_reviews/
│
├── data/
│   └── labeledTrainData.tsv
├── sentiment_analysis.ipynb
├── images/
│   └── confusion_matrix.png
└── README.md

## 📊 Key Features
- Text preprocessing: tokenization, stop word removal, stemming
- TF-IDF vectorization
- Classifiers: Logistic Regression, Naive Bayes, SVM
- Performance metrics: Accuracy, Precision, Recall, F1-score

## 📦 Dataset
- Source: [IMDb Movie Reviews Dataset - Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## 🔍 Results
- Logistic Regression achieved 89% accuracy on the test set.
- Positive and negative reviews were classified with high precision.

## 🚀 Usage
```bash
git clone https://github.com/sriharshabsprasad/data-science-portfolio.git
cd data-science-portfolio/sentiment_analysis_movie_reviews
jupyter notebook
```