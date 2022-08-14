# Stock Exchange Prediction with Deep Learning
This project uses Deep learning libraries in Python to predict the price movement of the stock market.

## Dataset 
The dataset is provided by Yahoo finance. They give free access to dataset use for educational and research purposes

> Yahoo!, Y!Finance, and Yahoo! finance are registered trademarks of Yahoo, Inc.
> yfinance is not affiliated, endorsed, or vetted by Yahoo, Inc. It's an open-source tool that uses Yahoo's publicly available APIs, and is intended for research and educational purposes.
> You should refer to Yahoo!'s terms of use (here, here, and here) for details on your rights to use the actual data downloaded. Remember - the Yahoo! finance API is intended for personal use only.
> --- https://pypi.org/project/yfinance/

## Data Processing
Since this is a Time Series Analysis, i used timesteps in generating the features. the optimal number was 5, so 5 timesteps. Used MinmaxScaler from the sklearn library to normalize the data. 

## Models 
Models were built with the Funtional and Sequential API in the keras library. 3 were built with Sequential API and one with the Functional API. 
### Different models used :-
- LSTM with 2 hidden layers
- LSTM with 4 hidden layers
- Bidirectional LSTM with 2 hidden layers
- Bidirectional LSTM with 3 hidden layers
- Y-shaped model with Bidirectional LSTM on two input layers


## Evaluation
Two metrics were used for the evaluation of the these regression models.
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)






