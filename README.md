# Statistical Machine Learning Project

## Overview

This project was developed as part of the **Statistical Machine Learning** course.

The objective is to compare different Machine Learning techniques for both **supervised** and **unsupervised** learning using two real-world datasets in R.

The project includes data preprocessing, exploratory analysis, model training, performance evaluation, and result interpretation.

---

## Project Objectives

### Supervised Learning

- Predict individual income using the Adult Income dataset.
- Compare the performance of two supervised classification algorithms.
- Evaluate models using standard classification metrics.

### Unsupervised Learning

- Segment customers using the Online Retail dataset.
- Compare two clustering algorithms.
- Identify meaningful customer groups based on purchasing behavior.

---

## Datasets

### 1. Adult Income Dataset

- Source: UCI Machine Learning Repository
- Task: Binary Classification
- Target Variable: Income (>50K / <=50K)

### 2. Online Retail Dataset

- Source: UCI Machine Learning Repository
- Task: Customer Segmentation

---

## Algorithms

### Supervised Learning

- Logistic Regression
- Random Forest

### Unsupervised Learning

- K-Means Clustering
- Hierarchical Clustering

---

## Evaluation Metrics

### Classification

- Accuracy
- Precision
- Recall
- F1-Score
- ROC Curve
- AUC
- Confusion Matrix

### Clustering

- Elbow Method
- Silhouette Score
- Dendrogram
- Cluster Visualization

---

## Project Structure

```
Statistical-Machine-Learning-Project/
│
├── code/
│   ├── supervised_learning.Rmd
│   └── unsupervised_learning.Rmd
│
├── datasets/
│   ├── adult.csv
│   └── OnlineRetail.xlsx
│
├── reports/
│   ├── report_supervised.pdf
│   └── report_unsupervised.pdf
│
├── presentation/
│   └── presentation statistical_learning.pdf
│
├── images/
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Technologies Used

- R
- R Markdown
- tidyverse
- caret
- randomForest
- cluster
- factoextra
- ggplot2
- dplyr

---

## Results

### Supervised Learning

The comparison shows the strengths and weaknesses of the selected classification algorithms based on predictive performance and model evaluation metrics.

### Unsupervised Learning

Customer segmentation identifies groups with different purchasing behaviors and compares the quality of K-Means and Hierarchical Clustering.

---

## Repository Contents

- Source code in R Markdown
- Datasets
- Final reports
- Presentation slides

---

## How to Run

1. Download or clone this repository.

```bash
git clone https://github.com/sami-hnaien/Statistical-Machine-Learning-Project.git
```

2. Open the `.Rmd` files in **RStudio**.

3. Install the required packages.

4. Run all code chunks to reproduce the analysis.

---

## Author

**Sami Hnaien**

Master's Student in Data Science for Economics and Health

University of Milan
