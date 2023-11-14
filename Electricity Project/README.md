# Time Series Forecasting with FBProphet - NYC Electricity Consumption

## Overview

This group project contains the code and documentation for implementing a Time Series Forecasting model in Python using the FBProphet module. The model predicts New York City’s Electricity Consumption based on historical data, considering daily, monthly mean, and yearly mean datasets.

## Datasets

- **Daily Data:** [Electric Consumption and Cost 2010-April 2020](https://data.cityofnewyork.us/Housing-Development/Electric-Consumption-And-Cost-2010-April-2020-/jr24-e7cr)
- **Monthly Mean Data:** Derived from the daily dataset by averaging consumption based on each month.
- **Yearly Mean Data:** Derived from the daily dataset by averaging consumption based on each year.

## Tasks and Outputs

1. **Code Agnostic Time Unit Determination:**
   - Ensure the code automatically determines the time unit (day, month, or year) of the input dataset.

2. **Model Training and Prediction:**
   - Train the FBProphet model on each dataset and predict Electric Consumption (EC) values into the future.
   - Predict EC for:
     - Daily data: 100/200/365 days into the future
     - Monthly data: 1/6/9 months into the future
     - Yearly data: 1/10/20 years into the future

3. **FBProphet Model Tuning:**
   - Tune the model on the following parameters:
     - Forecasting growth: logistic, linear, flat
     - Seasonality: Add manual seasonality with various values for 'period' and 'fourier_order.'
     - Trend Changepoints: Tune 'n_changepoints' and 'changepoit_prior_scale' arguments.

4. **Model Evaluation:**
   - Print predicted values in tabular format.
   - Draw a line graph showing both historical data and future predictions.
   - Evaluate models using MAE, MAPE, and R^2 metrics.

## Implementation

All code and results are available in a single Jupyter Notebook file for easy review and reproduction.

