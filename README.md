# Using a Stacked LSTM model to Forecast Stock Prices

I started this project because I wanted to try to use the LSTM model on a time series. In particular, I used a stacked LSTM model with multiple hidden LSTM layers. This produces a much better output than a vanilla LSTM model.

## Results

For predicting the test data, the model performed relatively well. The RMSE for `train_predict` was only 14.65. On the other hand, the RMSE for the `test_predict` was 16.12. As both of the RMSE values were close to each other, I was confident to move on.

