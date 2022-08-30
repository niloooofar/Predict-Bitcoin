## Predicting BTC Close Price using Time Series with Deep Learning 

We predict next 3 close price of bitcoin based on multiple variables. So we do multivariate single target multi step time series analysis here. We get BTC data from `https://twelvedata.com` api and do a time series analysis with different deep learning models. Finally we compare the result of different models on our data to figure out which model did the best on predicting the close price.

### Dataset

 We get real time BTC data from https://twelvedata.com api

Remember to put your own api key in `api_key` variable inside `get_crypto_price` function.
