# Golden Insights: Forecasting Gold Prices with Machine Learning

## Overview
Gold Price Prediction is a machine learning project aimed at forecasting the price of gold based on historical data. The project utilizes various regression algorithms, including Linear Regression, Decision Tree Regressor, and Random Forest Regressor, to make predictions. The dataset used in this project is sourced from Kaggle, comprising 2290 rows and 6 columns, including date and various financial indicators such as S&P 500 index, gold price, oil price, silver price, and EUR/USD exchange rate.

## Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data/data)
- **Size:** 2290 rows x 6 columns
- **Columns:**
  - **Date:** Date in MM/dd/yyyy format
  - **SPX:** S&P 500 index - A stock market index tracking the performance of 500 large companies listed on US stock exchanges
  - **GLD:** Gold price
  - **USO:** The United States Oil Fund LP (USO) - An exchange-traded security reflecting the price movements of crude oil
  - **SLV:** Silver price
  - **EUR/USD:** Euro to US dollar exchange rate

## Methodology
1. **Data Collection:** The dataset was obtained from Kaggle, providing historical financial data including gold prices.
2. **Data Cleaning:** Preprocessing steps were applied to handle missing values, outliers, and ensure data compatibility for training the model.
3. **Model Training:** Multiple regression algorithms were chosen for training the model, including Linear Regression, Decision Tree Regressor, and Random Forest Regressor. These algorithms utilize historical data to learn patterns and relationships between various financial indicators and gold prices.
4. **Model Testing:** The trained models were evaluated using testing data to assess their accuracy in predicting gold prices.

## Algorithms
- **Linear Regression:** This algorithm fits a linear model to the relationship between the independent variables (financial indicators) and the dependent variable (gold price). It assumes a linear relationship between the variables.
- **Decision Tree Regressor:** This algorithm builds a decision tree to predict the value of the target variable based on several input variables. It can handle both numerical and categorical data.
- **Random Forest Regressor:** This algorithm builds multiple decision trees and merges their predictions to improve accuracy and prevent overfitting. It's suitable for handling non-linear relationships and ensemble learning.

## Goal
The primary objective of this project is to predict the price of gold for the current date by leveraging historical records of financial indicators. By employing various regression algorithms, the project aims to provide valuable insights for investors and stakeholders in the gold market.

## Conclusion
Gold Price Prediction using regression algorithms offers a promising approach to forecast gold prices based on historical trends and related financial indicators. By harnessing the power of machine learning, this project contributes to enhancing decision-making processes in the gold market, enabling stakeholders to make informed investment decisions. Based on the evaluation, Linear Regression has shown higher accuracy among the three models, making it the preferred choice for final predictions.
