# 📊 Statistical Machine Learning Project

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Supervised%20%26%20Unsupervised-orange?style=for-the-badge)
![University](https://img.shields.io/badge/University%20of%20Milan-Course%20Project-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📖 Overview

This repository contains the final project developed for the **Statistical Machine Learning** course.

The project explores both **Supervised Learning** and **Unsupervised Learning** using two real-world datasets.

The complete workflow includes:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training
- Model comparison
- Performance evaluation
- Result interpretation

---

# 🎯 Objectives

## Supervised Learning

Predict whether an individual's annual income exceeds **$50K** using demographic and employment-related variables.

Algorithms compared:

- Logistic Regression
- Random Forest

---

## Unsupervised Learning

Perform customer segmentation using purchasing behavior extracted from the **Online Retail** dataset.

Algorithms compared:

- K-Means Clustering
- Hierarchical Clustering

---

# 📂 Datasets

## Adult Income Dataset

- Source: UCI Machine Learning Repository
- Type: Classification
- Target: Income (>50K / ≤50K)

---

## Online Retail Dataset

- Source: UCI Machine Learning Repository
- Type: Customer Segmentation

---

# 🤖 Machine Learning Pipeline

## Supervised Learning

- Data Cleaning
- Missing Value Handling
- Feature Encoding
- Train/Test Split
- Logistic Regression
- Random Forest
- Model Evaluation

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve
- AUC
- Confusion Matrix

---

## Unsupervised Learning

- Data Cleaning
- Customer Feature Engineering (RFM-style variables)
- Data Standardization
- Optimal Number of Clusters
- K-Means
- Hierarchical Clustering

### Evaluation Metrics

- Elbow Method
- Silhouette Analysis
- Dendrogram
- Cluster Visualization

---

# 📁 Repository Structure

```
Statistical-Machine-Learning-Project
│
├── code
│   ├── supervised_learning.Rmd
│   └── unsupervised_learning.Rmd
│
├── datasets
│   ├── adult.csv
│   └── OnlineRetail.xlsx
│
├── reports
│   ├── report_supervised.pdf
│   └── report_unsupervised.pdf
│
├── presentation
│   └── presentation statistical_learning.pdf
│
├── images
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🛠 Technologies

- R
- RStudio
- R Markdown
- tidyverse
- dplyr
- ggplot2
- caret
- randomForest
- cluster
- factoextra

---

# 📈 Results

## Supervised Learning

The supervised analysis compares the predictive performance of Logistic Regression and Random Forest using multiple evaluation metrics.

Performance was assessed using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve
- AUC
- Confusion Matrix

---

## Unsupervised Learning

The clustering analysis identifies customer groups with similar purchasing behaviors.

The project compares K-Means and Hierarchical Clustering using:

- Elbow Method
- Silhouette Score
- Dendrogram
- Cluster Visualization

---

# 📄 Included Files

- ✅ Complete R Markdown source code
- ✅ Original datasets
- ✅ Final reports (PDF)
- ✅ Final presentation

---

# 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/sami-hnaien/Statistical-Machine-Learning-Project.git
```

Open the project in **RStudio**.

Install the required packages if necessary.

Run all code chunks in the `.Rmd` files.

---

# 👨‍💻 Author

**Sami Hnaien**

Master's Student

**Data Science for Economics and Health**

University of Milan

---

## ⭐ Project Highlights

- Supervised Machine Learning
- Unsupervised Machine Learning
- Classification
- Customer Segmentation
- Statistical Learning
- Data Visualization
- Model Evaluation
- R Programming