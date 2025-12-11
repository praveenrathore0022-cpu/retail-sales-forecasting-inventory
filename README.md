# Retail-sales-forecasting-inventory

Retail Sales Forecasting & Inventory Optimisation (Python | Time Series)

This project develops a weekly retail sales forecasting model using SARIMA to support inventory planning and reduce stockouts. The analysis is based on three years of historical transaction data and follows a complete time-series modelling workflow.

Project Overview

Processed and analysed weekly sales data to understand trends, seasonality, and structural patterns.

Conducted time-series diagnostics, including ADF tests, seasonal decomposition, and ACF/PACF analysis.

Evaluated multiple ARIMA/SARIMA configurations and validated model performance through residual checks and Ljung–Box tests.

Final model achieved a test-set MAPE of 1.63%, providing reliable short-term demand estimates.

Generated 12-week ahead forecasts with confidence intervals to support inventory allocation decisions.

## Tech Stack

Python

Pandas, NumPy

Statsmodels (SARIMA)

Matplotlib / Seaborn

## Key Outputs

In-sample MAPE: 5.72%

Test-set MAPE: 1.63%

Residual diagnostics confirm no significant autocorrelation

Forecasts highlight clear seasonal cycles aligned with retail trading patterns

## Deliverables

Colab  Notebook with the full modelling workflow

12-week forecast output (CSV)

Diagnostic plots and forecast charts

Clean and reproducible project folder
