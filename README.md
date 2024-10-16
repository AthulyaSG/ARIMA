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

![image](https://github.com/user-attachments/assets/39f06e9b-a0c5-49bb-b62b-8f93e0bd4f1f)





