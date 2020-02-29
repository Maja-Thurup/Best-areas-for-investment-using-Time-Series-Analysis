
# Project - Best areas for investment using Time Series Analysis

In this project you will find my solution to finding top 5 zipcodes for investing in real estate. I used data from [Zillow](https://www.zillow.com/research/data/) that contains all monthly median prices for all zipcodes in USA from year 1996 to 2018. In the notebook you will find the whole process starting with filtering and cleaning the data followed by usefull functions for predictions and testing. At the end you will find tests and forecasts with comprehensive visuals followed by summary and conclusion.


## Use for this project

This project shows a method of finding and forecasting real estate prices. It uses ARIMA model for forecasting. 
**plot_forecast(ts, periods=1)** here you can specify how far in the future you want to forecast. It finds best parameters for ARIMA model and returns plot with TS plus predicted curve.
For testing how this method works there is **test_predictions(ts, test_size=0.05)** function. It returns plot with predicted vs actual prices and RMSE value.

Overall this project can give a good perspective on real estate market trends.






