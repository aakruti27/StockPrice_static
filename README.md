# Stock Price Prediction with Linear Regressor

Dateset:- https://www.kaggle.com/datasets/caesarmario/samsung-electronics-stock-historical-price?select=005930.KS_weekly.csv

The dataset had weekly values for 6 different attributes. We decided to work with this as static data instead of time series in this project to see if it still performs well with basic logic regression model without Date attribute taken into account. 

We also visualized different attributes to see the pattern among them and remove or adjust any values. 

There was not a gaussian distrubution which is why Normalized data gave better results - MSE=0.001
With standardized data, we got a little higher error(=0.0154) but it was still not too bad. 

The final step was to combine the validation and training normalized data and predict from test set, the MSE on test set was 0.0008
