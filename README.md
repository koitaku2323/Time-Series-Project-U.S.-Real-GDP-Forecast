# U.S.-Real-GDP-Forecast

This time series project aimed to forecast U.S. real GDP using quarterly data from 2002 to 2023.
The project aims to identify critical trends and patterns in U.S. real GDP over this period. Various time series
techniques such as ARIMA, SARIMA, and data transformation were applied to the historical U.S. real GDP data. The data were analyzed for trends, seasonality, and other patterns. The selected forecasting models
were evaluated based on their accuracy and performance using the 12 data points from the test sample.

The project's key results reveal the crucial trends and patterns in U.S. real GDP, such as long-term growth, business cycles, and seasonality. The forecasting models demonstrated their effectiveness in capturing and predicting these patterns. The project provides valuable insights into the future trajectory of U.S. real GDP and offers guidance for policymakers and decision-makers.

In conclusion, the model SARIMA (p = 1, d = 1, q = 0) × (P = 0, D = 1, Q = 1)s=4 was determined to
be the most appropriate and accurate forecasting model that captures trends and patterns in U.S. real GDP
from 2002 to 2023. However, multiple models present precise relative forecasts. Suggesting
that more than one model may be appropriate in forecasting U.S. Real GDP. It is not clear which model
best captures the trend and trajectory. This is reasonable since the original data is not Gaussian due to
volatility during the Great Recession (December 2007 – June 2009) and the Pandemic (April 2020). The
non-Gaussian-like behavior may cause the forecasting values to shift up and down depending on when the
volatility occurred in historical data. For example, the forecast produced by our final model may appear
to be overestimated. This is because there was a recent crash in the economy that decreased U.S. Real GDP
drastically, and is slowly recovering.
