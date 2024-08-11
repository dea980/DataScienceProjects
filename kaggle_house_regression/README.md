# House Price Prediction Project

This project aims to predict house prices using the [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview) competition dataset from Kaggle. This dataset includes 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa, making it a rich resource for applying various machine-learning techniques.

## Table of Contents

1. [Problem and Data Description](#problem-and-data-description)
2. [Data Preprocessing & Exploratory Data Analysis](#data-preprocessing--exploratory-data-analysis)
3. [Algorithm and Methodology](#algorithm-and-methodology)
4. [Experiments and Results](#experiments-and-results)
5. [Summary and Conclusions](#summary-and-conclusions)

## Problem and Data Description

The objective of this project is to predict the sale prices of houses using the attributes provided in the dataset. The training set consists of 1,460 rows and 81 columns, while the test set consists of 1,459 rows and 80 columns. Key features include overall quality, neighborhood, year built, and gross living area. The goal is to identify features most correlated with sale prices and use them in regression models.

## Data Preprocessing & Exploratory Data Analysis

### Handling Missing Values

We focused on columns most correlated with sale prices, handling missing values only in these columns. Two attributes, `Garage Year Built` and `Masonry Veneer Area`, had missing values, which were filled using the mean and median, respectively.

### Exploratory Data Analysis

Scatter plots were used to analyze relationships between `Sale Price` and highly correlated features. For example:

- **Gross Living Area** showed a strong positive relationship with `Sale Price`.
- **Year Built** had a slight positive relationship.
- **Garage Area** showed a moderate positive relationship.
- **Overall Quality** demonstrated a strong positive relationship.

Distributions of various attributes were examined to understand their characteristics, such as skewness and variance.

## Algorithm and Methodology

Multiple regression models were applied to predict house prices:

- **Linear Regression**
- **Random Forest Regressor**
- **Support Vector Regressor**
- **Gradient Boosting Regressor**
- **Decision Tree Regressor**
- **Bayesian Ridge Regression**
- **Lasso Regression**
- **MLP Regressor**
- **KNN Regressor**

The Gradient Boosting Regressor showed the best performance, highlighting its popularity in the data science community.

## Experiments and Results

Each model's accuracy was evaluated, with the Gradient Boosting Regressor achieving an accuracy of approximately 84.29% during cross-validation. The Random Forest Regressor also performed well, achieving over 80% accuracy.

## Summary and Conclusions

This project successfully applied various regression techniques to predict house prices, with the Gradient Boosting Regressor yielding the best results. Future improvements could involve:

- Performing grid searches for hyperparameter tuning.
- Removing outliers.
- Exploring additional features beyond those highly correlated with `Sale Price`.

## Acknowledgments

The dataset was compiled by Dean De Cock for use in data science education. It is a modern alternative to the Boston Housing dataset and offers extensive opportunities for feature engineering and model testing.

