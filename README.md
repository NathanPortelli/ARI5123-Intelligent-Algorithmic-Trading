# Utilising Temporal Convolutional Networks for Cryptocurrency Price Forecasting

Project created in partial fulfilment of the Masters in AI study unit 'ARI5123 - Intelligent Algorithmic Trading'.

## Abstract

This research explores the use of Temporal Convolutional Network (TCN) for predicting cryptocurrency prices. Given the inherent volatility and complex patterns in cryptocurrency markets, traditional forecasting models often fall short. TCNs, being able to capture long-term dependencies in sequential data, are proposed as a superior alternative. The study analyses data from five cryptocurrencies at 15-minute intervals, develops a TCN-based forecasting model and evaluates its performance against baseline models, including Buy-and-Hold, Naïve Forecast, ARIMA, and Long Short-Term Memory (LSTM) networks. Results indicate that TCNs enhanced prediction accuracy and robustness, providing valuable insights for traders in making informed decisions.

### Objectives

The primary aim of this research is to optimise the profitability of cryptocurrency trading strategies, by achieving accuracy and robustness when predicting cryptocurrency prices, thereby empowering traders with valuable insights for informed decision-making.

The objectives are therefore as follows:
- Develop and implement a forecasting model tailored for cryptocurrency price prediction, with the aim of enhancing accuracy and reliability in forecasting future price movements.
- Train and optimise the model using historical price data from several cryptocurrencies.
- Evaluate the forecasting performance of the TCN based on metrics such as Root Mean Square Error (RMSE), Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and R-Squared ($$R^2$$).
- Compare the performance of the TCN with the more established Long Short-Term Memory (LSTM) model, as well as other baseline models, including Buy-and-Hold, Naïve Forecast, and the traditional ARIMA model.
- Conduct trading simulations to assess the real-world applicability and effectiveness of the forecasting models.

## Content
The full research paper can be found [here](https://github.com/NathanPortelli/ARI5123-Intelligent-Algorithmic-Trading/blob/main/Utilising%20Temporal%20Convolutional%20Networks%20for%20Cryptocurrency%20Price%20Forecasting.pdf).

The datasets, extracted from [Binance](https://www.binance.com/en) through their [Binance API](https://binance-docs.github.io/apidocs/spot/en/#), contain historical price data for Bitcoin (BTC), Ethereum (ETH), Ripple (XRP), Binance Coin (BNB), and Litecoin (LTC) at 15-minute intervals, covering the time period from 1st January 2024 until 30th May 2024. This data contains `open_time`, `open`, `high`, `low`, `close`, `volume`, `close_time`, `quote_volume`, `count`, `taker_buy_volume`, and `taker_buy_quote_volume`.

The Python project is within the [Jupyter Notebook](https://github.com/NathanPortelli/ARI5123-Intelligent-Algorithmic-Trading/blob/main/ARI5123_Nathan_Portelli.ipynb). `results.json` contains the output of the Jupyter Notebook.
