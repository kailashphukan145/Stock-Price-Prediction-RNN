# Stock-Price-Prediction-RNN
LSTM RNN model for predicting HDFC Bank stock prices using historical data from Yahoo Finance. Built with TensorFlow &amp; Keras. Includes data preprocessing, training, visualization, and real-time prediction.
# HDFC Bank Stock Price Prediction using LSTM (RNN)

This project demonstrates how to build an LSTM-based Recurrent Neural Network (RNN) to predict stock prices for **HDFC Bank** using historical data from **Yahoo Finance**.

# Project Overview

- Collects historical stock price data (`HDFCBANK.NS`) from Yahoo Finance.
- Preprocesses data using MinMax scaling.
- Creates time-series datasets for model training.
- Builds and trains an LSTM neural network using TensorFlow / Keras.
- Evaluates and visualizes the model’s performance.
- Performs real-time next-day price prediction using the latest 60 days of data.

# Libraries

- Python
- Jupyter Notebook / Google Colab
- TensorFlow / Keras
- Pandas
- Numpy
- Matplotlib
- yfinance (Yahoo Finance API)

# Model Architecture

- Two LSTM layers with 50 units each
- Dense output layer
- Optimizer: Adam
- Loss Function: Mean Squared Error (MSE)
- 10 training epochs

# Results

- Visualized actual vs. predicted stock prices
- Real-time next closing price prediction
- Final example:  
  `Predicted Next Closing Price: ₹1905.38`
