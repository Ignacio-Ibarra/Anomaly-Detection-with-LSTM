# Anomaly Detection with LSTM   

Detection of anomalous values in a time series of the LULU stock price on Nasdaq. I first fit a univariate multi-step LSTM model to predict prices for the next 30 days, and then, based on the 3-day moving average error, detect threshold-based anomaly points.