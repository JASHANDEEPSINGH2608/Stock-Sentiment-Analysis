# Stock-Sentiment-Analysis

This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices based on historical data from Yahoo Finance. The model is built using Python, TensorFlow, and Keras, and is designed to predict the closing price of Apple's stock.

# Features #
Data Retrieval: Historical stock data is retrieved from Yahoo Finance using the yfinance library.
Data Preprocessing: The data is scaled using MinMaxScaler, and a window of the last 60 days is used to train the model.
Model Architecture: The model is built using two LSTM layers followed by Dense layers.
Training and Testing: The data is split into training and testing datasets, and the model is trained to minimize mean squared error.
Prediction: The model predicts future stock prices and the results are visualized using Matplotlib.

# Methodology #
Data Collection: Historical stock data for Apple (AAPL) is downloaded from Yahoo Finance.
Data Preprocessing: The closing prices are scaled, and a sliding window of 60 days is used to create training and testing datasets.
Model Building: An LSTM-based model is constructed using Keras, with two LSTM layers and two Dense layers.
Model Training: The model is trained on 80% of the data, with a batch size of 1 and 1 epoch.
Prediction and Evaluation: The model is used to predict the stock prices on the test data. The root mean squared error (RMSE) is calculated to evaluate the model's performance.
Visualization: The predicted and actual prices are plotted for visual comparison.

# Input File #
The input data is retrieved automatically from Yahoo Finance. The dataset used includes historical data for Apple (AAPL) from January 1, 2012, to December 17, 2023. No manual input file is required, but you can modify the ticker symbol and date range in the script to fetch data for different stocks or time periods.
# Usage #
Download the .ipynb file from the repositry and run on Jupyter Notebook
# Results #
The model predicts future stock prices based on historical data, with the predictions and actual prices visualized in a graph. The root mean squared error (RMSE) of the predictions is also calculated and displayed.
