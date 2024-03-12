# Crude-Oil-Price-Prediction
This repository contains code for analyzing and predicting crude oil prices using various time-series forecasting methods. The analysis covers the period from 2013 to 2022, with a focus on training models to forecast prices accurately.


**Data**

The dataset used in this analysis is sourced from a CSV file named data.csv. It contains historical crude oil price data at monthly intervals.


**Analysis Steps**

1. Data Exploration and Visualization
- The initial step involves loading the data and visualizing the crude oil price time-series from 2013 to 2022 using ggplot2.

2. Partitioning Data
- The dataset is partitioned into two parts: a training set (from 2013 to 2020) and a validation set (from 2021 to 2022).

3. Regression Models
Two regression models are implemented:
- Trend & Season Linear Regression Model
- Trend Linear Regression Model

These models aim to capture the trend and seasonality in crude oil prices.

4. Naive Forecasting
Two naive forecasting models are implemented:
- Naive Forecast
- Seasonal Naive Forecast

These models provide simple baseline forecasts for comparison.

5. ARIMA & Exponential Smoothing
- Autoregressive Integrated Moving Average (ARIMA) and Exponential Smoothing models are implemented for time-series forecasting.

These models capture the underlying patterns and seasonality in the data.


**Results**
- Each forecasting method is evaluated based on its accuracy in predicting crude oil prices for the validation period (2021-2022).
- The accuracy metrics include Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), etc.


**Repository Structure**
- data.csv: Dataset containing historical crude oil prices.
- crude_oil_price_prediction.R: R script containing code for data preprocessing, model training, and evaluation.
- README.md: This file providing an overview of the analysis and instructions for usage.


**Usage**
- Clone the repository to your local machine.
- Ensure you have R installed along with the required packages (forecast, ggplot2, gridExtra).
- Run the crude_oil_price_prediction.R script in RStudio or any R environment to execute the analysis.
- Review the generated plots and accuracy metrics to evaluate the performance of different forecasting methods.


Feel free to explore and modify the code as needed for your analysis.
