# Time-Series-Analysis
Projects on Time series models

## Project 1
This project shows a step-by-step process of fitting an ARIMA model into a series. 

I have fitted and compared two ARIMA models on the same series and concluded which one fits better based on statistical tests.

## Project 2
This project studies two data sets available in the TSA Package. 

#### Data 1: Prescription data: This is the monthly U.S. average prescription costs for 68 months from August 1986.

Results from the Augmented Dickey-Fuller test and F statistics (Equivalent to self-calculated phi3) are compared to test whether the time series has a unit root.

#### Data 2: Beer Sales: This is the monthly beer sales in millions of barrels, 01/1975 - 12/1990.

The trend is estimated by smoothing it and the order for moving average smoother is selected. Further, the series is decomposed as an additive model with trend, seasonal, and random components.

## Project 3
The project studies the Google dataset available in the TSA package. Daily returns of the Google stock from 08/20/04 - 09/13/06.

Series is tested for heteroskedasticity. A step-by-step process of fitting an ARMA-GARCH model is shown.

### Packages used
TSA,
forecast,
lmtest,
fGarch,
urca,
tseries,
dplyr, 
ggplot2

#### Note: R is a case-sensitive language.
