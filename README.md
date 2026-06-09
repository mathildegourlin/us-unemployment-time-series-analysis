# US Unemployment Rate Time Series Analysis

## Overview

This project analyzes monthly U.S. unemployment rate data from January 2010 through December 2023 using time series analysis techniques in R. The analysis applies the Box-Jenkins methodology, stationarity testing, ARIMA modeling, and forecasting to examine unemployment trends and predict future labor market conditions.

The project demonstrates practical applications of statistical modeling, forecasting, and data visualization while exploring how unemployment rates evolved through major economic events, including the post-Great Recession recovery and the COVID-19 pandemic.


## Objectives

- Analyze long-term unemployment trends in the United States
- Evaluate stationarity using formal statistical tests
- Build and compare ARIMA forecasting models
- Assess model performance through residual diagnostics
- Generate forecasts for future unemployment rates

## Dataset

**Source:** Federal Reserve Economic Data (FRED)

**Series:** UNRATE

**Frequency:** Monthly

**Time Period:** January 2010 – December 2023

**Observations:** 168

The unemployment rate is one of the most important indicators of economic health and labor market performance in the United States.

## Methodology

### Exploratory Data Analysis

- Time series visualization
- Distribution analysis
- Trend identification
- Seasonal pattern assessment

### Stationarity Testing

- Augmented Dickey-Fuller (ADF) Test
- Phillips-Perron (PP) Test

### Time Series Modeling

- ACF and PACF diagnostics
- ARIMA model selection
- Model comparison using AIC
- Residual analysis
- Forecast generation

## Key Findings

- The original unemployment series was nonstationary and required differencing.
- First differencing successfully transformed the data into a stationary series.
- ARIMA(1,1,2) provided the best overall model fit among the candidate models tested.
- Diagnostic testing indicated that model residuals behaved like white noise.
- Forecasts suggested unemployment would remain relatively stable while reflecting increasing uncertainty over longer forecast horizons.

## Technologies Used

- R
- tidyverse
- forecast
- tseries
- ggplot2
- knitr
- R Markdown

## Skills Demonstrated

- Time Series Analysis
- Forecasting
- ARIMA Modeling
- Statistical Testing
- Data Visualization
- Exploratory Data Analysis
- Economic Data Analysis
- R Programming
- Quantitative Research


## Example Outputs

The project includes:

- Time series visualizations
- Distribution plots
- Stationarity diagnostics
- ACF and PACF plots
- Residual diagnostics
- Forecast visualizations



## Future Improvements

- Incorporate structural break analysis for the COVID-19 period
- Compare forecasting performance against alternative models
- Extend analysis using additional macroeconomic indicators
- Explore multivariate forecasting approaches


## Author

**Mathilde Gourlin**

University of California, Santa Barbara

Statistics, Data Science, and Communication


