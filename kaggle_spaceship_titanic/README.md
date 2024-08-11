# Spaceship Titanic Classification Project

This project is based on the [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic/rules) competition hosted on Kaggle. The goal is to predict which passengers were transported to an alternate dimension using various classification techniques.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Problem and Data Description](#problem-and-data-description)
3. [Data Preprocessing & Exploratory Data Analysis](#data-preprocessing--exploratory-data-analysis)
4. [Algorithm and Methodology](#algorithm-and-methodology)
5. [Experiments and Results](#experiments-and-results)
6. [Summary and Conclusions](#summary-and-conclusions)
7. [License](#license)

## Project Overview

The Spaceship Titanic dataset contains information about passengers on an interstellar spaceship. Our task is to build a model to predict whether a passenger was transported to another dimension. This project serves as a learning opportunity to apply various classification algorithms and explore feature engineering techniques.

## Problem and Data Description

- **Objective:** Predict the classification of passengers as to whether they were transported to another dimension.
- **Training Set:** 8,693 entries with 14 attributes.
- **Test Set:** 4,277 entries with 13 attributes (excluding the target variable).

### Key Attributes

- **Numerical Attributes:** Room Service, Food Court, Shopping Mall, Spa, VR Deck (monetary attributes), Age.
- **Categorical Attributes:** Home Planet, CryoSleep, Cabin, Destination, VIP.

## Data Preprocessing & Exploratory Data Analysis

### Handling Missing Values

- **Numerical Attributes:** Filled missing values with the median or mean.
- **Categorical Attributes:** Used mode for missing values.

### Exploratory Data Analysis

- Balanced target variable: 49.5% False, 50.4% True.
- Key insights:
  - Passengers from Europa were mostly transported.
  - CryoSleep significantly increased the chance of being transported.
  - VIP status had a lower chance of being transported.

## Algorithm and Methodology

Several classification algorithms were used, including:

- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**
- **Naive Bayes**
- **Decision Tree**
- **Random Forest**
- **Extreme Gradient Boosting (XGBoost)**
- **Light Gradient Boosting Machine (LGBM)**
- **Neural Network Multi-layer Perceptron (NNMLP)**

Principal Component Analysis (PCA) was conducted to reduce dimensionality, preserving 56.37% of the variance with three components.

## Experiments and Results

- **Model Performance:** Evaluated using cross-validation accuracy.
- **Best Model:** Light Gradient Boosting Machine with an accuracy of 79.32%.
- **Leaderboard Rank:** Achieved a rank of 1118 out of 1866 teams on Kaggle.

### Model Accuracy (After K-Fold Validation)

| Model                  | Accuracy (%) |
|------------------------|--------------|
| LightGBM               | 79.32        |
| XGBoost                | 78.91        |
| Random Forest          | 78.89        |
| Gradient Boost         | 78.89        |
| Logistic Regression    | 78.68        |
| Neural Network (MLP)   | 77.37        |
| K-Nearest Neighbors    | 76.10        |
| Decision Tree          | 75.00        |
| Naive Bayes            | 69.60        |

## Summary and Conclusions

This project successfully applied a range of classification techniques to predict passenger outcomes on the Spaceship Titanic. The Light Gradient Boosting Machine was the most effective model, achieving a significant accuracy improvement. Future enhancements could include hyperparameter tuning and additional feature engineering.
