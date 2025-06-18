# 📊 Santander Value Prediction Challenge

This project is a solution for the [Santander Value Prediction Challenge](https://www.kaggle.com/competitions/santander-value-prediction-challenge), a regression task hosted on Kaggle. The goal of the competition is to predict a continuous value (`target`) using anonymized features provided by Santander Bank.

## 🚀 Project Overview

Financial institutions use machine learning models to estimate the value of potential transactions. In this challenge, we aim to model these values based on 499 anonymized numerical features (`var_0` to `var_498`), using advanced regression techniques.

This repository includes:

- Full data preprocessing pipeline  
- Feature selection and dimensionality reduction  
- Model training using LightGBM  
- Evaluation using RMSLE metric  
- Feature importance analysis  
- Final submission preparation for Kaggle  

## 📁 Files

- `value-prediction-model.ipynb`: Jupyter Notebook containing full data pipeline, modeling, and evaluation  
- `README.md`: Project overview and setup instructions  

## 🧠 Machine Learning Techniques Used

- **Data Preprocessing**: Null imputation, standardization  
- **Feature Engineering**: Variance thresholding  
- **Modeling**: LightGBM Regressor with hyperparameter tuning  
- **Evaluation Metric**: Root Mean Squared Log Error (RMSLE)  
- **Submission**: CSV formatted predictions for Kaggle submission  

## 📈 Evaluation Metric

The primary metric used is **RMSLE** (Root Mean Squared Logarithmic Error):

