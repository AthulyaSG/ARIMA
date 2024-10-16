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

## Data Transformation

### Logarithmic Transformation

- To stabilize the variance of the data
- To convert multiplicative relationships into additive relationships
- To make the data more normally distributed

![image](https://github.com/user-attachments/assets/818e9238-c515-48fa-b36e-8b55c84f27ed)

### Removing Trend With Moving Average

- To identify seasonal patterns
- To stabilize the variance of the data
- To make the time series stationary

![image](https://github.com/user-attachments/assets/41a0d9db-16d6-4588-9bf8-209f8fbfe5bf)

### Exponential Decay Transformation

- To stabilize the variance of the data
- To model and analyze the data using traditional time series techniques

![image](https://github.com/user-attachments/assets/feb0030c-b37c-44ae-b6f6-f95ca575337a)

### Time Shift Transformation

- To compare and analyze data at different lags
- To identify the time delay between the two variables
- To better understand the relationship between them

![image](https://github.com/user-attachments/assets/d630bd48-631a-4e3b-8fa2-2148ddd8b57e)














