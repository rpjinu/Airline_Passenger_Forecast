# Airline_Passenger_Forecast
"Forecasting airline passenger numbers using time series analysis with ARIMA, SARIMA, and ETS models to explore and compare different approaches for accurate prediction."

*Project Overview*

The project utilizes a dataset of monthly international airline passengers from January 1949 to December 1960. The main objective is to predict future passenger numbers and evaluate the performance of different time series models.

*Dataset*
Source: Time Series Data Library\
*Attributes*
Month: Time period (YYYY-MM format)\
Passengers: Number of passengers (in thousands)\
*Models Implemented*
ARIMA (AutoRegressive Integrated Moving Average):\
Captures the linear relationship and trends within the time series.\
SARIMA (Seasonal ARIMA):\
ETS (Error, Trend, Seasonal):\
Decomposes the time series into error, trend, and seasonal components.\
*Project Workflow*
Data Processing:-\

Loaded and visualized the dataset.\
Managed any missing data and prepared the dataset for modeling.\
Split the data into training and testing sets for model evaluation.\
*Model Training:*

Trained ARIMA, SARIMA, and ETS models on the training dataset.\
Evaluated models using metrics like RMSE and AIC.
Visualized the forecasting results to assess model performance.
Model Selection and Saving:

Selected SARIMA as the best-performing model.
Saved the trained SARIMA model for future forecasting.
