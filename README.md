# 💳Credit Card Fraud Detection using Machine Learning

## Project Overview

Credit card fraud is a major financial threat affecting banks and customers worldwide. This project uses machine learning techniques to identify fraudulent transactions based on transaction patterns.

The model analyzes anonymized credit card transaction data and predicts whether a transaction is **fraudulent or legitimate**.

This project demonstrates skills in **data preprocessing, exploratory data analysis (EDA), machine learning modeling, and evaluation**.

## 📊 Dataset

The dataset used in this project is the **Credit Card Fraud Detection Dataset** available on Kaggle.

Dataset Source:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Features

* **284,807 transactions**
* **31 columns**
* Features **V1–V28** are anonymized using PCA
* `Time` – seconds elapsed between transactions
* `Amount` – transaction amount
* `Class` – target variable

  * 0 → Normal transaction
  * 1 → Fraudulent transaction

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Data Loading
2. Data Exploration & Analysis
3. Data Cleaning
4. Handling Class Imbalance
5. Feature Scaling
6. Machine Learning Model Training
7. Model Evaluation

## Machine Learning Models

The following algorithms can be used in fraud detection:

* Logistic Regression
* Random Forest
* Decision Tree
* Support Vector Machine

Models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Exploratory Data Analysis

EDA helps understand:

* Class imbalance
* Transaction distribution
* Fraud patterns
* Feature relationships

Visualizations include:

* Transaction distribution plots
* Fraud vs Non-fraud comparison
* Correlation heatmap

## Project Objective

The objective of this project is to build a machine learning model capable of detecting fraudulent credit card transactions with high accuracy while minimizing false positives.

## Future Improvements

* Hyperparameter tuning
* Deep learning models
* Real-time fraud detection systems
* Deployment using Streamlit
