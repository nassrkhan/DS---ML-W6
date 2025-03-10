# Breast Cancer Classification using Caret in R

This project demonstrates a complete workflow for applying machine learning algorithms to a breast cancer dataset using the Caret package in R. It includes data preprocessing, model training, evaluation, cross-validation, and synthetic data generation using SMOTE to handle class imbalance.

## 📊 Dataset

The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Data Set**, available on [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

## 🚀 Features

- Data preprocessing and partitioning (70% training, 30% testing)
- Machine learning models using:
  - K-Nearest Neighbors (K-NN)
  - Support Vector Machines (SVM)
- Evaluation using confusion matrix and accuracy metrics
- 10-fold cross-validation for model reliability
- Handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)
- Generating synthetic datasets for balanced training

## 🛠️ Tools & Packages

- **R** programming language
- `caret` package for machine learning
- `smotefamily` package for synthetic data generation
- `ggplot2` and `lattice` for visualization (optional)


## ✅ How to Run

1. **Install required packages:**
```r
install.packages("caret")
install.packages("smotefamily")
install.packages("ggplot2")
install.packages("lattice")


