# Gold Price Prediction using Random Forest Regression

## Overview
Gold Price Prediction is a machine learning project aimed at forecasting the price of gold based on historical data. The project utilizes a Random Forest Regression algorithm to make predictions. The dataset used in this project is sourced from Kaggle, comprising 2290 rows and 6 columns, including date and various financial indicators such as S&P 500 index, gold price, oil price, silver price, and EUR/USD exchange rate.

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
3. **Model Training:** Random Forest Regressor algorithm was chosen for training the model, utilizing historical data to learn patterns and relationships between various financial indicators and gold prices.
4. **Model Testing:** The trained model was evaluated using testing data to assess its accuracy in predicting gold prices.

## Algorithm
Random Forest Regressor was selected as the algorithm of choice due to its capability to handle non-linear relationships and ensemble learning, which often leads to robust predictions in regression tasks.

## Goal
The primary objective of this project is to predict the price of gold for the current date by leveraging historical records of financial indicators. By employing machine learning techniques, the project aims to provide valuable insights for investors and stakeholders in the gold market.

## Conclusion
Gold Price Prediction using Random Forest Regression offers a promising approach to forecast gold prices based on historical trends and related financial indicators. By harnessing the power of machine learning, this project contributes to enhancing decision-making processes in the gold market, enabling stakeholders to make informed investment decisions.
