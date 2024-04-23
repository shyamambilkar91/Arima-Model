# Arima Model 
## Autoregressive Integrated Moving Averages

The general process for ARIMA models is the following:
* Visualize the Time Series Data
* Make the time series data stationary
* Plot the Correlation and AutoCorrelation Charts
* Construct the ARIMA Model or Seasonal ARIMA based on the data
* Use the model to make predictions

## Install Dependencies
1. import numpy as np
2. import pandas as pd
3. import matplotlib.pyplot as plt
4. %matplotlib inline
5. from statsmodels.graphics.tsaplots import plot_acf,plot_pacf
6. import statsmodels.api as sm

