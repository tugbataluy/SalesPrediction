# SalesPrediction
Prediction based upon a product by using time series

## Used Libraries
* Pandas
  * pandas.tseries.offsets ->  DateOffset   
* Statsmodels
  * Statsmodels.tsa.stattools -> adfuller
  * Statsmodels.graphics.tsaplots -> plot_pacf, plot_acf
  * Statsmodels.tsa.arima.model -> ARIMA
  * Statsmodels.api (as sm) -> sm.tsa.statespace.SARIMAX
* Matplotlib

## Some Outputs Whic Are Gained
* Sales Amount per Month between 1964 - 1972
  
![image](https://github.com/user-attachments/assets/94021a71-0194-43f2-a5d9-5fa8ff1959fc)

* Seasonal Sale Differences
  
![image](https://github.com/user-attachments/assets/e99445be-92c2-4d0b-8643-a26dc5922f6c)

* ACF PACF Graphs

  
![image](https://github.com/user-attachments/assets/ab70316c-c7ec-4cb5-96f4-51f1989525be)

* ARIMA Prediction ( Predictions are not accurate because data is seasonal )

  
![image](https://github.com/user-attachments/assets/454bd543-c5e8-4017-8a50-d15e2b0afae3)

* SARIMA Prediction ( Sales and Forecasted Values are Approximately same )

  
![image](https://github.com/user-attachments/assets/c89dfd94-81e6-4303-87df-a5f103487ab7)

* Additional Data Created By Using DateOffset and Forecasted
  
![image](https://github.com/user-attachments/assets/7963e6c3-e6c1-4b38-a94e-c09e3875d47b)

