# ITC-Stock-Prediction
Stock prediction using LSTM for International Tobacco Company
# Stock Price Predictor (Time Series - LSTM)

## Overview

This project predicts stock prices using historical data with a time series deep learning model (LSTM). It captures sequential patterns to forecast future prices.

## Features

* Time series forecasting using LSTM
* Data normalization with MinMaxScaler
* Visualization of actual vs predicted prices
* Next-day stock price prediction

## Tech Stack

* Python
* TensorFlow / Keras
* Pandas, NumPy
* Matplotlib
* yFinance

## Dataset

Stock data is fetched using yFinance (e.g., Apple stock - AAPL).

## Model

* LSTM (Long Short-Term Memory)
* Input: Past 60 days stock prices
* Output: Next day price

## Results

* Model learns trends effectively
* Produces close approximation to real stock prices

## How to Run

1. Install dependencies:
   pip install yfinance tensorflow
2. Run the notebook in Google Colab
3. Execute all cells sequentially

## Output

* Graph comparing actual vs predicted prices
* Predicted next-day stock price

## Future Improvements

* Use advanced models like GRU or Transformer
* Add multiple stock features (Open, High, Volume)
* Hyperparameter tuning

