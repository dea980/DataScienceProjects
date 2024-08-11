# Data Science Projects

This repository contains two data science projects focusing on predictive modeling using machine learning techniques. Each project involves data preprocessing, exploratory data analysis, and the application of various machine-learning algorithms to solve a specific problem.

## Table of Contents

1. [House Price Prediction](#house-price-prediction)
2. [Spaceship Titanic Classification](#spaceship-titanic-classification)

## House Price Prediction

### Overview

This project is based on the [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview) competition on Kaggle. The aim is to predict the final sale prices of residential homes in Ames, Iowa, using a dataset with 79 features.

### Problem and Data Description

- **Objective:** Predict the sale prices of houses.
- **Training Set:** 1,460 entries with 81 columns.
- **Test Set:** 1,459 entries with 80 columns.

### Data Preprocessing & Exploratory Data Analysis

- **Handling Missing Values:** Focused on columns with high correlation to `Sale Price`.
- **Exploratory Data Analysis:** Used scatter plots and distribution plots to understand relationships and data characteristics.

### Algorithm and Methodology

Applied regression models including:

- Linear Regression
- Random Forest Regressor
- Support Vector Regressor
- Gradient Boosting Regressor
- Decision Tree Regressor
- Bayesian Ridge Regression
- Lasso Regression
- Multi-layer Perceptron (MLP)
- K-Nearest Neighbors (KNN)

### Experiments and Results

- **Best Model:** Gradient Boosting Regressor with an accuracy of 84.29%.
- **Leaderboard Rank:** Positioned at 2474 out of 4130 teams on Kaggle.

### Summary and Conclusions

This project demonstrated the effectiveness of advanced regression techniques in predicting house prices. The Gradient Boosting Regressor performed the best, and further improvements can be made through hyperparameter tuning and additional feature engineering.

---

## Spaceship Titanic Classification

### Overview

This project is based on the [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic/rules) competition hosted on Kaggle. The task is to classify passengers as either transported to another dimension or not, using a variety of classification algorithms.

### Problem and Data Description

- **Objective:** Predict passenger transportation status.
- **Training Set:** 8,693 entries with 14 attributes.
- **Test Set:** 4,277 entries with 13 attributes.

### Data Preprocessing & Exploratory Data Analysis

- **Handling Missing Values:** Used median, mean, or mode based on attribute distribution.
- **Exploratory Data Analysis:** Identified key features such as CryoSleep and Home Planet affecting transportation.

### Algorithm and Methodology

Implemented classification models including:

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest
- Extreme Gradient Boosting (XGBoost)
- Light Gradient Boosting Machine (LGBM)
- Neural Network Multi-layer Perceptron (NNMLP)

### Experiments and Results

- **Best Model:** Light Gradient Boosting Machine with an accuracy of 79.32%.
- **Leaderboard Rank:** Achieved a rank of 1118 out of 1866 teams on Kaggle.

### Summary and Conclusions

The project successfully utilized machine learning algorithms to classify passengers on the Spaceship Titanic. The Light Gradient Boosting Machine was the top performer, and future work could focus on model tuning and additional feature exploration.


