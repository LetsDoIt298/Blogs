# Time series forecasting can be confusing to navigate so many algorithms.

1. ARIMA (AutoRegressive Integrated Moving Average): Uses a Linear Regression as the base model. Captures autoregressive and moving average terms, along with integrating the differencing of raw observations (to make the time series stationary). Local only (requires loops for each time series). AutoARIMA is my preferred implementation.

2. Prophet: A forecasting tool developed by Facebook. Designed for data with daily observations and seasonal patterns, employing an additive model with yearly, weekly, and daily components. Local forecasting (requires loops).

3. LSTM (Long Short-Term Memory): A type of recurrent neural network (RNN) used in deep learning. It is specifically designed to avoid the long-term dependency problem, making it effective for time series. My preferred implementation is AWS's GluonTS DeepAR.

4. Holt-Winters Method: A statistical forecasting technique that applies exponential smoothing to capture trend and seasonality in time series data. Useful for data with a clear trend and seasonal pattern. A special case of Exponential Smoothing.

5. SARIMA (Seasonal ARIMA): An extension of ARIMA that incorporates seasonality. Designed for time series with both non-seasonal and seasonal components, making it more flexible than the standard ARIMA model. AutoARIMA is my preferred implementation.

6. Exponential Smoothing: Applies exponentially decreasing weights to past observations. Best for short-term forecasts, particularly effective for data without trends or seasonal patterns. ETS (Exponential-Trend-Smoothing) is my preferred implementation.

7. Random Forest: An ensemble learning method that makes many decision trees. The forecast is the mean prediction of the individual trees. Global or local. Scalable. Cannot predict over max/min due to tree-based algorithm problem.

8. XGBoost: An efficient and scalable implementation of gradient boosting. Known for its high performance and flexibility in handling various types of predictive modeling tasks. Does well at detecting complex seasonality provided feature engineering is performed. Global or local. Cannot predict over global min/max.

![1719579905475](https://github.com/LetsDoIt298/Blogs/assets/90137904/de0f16ec-75df-4360-b316-f2edd1ff70cf)

