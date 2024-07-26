

# Forecasting model 

Time series forecasting involves predicting future values based on previously observed values. The examples in the [Jupyter notebook](https://github.com/BhadraNivedita/Forecasting-the-monthly-sales-with-LSTM/blob/main/TimeseriesForecasting_differentMethods.ipynb) shows popular methods starting from basic approaches to more sophisticated models. 


## Moving Average

A moving average model smooths out short-term fluctuations and highlights longer-term trends or cycles. It averages a fixed number of past observations.

## Exponential Smoothing

Exponential Smoothing assigns exponentially decreasing weights over time, giving more importance to recent observations.

## ARIMA (AutoRegressive Integrated Moving Average)

ARIMA combines Autoregression (AR), Integration (I), and Moving Average (MA) to model time series data. It's useful for non-stationary data.

## Prophet
Prophet, developed by Facebook, is designed for time series forecasting with strong seasonal effects and several seasons of historical data.


## LSTM Model

LSTM (Long Short-Term Memory) is a type of recurrent neural network (RNN) architecture designed to model sequences and their long-range dependencies more effectively than traditional RNNs. LSTMs are capable of learning long-term dependencies by incorporating memory cells and gates that control the flow of information. They are particularly useful for tasks where context over long sequences is important, such as time series forecasting, language modeling, and speech recognition.

## BiLSTM Model

BiLSTM (Bidirectional Long Short-Term Memory) extends the LSTM model by processing data in both forward and backward directions. This bidirectional approach allows the model to have a better understanding of the context by capturing information from both past (backward) and future (forward) states. BiLSTMs are especially useful for tasks like natural language processing, where context from both directions can significantly enhance the model's performance.
