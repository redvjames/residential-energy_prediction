# residential-energy_prediction
A Project for Machine Learning 3 Course of Asian Institute of Management's Master of Science in Data Science 2023 

This post will discuss a state-of-the-art, hot off-the-press forecasting model called NBEATSx or Neural Basis Expansion Analysis for Time Series with Exogenous Variables. We’ll apply this model in the residential energy consumption context, where we’ll explore how this new model incorporates explainability through time series decomposition and how its performance, in terms of mean absolute percentage error, compares to other existing time series models from basic (e.g., season naive) to more complex (e.g., Prophet).

DATA SOURCE
Hourly Usage of Energy (HUE) Dataset for Buildings in British Columbia. 
This dataset, provided by Simon Fraser University in Canada, covers the period from June 2012 to September 2015. It includes various features such as date, day, month, energy consumption in kilowatt-hours (kWh), hour of the day, humidity levels, holiday indicators, pressure readings, and temperatures. By analyzing this dataset, we aim to gain insights into energy consumption patterns and explore the effectiveness of different time series models in forecasting and optimizing energy usage. Although not specific to the Philippines, this dataset provides a valuable starting point for our pilot study. You can access the dataset here: https://www.nature.com/articles/s41597-022-01455-7
