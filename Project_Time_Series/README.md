# Machine Learning & Time Series: Sweet Lift Taxi

## Project Description:
Sweet Lift Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak hours, we need to predict the amount of taxi orders for the next hour. 
Build a model for such a prediction.

The RMSE metric on the test set should not be more than 48.

## Project Instructions:
1. Download the data and resample it by one hour.
2. Analyze the data.
3. Train different models with different hyperparameters. The test sample should be 10% of the initial dataset.
4. Test the data using the test sample and provide a conclusion.

## Key Concepts:
🗝️ Resampling data using df.resample()

🗝️ Autoregressive (AR); Moving Average (MA); Autoregressive Integrated Moving Average (ARIMA)

🗝️ Linear Regression, Random Forest, LightGBM, Time-based models

🗝️ Feature Engineering; RMSE Metric

## What I Learned:
✔️ Time-based models are built on the assumption that past values contain information about the future.

✔️ Univariate time series data - forecasting a single variable's future based on its own past.

✔️ ARIMA models assume Linearity in data and don't work well with non-linear relationships.
