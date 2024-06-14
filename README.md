# goldmansachsstockprediction

## Overview

This project aims to predict the stock price of Goldman Sachs using various regression machine learning models. The models employed include Multiple Linear Regression, Gradient Boosting Regression, eXtreme Gradient Boosting (XGBoost), CatBoost Regression, Light Gradient Boosting (LGBM), Bayesian Optimization for Hyperparameter Tuning, and TPOT Regression.

## Dataset

The dataset used for this project includes the following features:
  - **Date**: The date of the observation.
  - **Open**: Opening price of the stock.
  - **High**: Highest price of the stock during the trading day.
  - **Low**: Lowest price of the stock during the trading day.
  - **Close**: Closing price of the stock.
  - **Adj Close**: Adjusted closing price of the stock.
  - **Volume**: The trading volume of the stock.

## Workflow

### Importing Libraries

Imported necessary libraries for data manipulation and model building.

Before running the code, make sure to install the required packages by executing the following commands:

###### pip install numpy pandas matplotlib seaborn scikit-learn

### Data Preprocessing and Visualization

Conducted data preprocessing and visualization, including:
  - Handling missing values by imputing them.
  - Updating the date column into day, month, and year.
  - Exploring the dataset through various plots to understand the relationships between features and the target variable.

### Scaling

Scaled the data to ensure uniformity in feature scales using MinMax Scaler.

### Model Training and Evaluation

 Trained the following regression models:
 
  - Multiple Linear Regression
  - Gradient Boosting Regression
  - eXtreme Gradient Boosting (XGBoost)
  - CatBoost Regression
  - Light Gradient Boosting (LGBM)
  - Bayesian Optimization for Hyperparameter Tuning
  - TPOT Regression
    
Evaluated model performance using metrics such as R2 score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), Maximum Error, and Mean Squared Error (MSE).

## Conclusion

This project demonstrates the application of various regression machine learning models to predict the stock price of Goldman Sachs. By evaluating different models and techniques, we aim to provide insights into the factors influencing the stock price and improve predictive accuracy.

  
