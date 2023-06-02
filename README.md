# Dental Claim Data Analysis

This repository contains code for analyzing dental claim data. The data is processed and visualized using various techniques, and machine learning models are trained to predict the amount paid after coordination of benefits (COB) for dental claims.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [EDA](#eda)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

In this project, we aim to analyze dental claim data to understand the factors that influence the amount paid after COB. We perform exploratory data analysis (EDA) to gain insights into the data, preprocess the data for modeling, and train several regression models to predict the payment amount. The models used include Support Vector Regression (SVR), XGBoost, and Decision Tree.

## Installation

To run this code, you need to have the following dependencies installed:

- Python 3
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- xgboost
- seaborn
- matplotlib

## Data

The dental claim data is stored in the `dental_claim_data.xlsx` file. It consists of two sheets: `summary` and `data`. The `data` sheet contains the actual dental claim data with various features, including the amount paid after COB. The `summary` sheet provides an overview of the data.

## EDA

The EDA section explores the data by visualizing the distributions of variables, checking for missing values, detecting outliers, and analyzing correlations between variables. Various plots and statistical summaries are used to gain insights into the data.

## Feature Engineering

Before training the regression models, the data is preprocessed and prepared for modeling. This includes handling missing values, encoding categorical variables, standardizing numerical variables, and performing dimensionality reduction using Principal Component Analysis (PCA).

## Modeling

Three regression models are trained to predict the amount paid after COB: Support Vector Regression (SVR), XGBoost, and Decision Tree. The models are evaluated using mean squared error (MSE) and R-squared score. Hyperparameter tuning is performed using grid search to optimize the models.

## Results

The performance of the regression models is compared based on MSE and R-squared score. The XGBoost model achieves the best performance with the lowest MSE and highest R-squared score. The Decision Tree model also performs well, while the SVR model shows the poorest performance.

## Conclusion

In conclusion, the XGBoost and Decision Tree models provide accurate predictions for the amount paid after COB in dental claims. The models can be used to assist in claim processing and decision-making. Further improvements can be made by collecting additional data and fine-tuning the models.
