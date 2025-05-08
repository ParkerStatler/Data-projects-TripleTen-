# Time Series
## Introduction
Sweet Lift Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak hours, we need to predict the amount of taxi orders for the next hour. Build a model for such a prediction. The model must score an RMSE of 48 or lower.
## Project 
- Data was loaded in with datetime as the index
- General graphs were looked at:
  - The plot of the dataframe
  - Trend, seasonality, and residuals
- Seasonality was looked at on a 24 hour timeframe
- Autocorrelation and partial autocorrelation graphs were made
- The moving average was graphed on the dataframe plot
- Data was preprocessed for training
  -Stationarity was check, data was stationary
  - features were made:
    - month
    - day
    - day of the week
    - hour
    - lag
    - rolling mean
- Data was split for training and testing
- Three models were trained
  - Linear regression
  - Random Forest regressor
  - Arima
## Conclusion
Linear Regression was also trained and tested more as a sanity check. The Random Forest model provided the best results fitting the necassary criterion with an RMSE of 47.4. The Random Forest model would be the best choice for predicting taxi sales for the next hour.
