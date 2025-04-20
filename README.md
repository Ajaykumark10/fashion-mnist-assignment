# Fashion MNIST Image Classification

This repository contains my machine learning project for classifying clothing images using the **Fashion MNIST** dataset.

## 📁 Dataset

- Source: [Fashion MNIST on Kaggle](https://www.kaggle.com/datasets/zalando-research/fashion-mnist)
- CSV Files:
  - `fashion-mnist_train.csv` ❌ *(too large to include in repo; download manually)*
  - `fashion-mnist_test.csv` ✅ *(included)*

## 🎯 Objectives

- Build multiple classifiers including **MLPClassifier**, **KNN**, **Logistic Regression**, **Decision Tree**, and **SVC**
- Tune hyperparameters using `RandomizedSearchCV`
- Use evaluation metrics like Accuracy, F1-Score, and Confusion Matrix
- Select the best-performing model for multi-class classification

## 📊 Metrics Used

- Accuracy Score
- Confusion Matrix (visualized)
- Classification Report (Precision, Recall, F1-score)

## 🛠️ Tech Stack

- Python
- scikit-learn
- pandas
- matplotlib / seaborn
- Jupyter Notebook

## 🚀 How to Use

1. Download `fashion-mnist_train.csv` from Kaggle and place it in the root folder.
2. Launch the `.ipynb` notebook in Jupyter or VS Code.
3. Run each section step-by-step for data preprocessing, modeling, and evaluation.

## 📌 Notes

- The training file is excluded because it exceeds GitHub's 100MB limit.
- This repo focuses on end-to-end model building with detailed documentation inside the notebook.


