# SARIMAX_model
Using ARIMA and SARIMAX models to forecast a time series of electrical energy usage

1. Tested the data using the ADF test statistic for stationarity
2. Used differencing to create first order 1-lag data and seasonal 12-lag data
3. Plotted the ACF and PACF to aid in AR, MA value decisions
4. Created rough base model without seasonality to verify initialy hypothesis of seasonality
5. Created SARIMAX model which captured the trend of data
6. Created forecast based on the SARIMAX model

# Issues
1. DATE in string form, converted to datetime and labelled as index for an interpretable visualisation
2.  Depracated import call for ARIMA
- from statsmodels.tsa.**arima_model** import ARIMA > from statsmodels.tsa.**arima.model** import ARIMA
- 
