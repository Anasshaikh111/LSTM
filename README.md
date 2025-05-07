# LSTM
LSTM Time Series Forecasting with TensorFlow &amp; Python

This project demonstrates how to use an LSTM (Long Short-Term Memory) model built with TensorFlow to predict stock prices using historical Microsoft stock data.

Model Architecture
The LSTM model consists of the following 5 layers:

LSTM (64 units, return_sequences=True) – Processes input sequences

LSTM (64 units) – Outputs the last hidden state

Dense (128 units, ReLU) – Learns complex patterns

Dropout (0.5) – Prevents overfitting

Dense (1 unit) – Outputs the predicted stock price

Data Processing
Used historical Microsoft stock prices

Normalized data using StandardScaler

Created a 60-day sliding window for time-series input

Split into training and test datasets (95% training)

Visualized actual vs predicted prices using Matplotlib


Technologies Used
Python

TensorFlow / Keras

Pandas / NumPy

Matplotlib / Seaborn

Scikit-learn

Tags
LSTM, TensorFlow, Deep Learning, Time Series, Stock Prediction, Python

