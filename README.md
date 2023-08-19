# Stock Price Prediction Project

Objective

Take a stock price dataset and build a machine learning model to predict future stock price movements. The key steps include:

1) Feature Engineering: Generate technical indicators like RSI, MACD, Bollinger Bands etc. from the price data to use as model features.


2)Data Visualization: Create visualizations like candlestick charts, volume charts, overlaying technical indicators to understand price behavior.


3)ML Modeling: Try different models like ARIMA, LSTM, XGBoost. Evaluate and compare performance to select the best model.


4)Train-Test Split: Split sequential data maintaining time order without shuffling. Use 70-30 or 80-20 split.


5)Model Evaluation: Assess model accuracy on test set using RMSE, MAPE and visualize actual vs predicted prices.


6)Results Summary: Compare evaluation metrics across models. Discuss model strengths, weaknesses and insights gained.


Data
The stock price dataset used is "/kaggle/input/sandp500/all_stocks_5yr.csv". It contains daily open, high, low, close prices and volume for stocks from the S&P 500 index over 5 years.

Implementation
The project is implemented in Python using libraries like Pandas, Matplotlib, Sklearn, Keras, XGBoost. The source code can be found in the src folder.
