# stock-prediction-using-lstm-with-trainable-hidden-values
In this project we try an untraditional approach to forecast financial time series (NY stocks prices) based on LSTM arichitecture with TIHS (trainable initial hidden state) values as described in [1]. We trained our model in an unsupersived manner. The taken approach is based on reconstruction of the data many times from the TIHS values (functioning as encoder for the financial time series) and comparing the reconstructed data to the actual data respected to the MSE criterion. Also we use this method to investigate a lower dimension representations of complicated time series which are the TIHS themselves.

All data can be found on the Kaggle site we listed in references [2] (did not upload since it's too big).

We took down the learning proccess monitoring (learning plots and curves) for its lenght makes notebook hard to read.

This code takes some time to run. I suggests that you will start with lower number of iterations and jump right to the actual hyper-parameters that worked for us.
