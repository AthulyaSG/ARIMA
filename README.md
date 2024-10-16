# Rice Production Forecast Using ARIMA Model

## Introduction

- Forecasting the production of rice using ARIMA model
- Bivariate analysis
- Dataset: https://www.kaggle.com/code/vaibhavkhande/analysis-on-crop-production-in-different-countries/notebook
- Preprocess the data
    * Removed columns not required
    * replace() and dropna() to remove null values
    * Used groupby() to calculate the mean crop yield for each country

## Plotting Rolling Statistics

- To understand trends and patterns [upward or downward trend]
- To detect changes in variance [shift in the underlying process (depending on SD changes)]
- To assess stationarity [statistical properties do not change over time]
- To improve forecasting accuracy [smooth out the data]

![image](https://github.com/user-attachments/assets/6a4f5853-2a63-48e7-a60d-68bfff93f282)

## Augmented Dickey-Fuller (ADF) test

- To check whether the time series is stationary or not

![image](https://github.com/user-attachments/assets/fc6bf5c2-4655-4394-9215-d19e84325b08)

## Coupling AD-Fuller check with MA and moving SD

- To identify the trend and volatility of the data

  ![image](https://github.com/user-attachments/assets/7f7c9b91-af8a-4077-bc8a-923ff876983e)










