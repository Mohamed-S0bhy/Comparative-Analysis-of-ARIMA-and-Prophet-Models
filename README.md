# Time Series Forecasting Comparison: ARIMA vs. Prophet

### Project Overview
This project involves a comparative analysis of ARIMA and Prophet models for time series forecasting. The goal is to evaluate and compare the accuracy of these forecasting models using a dataset containing sales data.

### Data
The dataset used in this project contains two columns:
DATE: The date of the sales data.
SALES: The sales figures corresponding to each date.

### Project Structure
data.csv: The dataset file containing historical sales data.
forecasting_comparison.py: The Python script that performs the following tasks:
Loads and prepares the data.
Applies ARIMA and Prophet models for time series forecasting.
Generates and evaluates forecasts for both models.
Visualizes the actual vs. predicted values using Plotly.

### Requirements
To run the project, you'll need the following Python packages:

pandas
numpy
statsmodels
fbprophet
plotly
scikit-learn

### Results
The project provides:
Performance Metrics: MAE, MSE, and RMSE for both ARIMA and Prophet models.
Visualizations: Plots showing actual vs. predicted values for training and test datasets.
