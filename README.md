# Using AI to Predict Stock Prices

## Python 3 Libraries and Modules Used:
- numpy
- pandas
- matplotlib
- scikit-learn
- yfinance

## Purpose and Usage:

- Purpose - demonstrate the usage of continuous target variable Artificial Intelligence Models in combination with stock market data to further build and/or extrapolate the usage of such technologies

- Usage - this code is meant for educational purposes only, it should not be used in real financial decission making and in no way represents or outputs financial advice.
- - Recommended usage begins with the notebook 'correlation_evaluator.ipynb', which recieves a given input of stock tickers, calculates their individual MACD values and trends, and then - using a Linear Regression Model - R-Squared valuesof the MACD for each stock ticker are output.
  - The idea is that the better (closer to r^2=1) values of R-Squared, the more that the linear regression model may be able to explain variance in the day-to-day stock price.
  - With that in mind, after evaluating a group of stocks and finding the best R-Squared value(s), usage reccomends that the user moves into 'stock_prediction.ipynb' where the user may input their individual stock ticker of choice to see both the MACD Signal Line chart, MACD Histogram, more advanced model performance metrics (MSE, RMSE, MAE, and R^2), and finally the prediction for the next day's stock price.
  
## Data Source:
- yfinance
