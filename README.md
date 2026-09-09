# Energy-Consumption-Forecasting
Data Science Master's: Machine Learning Advanced Techniques module project - Energy consumption-Forecasting with classic and recurrent models.  

Energy Analytics is a quantitative consulting firm that optimizes electricity production processes. The goal of this project is to develop, using Python, an energy consumption forecasting system based on **Time Series Analysis techniques**, both classical (ARIMA/SARIMA) and deep learning-based (LSTM). The model must support energy analysis and planning decisions by providing reliable forecasts of future consumption trends.  

The work is designed to be applicable to real-world time series and must include exploratory analysis of the time series, verification of statistical properties, model training and comparison, and quantitative evaluation of predictive performance.  

## Dataset  
File downloadable here: [clustered_hourly_values_all.csv](https://github.com/Profession-AI/progetti-ml/blob/main/Previsione%20del%20Consumo%20Energetico%20con%20Modelli%20Classici%20e%20Ricorrenti/clusteredhourlyvalues_all.csv)  

The dataset contains 30 hourly time series derived from the data collected as part of the "The Smart Metering Electricity Customer Behaviour Trials (CBTs)" Project. The dataset contains electricity consumption data between 2009 and 2010 for more than 5000 homes, shops, and other businesses in Ireland. Each time series in the clustered_hourly_values_all.csv file represents the average consumption (kWh) of a cluster of customers with a similar profile.

For this project, we work with three series selected for their distinct statistical characteristics:

- cluster_26: both daily (24h) and weekly (168h) seasonality are marked; consumption varies significantly across time slots and between weekdays and weekends
- cluster_9: daily (24h) seasonality present, weekly seasonality absent; similar behavior on all days of the week
- cluster_24: no evident seasonality; substantially flat series with unstructured variation.
