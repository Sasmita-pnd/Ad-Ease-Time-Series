# Ad-Ease-Time-Series
### Introduction
● Ad Ease is an ads and marketing-based company helping businesses elicit maximum clicks at minimum cost.

● AdEase is an ad infrastructure to help businesses promote themselves easily,effectively, and economically.

● Ad ease trying to understand the per page view report for different wikipedia pages for 550 days, and forecasting the number of views so that you can predict and optimize the ad placement for your clients.\n


### Objective
We are provided with the data of 145k wikipedia pages and daily view count for each of them.

We need to understand the per page view report for different wikipedia pages for 550 days, and forecasting the number of views to predict and optimize the ad placement for your clients.

Clients belong to different regions and need data on how their ads will perform on pages in different languages.

### Techniques Used 
**EDA**


**Data Wrangling**
*   Null values check, Feature Engineering 


**Data Visualisation**
*   Time Series Plots, Distribution Plots using Bar-Plots


**Stationarity, decomposition, detrending, ACF, and PACF**


**Model**
*   ARIMA, auto- ARIMA, SARIMAX, Facebook Prophet


### Results
**Arima** Model for Different Language Pages Summary
*   MAPE for de: 0.077
*   MAPE for en: 0.072
*   MAPE for es: 0.218
*   MAPE for fr: 0.077
*   MAPE for ja: 0.078
*   MAPE for ru: 0.054
*   MAPE for zh: 0.046

**Sarimax** model for en as exogeneous variable was available for en only
*   MAPE for en without exog: 0.08
*   MAPE for en with exog :0.048

**Facebook Prophet** model for en with exog
*   MAPE: 0.04

Best MAPE value is achieved by Facebook Prophet for english pages of 0.04
