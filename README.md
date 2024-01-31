# House Price Prediction Project
## Overview
This machine learning project aims to predict house prices based on a variety of features such as the size of the house, location, number of bedrooms, etc. By leveraging historical house price data, this project utilizes several regression models to estimate the market value of houses. This tool is intended for real estate agents, property investors, and individuals looking to buy or sell properties with an informed understanding of the market.

## Features
- **Data Preprocessing:** Cleansing and preparing the dataset for training, including handling missing values, feature encoding, and normalization.
- **Exploratory Data Analysis (EDA):** Visualizing data distributions, correlations, and trends to understand the factors influencing house prices.
- **Model Selection:** Comparing various regression models, including Linear Regression, Decision Trees, Random Forest, and Gradient Boosting, to select the best performer.
- **Model Evaluation:** Utilizing metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared to evaluate model performance.
- **Feature Importance Analysis:** Identifying and analyzing the most significant features affecting house prices.
- **Predictive Interface:** A simple web or command-line interface for making predictions with the trained model.

## Dataset
The dataset used for this project is the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques), which contains detailed information about residential property sales in Ames, Iowa. This dataset includes 79 explanatory variables describing various aspects of residential homes.

## Results
| Model | Accuracy | 
|----------|----------|
|GradientBoosting  |  90.850%|
|LinearRegression  |  89.952%|
|RandomForest      | 88.793%|
|DecisionTree      | 76.80%|
