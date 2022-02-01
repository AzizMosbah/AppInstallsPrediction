# Installs Forecasting for a large App on the AppStore
This project is meant to compare time series forecasting models on app installs which is a high variance variable. 
Signal is inherently difficult to detect in such time series but we will see that our models do achieve some kind of pattern detection.
The training is done on two years worth of data and the evaluation is done on 3 months

#### -- Project Status: Completed
* We have implemented a naive benchmark model that achieves **15.83% Mean Absolute Percentage Error**
* Facebook prophet, a "plug and play" model widely used everywhere in industry, does slightly better than the naive benchmark with **13.53% MAPE**
* An LSTM neural network on I performed hyperparameter tuning using grid-search is the best solution by far with **10.77% MAPE
**
### Methods Used for forecasting

* Facebook Prophet
* LSTM Recurrent Neural Network



### Technologies

* Python
