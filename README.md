This project focuses on forecasting energy consumption using a time-series approach with LSTM (Long Short-Term Memory) networks. It leverages a dataset of hourly energy consumption values, which is cleaned, processed, and scaled using MinMaxScaler. A time-window of 24 hours is used to predict future energy consumption. The LSTM model is trained to capture temporal dependencies, with training and testing data split at an 80/20 ratio. 

After training the model, predictions are made on the test dataset, and the results are inverse-scaled to match the original energy consumption values. The performance of the model is evaluated using Root Mean Squared Error (RMSE) to assess the accuracy of the predictions. 

Visualizations are generated to compare the predicted energy consumption with the actual values, helping identify the model's predictive accuracy over time. This project demonstrates how deep learning techniques like LSTM can be used to make accurate energy consumption forecasts, assisting in better resource planning and consumption management.