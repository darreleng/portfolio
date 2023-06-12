# Portfolio
This repository is a compilation of practice projects as I explore the world of data science.

## [Project 1 - ARIMA Models](https://github.com/darreleng/portfolio/blob/main/macrodata_arima.ipynb)
On a US macroeconomic dataset, I do a little preprocessing before analysing its time components with STL. Then, I check for stationary using differencing and augmented Dickey-Fuller tests before finding the optimal p and q orders using Akaike Information Criterion. Once an ARIMA model is fitted, I analyse its residuals qualitatively and quantitatively to check if the model adequately captures the predictable patterns of the data. Finally, I create deterministic time features to be used as exogenous variables for a separate ARIMAX model. 

## [Project 2 - Time Series Forecating with CatBoost](https://github.com/darreleng/portfolio/blob/main/supermarketsales_catboost.ipynb)
This project uses a dataset containing sales of a supermarket. I first clean and transform several different data sources so that they can be merged seamlessly together. Next, I explore the data with visualisations guided by answering business questions such as the effect of wages being paid out on sales and whether there is weekly seasonality. Then, I feature engineer and train a CatBoost model (a gradient-boosted model) on the data. I evalute the model and do more feature engineering to improve the model's performance.

## Upcoming Projects
* Time series forecasting with Deep Learning
* Classification problems
