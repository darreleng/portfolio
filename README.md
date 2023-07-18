# Portfolio
This repository is a compilation of practice projects as I explore the world of data science!

## [Project 1 - ARIMA Models](https://github.com/darreleng/portfolio/blob/main/macrodata_arima.ipynb)
On a US macroeconomic dataset, I do a little preprocessing before analysing its time components with STL. Then, I check for stationary using differencing and augmented Dickey-Fuller tests before finding the optimal p and q orders using Akaike Information Criterion. After fitting an ARIMA model, I analyse its residuals qualitatively and quantitatively to check if the model adequately captures the predictable patterns of the data. Finally, I create deterministic time features to be used as exogenous variables for a separate ARIMAX model. 

## [Project 2 - Time Series Forecating with CatBoost](https://github.com/darreleng/portfolio/blob/main/supermarketsales_catboost.ipynb)
This project uses a dataset containing sales of a supermarket. I first clean and transform several different data sources so that they can be merged seamlessly together. Next, I explore the data with visualisations guided by answering business questions such as the effect of wages being paid out on sales and whether there is weekly seasonality. Then, I feature engineer and train a CatBoost model (a gradient-boosted model) on the data. Lastly, I evaluate the model's performance by comparing its sales predictions against the actual sales by product family.

## [Project 3 - Henry Thia vs. Khaw Boon Wan Classifier](https://github.com/darreleng/portfolio/blob/main/thia_khaw_classification.ipynb)
There is a running joke in Singapore that actor Henry Thia and former politician Khaw Boon Wan are doppelgängers. In the first half of this project, I evaluate the accuracy of a semi-supervised K-means model. In the second half, I first build a simple convolutional neural network to establish a baseline accuracy score. From there, I try to improve its score through data augmentation and transfer learning using an EfficientNet model.

## [Project 4 - Energy Anomaly Detection](https://github.com/darreleng/portfolio/blob/main/energy_anomaly_detection.ipynb)
In this project, I try to detect meter reading anomalies in 2 buildings using a CatBoost classifier and an LSTM neural network.

## [Project 5 - Stroke Predictions](https://github.com/darreleng/portfolio/blob/main/stroke_predictions.ipynb)
For this project, I first try to explore the relationships between the different variables and how they interplay with stroke. Afterwards, I try to predict which patient has suffered a stroke before. Some of the patients in the dataset have missing 'bmi' values. To fill each missing value, I use the mean 'bmi' value of other patients who share similar characteristics as the particular patient in question. After imputing and other data preparation steps, I train a CatBoost Classifier model and tune it with cross-validation before evaluating it and trying another approach to improve the overall predictive performance.
