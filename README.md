## Prices of cryptocurrencies forecasted
The data on cryptocurrencies if taken from the below data source
https://data.world/chasewillden/cryptocurrency-price-by-date-2013-february-2018# 
The data contains around 1515 cryptocurrencies and their prices from 2013 to 2018. the target is to forecast the future prices of the cryptocurrencies based on the present and past p[rices.

#### Modeling 
In the Modeling phase, we aimed to evaluate the performance and predictive capabilities of various models on a sample cryptocurrency. This initial step was crucial to determine the feasibility and effectiveness of scaling these models to top cryptocurrencies in subsequent analyses.
The models used include LSTMs, Bidirectional LSTMs, GRUs, ARIMA model, SARIMA model and Prophet. The rmse, r2 score and visual plots are used as metrics for evaluation of each model trained and tested.

Among the various models tested, the Prophet model showed the most promising results. It was able to capture the seasonality and trend effectively, providing accurate forecasts with lower error rates compared to the other models.

#### Prediction and results

The prediction is done for the top 10 cryptocurrencies in 2018 till the last date in the data, to find the cryptocurrencies with high prices in the next 45 days, using Prophet. 
<img width="1398" alt="Screenshot 2024-05-31 at 5 45 25 PM" src="https://github.com/Neelesh1305/Price-forecasting-on-cryptocurrency-data/assets/113800036/24fd3f92-eed0-4480-8a87-83646f77d26e">

#### Conclusion
Among all the models that we have used the pret-trained model Prophet looked most promising and hence we have chosen that model for our final predictions.
Based on our predictions and above data, we can deduce that by the end of March 1, 2018 the top cryptocurrencies with highest price would be bit20, 42-coin, project-x, bitbc and bitcoin, assuming there are no new cryptocurrencies by then.
