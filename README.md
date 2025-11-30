
# Heart Disease Classification – End-to-End Machine Learning Project

This project implements a complete machine learning workflow to predict heart disease using clinical patient data. It covers data exploration, preprocessing, feature engineering, model training, evaluation, and hyperparameter tuning to compare multiple classifiers and select the best-performing model.

---

## Overview

The goal of the project is to build a predictive model that determines whether a patient is likely to have heart disease based on medical attributes such as age, sex, chest pain type, resting blood pressure, cholesterol level, maximum heart rate, ST depression, and more.

The full workflow includes:

1. Data loading and inspection
2. Exploratory data analysis (EDA) and visualization
3. Preprocessing and feature preparation
4. Training multiple machine learning models
5. Model evaluation and comparison
6. Hyperparameter tuning
7. Final model selection

---

## Features

### Exploratory Data Analysis

* Summary statistics
* Class distribution
* Correlation matrix and heatmap
* Visualizations of key medical features
* Relationship analysis between features and disease presence

### Preprocessing

* Cleaning and preparing feature sets
* Encoding categorical variables
* Train/test split
* Scaling numerical features

### Models Implemented

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest Classifier

### Evaluation Metrics

* Accuracy
* Precision, Recall, F1-score
* Confusion matrix
* Cross-validation
* Best model comparison

### Hyperparameter Tuning

* Optimal K search for KNN
* RandomizedSearchCV for Random Forest
* Comparison between default and tuned models

---

## Repository Structure

```
heart-disease-classification/
│
├── notebooks/
│   └── heart-disease-classification.ipynb
│
├── data/
│   └── heart.csv      # optional (may be excluded)
│
├── reports/
│   └── heart-disease.pdf   # full documentation with plots and results
│
├── results/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── metrics_summary.txt
│
├── requirements.txt
│
└── README.md
```

---

## Dataset

This project uses the **UCI Heart Disease Dataset (Cleveland subset)**, available from:

* UCI Machine Learning Repository
* Kaggle mirror versions

Because of dataset licensing restrictions, the CSV file may not be uploaded directly. Place the dataset inside the `/data` folder before running the notebook.

---

## How to Run

1. Install the required packages:

```
pip install -r requirements.txt
```

2. Place the dataset as:

```
data/heart.csv
```

3. Launch the notebook:

```
jupyter notebook notebooks/heart-disease-classification.ipynb
```

4. Run all cells sequentially to reproduce results.

---

## Summary

This project demonstrates an end-to-end supervised machine learning workflow applied to a real medical dataset. It includes EDA, preprocessing, model development, evaluation, and hyperparameter optimization to produce a reliable heart disease prediction model. The included PDF report documents all findings, visualizations, and model comparisons.

---



Just tell me.
