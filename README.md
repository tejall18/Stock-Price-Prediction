# Stock-Price-Prediction

 
 ## Relevant Files
 1. [SPY.csv](https://github.com/bsamaha/Python-Trading-Robot/blob/master/SPY.csv) - This file contains the pulled data on the SPY ETF from its inception until 8/31/2020
 2. [SPY Time Series Forecasting.ipynb](https://github.com/bsamaha/Python-Trading-Robot/blob/master/Notebooks/1.%20Time%20Series%20Forecasting%20with%20Naive%2C%20Moving%20Averages%2C%20and%20ARIMA.ipynb) - This notebook contains code showing how to update the SPY.csv to present day and also contains a naive model, 5 day moving average, 20 day moving average,an ARIMA model, and a Recurrent Neural Network model.
 3. [Linear Model Forecast](https://github.com/bsamaha/Python-Trading-Robot/blob/master/Notebooks/2.%20Linear_Model_Forecast.ipynb) - This notebook was created in google colab and may need to be loaded into colab to run as may all notebooks succeeding this one. This is a linear model with a single dense neuron.
 4. [Dense Forecasting](https://github.com/bsamaha/Python-Trading-Robot/blob/master/Notebooks/3.%20Dense_Forecast.ipynb) - This was created in colab and is a model of two dense layers containing 10 units each.
 5. [RNN Notebook](https://github.com/bsamaha/Python-Trading-Robot/blob/master/Notebooks/4.%20RNN_seqtovec_seqtoseq.ipynb) - This notebook was created in colab and shows how I ran this model using RNNs.
 6. [LSTM.ipynb](https://github.com/bsamaha/Python-Trading-Robot/blob/master/Notebooks/5.%20LSTM_Model.ipynb) - This model contains a model built using Long Short Term Memory cells in the recurrent neural network . This notebook was built in Google Colab and is intended to be used in Google Colab for GPU purposes.
 7. [Preprocessing with CNN](https://github.com/bsamaha/Python-Trading-Robot/blob/master/Notebooks/6.Preprocess_CNN.ipynb)  - In colab, this notebooks hows how to use a 1D conv net to preprocess data for a RNN.
 8. [Full CNN - WaveNet](https://github.com/bsamaha/Python-Trading-Robot/blob/master/Notebooks/7.%20Full_CNN_Wavenet.ipynb) - This notebooks created in colab shows how to create a full CNN to use for time series analysis using a wavenet architecture.
 4. [Formulas.py](https://github.com/bsamaha/Python-Trading-Robot/blob/master/Notebooks/formulas.py) - This .py file contains a miscellaneous group of functions I thought I would be using throughout this project. This file is imported into only the "Time Series Forecasting.ipynb". In the notebooks authored using Colab the relevant functions are located inside.

## Project Summary
The resulting error from all models built and tested are shown in the bar graph below. As you can see the most simple model, a Naive forecast outperformed many of the complex deep learning algorithms in terms of error. Surprisingly to me, the LSTM with a 30 day rolling window outperformed all models.

