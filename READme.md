# Project Overview 
The objective of this project is to develop a model to forecast volatility using time series data. The project involves preprocessing the data to make it suitable for modeling by making it stationary, and then applying an MLP (Multi-Layer Perceptron) model to forecast the volatility.  

# Dataset Description
The S&P 500 market stock dataset is a collection of historical stock prices for all companies currently listed on the S&P 500 index over the past five years. The dataset provides investors and analysts with a rich source of financial data to analyze and make informed investment decisions. It includes detailed information on each company's stock prices, such as the opening and closing prices, the daily high and low prices, and the trading volumes. The dataset is well-structured and covers a wide array of companies, making it a valuable resource for anyone interested in financial analysis and prediction.  

#  Analysis and transforms

* Time series decomposition
  * Level
  * Trend
  * Seasonality 
  * Noise
  
* Stationarity
  * AC and PAC plots
  * Rolling mean and std
  * Dickey-Fuller test
  
* Making our time series stationary
  * Difference transform
  * Log scale
  * Smoothing
  * Moving average



#  Forcasting with MLP
Based on the results, the model performs reasonably well in predicting the target variable. The low MAE and RMSE values indicate that the model's predictions are generally close to the actual values. The MSE value is also reasonable, although it is higher than the other metrics.

Overall, the model can be considered as a good starting point, but further improvement could be achieved by tuning the hyperparameters or trying out different models.