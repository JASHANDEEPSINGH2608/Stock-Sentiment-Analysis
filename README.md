# Stock-Sentiment-Analysis

This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices based on historical data from Yahoo Finance. The model is built using Python, TensorFlow, and Keras, and is designed to predict the closing price of Apple's stock.

# Features #
Data Retrieval: Historical stock data is retrieved from Yahoo Finance using the yfinance library.
Data Preprocessing: The data is scaled using MinMaxScaler, and a window of the last 60 days is used to train the model.
Model Architecture: The model is built using two LSTM layers followed by Dense layers.
Training and Testing: The data is split into training and testing datasets, and the model is trained to minimize mean squared error.
Prediction: The model predicts future stock prices and the results are visualized using Matplotlib.

## **Methodology**
<img src="https://user-images.githubusercontent.com/7460892/207003643-e03c8964-3f16-4a62-9a2d-b1eec5d8691f.png" width="80%" height="80%">

# Input File #
The input data is retrieved automatically from Yahoo Finance. The dataset used includes historical data for Apple (AAPL) from January 1, 2012, to December 17, 2023. No manual input file is required, but you can modify the ticker symbol and date range in the script to fetch data for different stocks or time periods.
# Usage #
Download the .ipynb file from the repositry and run on Jupyter Notebook
# Results #
The model predicts future stock prices based on historical data, with the predictions and actual prices visualized in a graph. The root mean squared error (RMSE) of the predictions is also calculated and displayed.
