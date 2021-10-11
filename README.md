# Forecast-Modeling-and-Predictions <br>
By Using Statistical Model ( ARIMA ) to Predict the Quantity Demand in future <br>

**Raw Data** <br>
![rawdata](https://user-images.githubusercontent.com/55430748/136794939-c31fa73d-a678-4450-9899-c8aaa50bbb45.png) <br>

**Checking Trend-Seasonality of Data**<br>
- If there is behaviour of increasing or decreasing trend , we have to remove it before modeling <br>
![trend_seasonal_residual](https://user-images.githubusercontent.com/55430748/136795107-8bdfdcfa-2958-4f75-a20f-5144ebabb6c8.png) <br>

**Checking ACF and PACF** <br>
- To get possible parameters p and q for ARIMA model <br>
![ACF_PACF](https://user-images.githubusercontent.com/55430748/136795506-28f40f7b-bd32-447e-93c3-e6ab93ab4bba.png) <br>


**Results of Modeling** <br>
![result](https://user-images.githubusercontent.com/55430748/136795535-f0a691dd-1215-4bc1-93f6-6b6cc7f691a7.png) <br>


**Predictions for next three months** <br>
- Predicting for next three months and calculate the confidence intervals of predictions <br>
- Confidence Intervels are based on 95% confidence levels and can be considerd as the possible upper and lower bounds. <br>
![prediction](https://user-images.githubusercontent.com/55430748/136795588-b891da87-7380-49f0-a6e2-9a8ed73cdc2b.png) <br>

**MAPE between Predctions and Actual Values (3 months)** <br>
MAPE(Mean Absolute Percentage Error) : 13.32% / 25.31% /19.55% <br>
