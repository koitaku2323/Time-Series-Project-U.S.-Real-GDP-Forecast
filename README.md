# U.S. Real GDP Forecasting Project

This repository contains code and analysis for a project focused on forecasting U.S. real Gross Domestic Product (GDP) using time series analysis techniques, particularly SARIMA models. The project aims to provide insights into the behavior of U.S. real GDP from 2022 to 2023 and generate accurate predictions for future GDP values.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)

## Introduction

The forecasting project utilizes SARIMA (Seasonal Autoregressive Integrated Moving Average) models to predict future U.S. real GDP values based on historical data. The data were analyzed for trends, seasonality, and other patterns. The selected forecasting models were evaluated based on their accuracy and performance using the 12 data points from the test sample. The project aims to assist policymakers, economists, and businesses make informed decisions regarding economic trends and developments.

## Data

The project utilizes historical U.S. real GDP data from reputable sources such as the U.S. Bureau of Economic Analysis (BEA) and the Federal Reserve Economic Data (FRED) database. The dataset covers quarterly GDP values from 2022 to 2023, providing a comprehensive basis for analysis and forecasting.

## Analysis

The analysis begins with data preprocessing steps, including transformations and decomposition, to identify underlying trends and seasonality patterns in the GDP data. SARIMA models are then fitted to the preprocessed data, with various parameter configurations tested to find the best-fitting model. Diagnostic checks, including residual analysis and model evaluation metrics such as AICc, are performed to ensure the reliability and accuracy of the selected model.

## Results

The forecasting results are presented through visualizations and comparisons of model forecasts against actual GDP values. Evaluation metrics such as AICc are used to assess the performance of the models and determine the best-fitting model configuration. The PDF report includes detailed explanations of the results, highlighting the accuracy of the forecasts and their implications for understanding U.S. economic trends. The project's key results reveal the crucial trends and patterns in U.S. real GDP, such as long-term growth, business cycles, and seasonality. The forecasting models demonstrated their effectiveness in capturing and predicting these patterns. The project provides valuable insights into the future trajectory of U.S. real GDP and offers guidance for policymakers and decision-makers.

## Conclusion

In conclusion, the model SARIMA (p = 1, d = 1, q = 0) × (P = 0, D = 1, Q = 1)s=4 was determined to be the most appropriate and accurate forecasting model that captures trends and patterns in U.S. real GDP from 2002 to 2023. However, multiple models present precise relative forecasts. Suggesting that more than one model may be appropriate for forecasting the U.S.'s real GDP, It is unclear which model best captures the trend and trajectory. This is reasonable since the original data is not Gaussian due to volatility during the Great Recession (December 2007 – June 2009) and the Pandemic (April 2020). The non-Gaussian-like behavior may cause the forecasting values to shift up and down depending on when the volatility occurred in historical data. For example, the forecast produced by our final model may appear to be overestimated. This is because there was a recent crash in the economy that decreased the U.S. Real GDP drastically, and it is slowly recovering.

## Acknowledgments

Special thanks to Dr. Feldman for her guidance, support, and valuable insights throughout the project. Thanks also to the U.S. Bureau of Economic Analysis (BEA) and the Federal Reserve Economic Data (FRED) database for providing access to reliable and comprehensive GDP datasets. 
