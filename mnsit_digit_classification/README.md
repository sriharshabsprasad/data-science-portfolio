# MNIST Vision – Handwritten Digit Classifier

## 🧠 Project Overview
This project develops an image classification model using the MNIST dataset to recognize handwritten digits (0-9) using neural networks and CNNs.

## 🎯 Objectives
- Build a high-accuracy image classifier for handwritten digits.
- Compare simple dense models with convolutional neural networks.
- Visualize learning performance with confusion matrix and accuracy plots.

## 🛠️ Technical Stack
- **Language:** Python  
- **Libraries:** TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn  
- **Tools:** Jupyter Notebook

## 📁 Project Structure
mnsit_digit_classification/
│
├── CNN_Image_Classifier.ipynb
├── images/
│   └── accuracy_vs_loss.png
└── README.md

## 📊 Key Features
- Dense and CNN architectures with dropout and batch normalization
- Early stopping and model checkpointing
- Evaluation metrics: Accuracy, Confusion Matrix, Classification Report

## 📦 Dataset
- Source: [MNIST Handwritten Digits Dataset](http://yann.lecun.com/exdb/mnist/)

## 🔍 Results
- CNN model achieved 99.1% test accuracy.
- Visualizations showed strong generalization and minimal overfitting.

## 🚀 Usage
```bash
git clone https://github.com/sriharshabsprasad/data-science-portfolio.git
cd data-science-portfolio/mnsit_digit_classification
jupyter notebook
```