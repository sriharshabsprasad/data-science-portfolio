# Fake or Fact? – Building a Robust AI System for News Verification

## 🧠 Project Overview
This project tackles the rising issue of misinformation by developing an automated classification system that distinguishes between real and fake news articles. It integrates traditional machine learning (ML) techniques with advanced deep learning (DL) models to create a scalable and accurate detection pipeline.

## 🎯 Objectives
- Detect fake news articles using both ML and DL models.
- Analyze linguistic patterns in fake vs. real news.
- Evaluate multiple feature extraction techniques like TF-IDF and word embeddings.

## 🛠️ Technical Stack
- **Language:** Python  
- **ML Models:** Logistic Regression, Random Forest, XGBoost  
- **DL Models:** Dense Neural Network, BiLSTM  
- **Libraries:** Pandas, NumPy, Scikit-learn, NLTK, Keras, TensorFlow, GloVe  
- **Tools:** Jupyter Notebook

## 📁 Project Structure
fake_news_detection/
│
├── data/
│   └── Fake.csv  
│   └── True.csv  
├── notebook/
│   └── fake_news_classification.ipynb
├── images/
│   └── training_metrics_bilstm.png
└── README.md

## 📊 Key Features
- Text preprocessing with stopword removal, tokenization, lemmatization
- Feature engineering via TF-IDF and pretrained GloVe embeddings
- Classical ML models for fast, interpretable results
- Deep learning with BiLSTM for context-aware classification
- Evaluation with Precision, Recall, F1-score, ROC-AUC

## 📦 Dataset
- Source: [Fake and Real News Dataset - Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data)

## 🔍 Results
- BiLSTM showed highest performance with improved F1-score and ROC-AUC.
- TF-IDF worked well for traditional models while GloVe enhanced deep learning.
- The system is capable of distinguishing misinformation with high accuracy.

## 🚀 Usage
```bash
git clone https://github.com/sriharshabsprasad/data-science-portfolio.git
cd data-science-portfolio/fake_news_detection
jupyter notebook
```
