# Forecasting Passenger Airplane Traffic

## Introduction
Forecasting passenger airplane traffic is essential for airlines and airport management to optimize operations, plan resources, and improve customer service. In this project, we will use time series analysis techniques to forecast future passenger traffic.

## Dataset
The dataset used for this project consists of historical monthly passenger traffic data. A dataset for this task is the "Airline Passengers" dataset, which records the number of international and domestical airline passengers from 2002 to 2017.

## Prerequisites
Ensure you have the following libraries installed:
- `numpy`
- `pandas`
- `matplotlib`
- `statsmodels`

## Check for Stationary

If the data is not stationary `p-value > 0.05`, so you should try different methods, such as _**log transformation**_, _**moving average**_, _**seasonal decomposition**_, etc.

## Model Explanation
Given that the data exhibits clear seasonal patterns, we will use the Seasonal AutoRegressive Integrated Moving Average (SARIMA) model for forecasting. SARIMA extends ARIMA by explicitly modeling the seasonal components in the data.

## Conclusion
In this project, we used the SARIMA model to forecast passenger airplane traffic. The SARIMA model is particularly suited for this task due to its ability to handle seasonality in the data. The forecasted results can help airlines and airport management to better prepare for future passenger traffic volumes.
