# Electricity-Demand-Forecasting
Electricity Demand Forecasting for Computational Algorithms in Data Science
Improved electricity demand forecasting accuracy from 13% → 9.86% MAPE using a statistically rigorous SARIMAX model with engineered temporal and weather features.

Approach:
Modeled multi-year load data with SARIMAX + exogenous weather variables
Engineered seasonality and trend features (Fourier terms, lag features, rolling stats)
Applied Box-Cox transformation to stabilize variance
Validated assumptions using ADF, ACF/PACF, and residual diagnostics
Addressed multicollinearity in weather inputs (VIF, condition number)

Tech Stack:
Python (pandas, numpy, statsmodels, sklearn)

Kaggle Dataset Link: https://www.kaggle.com/datasets/yug201/delhi-5-minute-electricity-demand-for-forecasting
