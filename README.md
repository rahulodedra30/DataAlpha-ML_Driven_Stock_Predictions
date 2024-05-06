# Machine Learning-Powered Trading Strategies

This repository contains code and documentation for implementing machine learning-powered trading strategies. The project focuses on utilizing machine learning techniques to develop and evaluate trading strategies for financial markets.

### Project Overview
The project aims to develop and evaluate machine learning-powered trading strategies using a variety of data sources and methodologies. Key components of the project include:

1. Data Collection: Utilizing APIs to collect macroeconomic data and stock market information, focusing on selected stocks and their competitors.
2. Feature Engineering: Extracting and engineering features from diverse sources such as FRED, Fama-French website, ADS, AR, CAPM, momentum factors, volume, and price/return lags.
3. Model Development: Training multiple machine learning models using the constructed feature database to predict stock prices or returns. Models include regression-based approaches (Ridge regression, LASSO, Elastic Net, LARS) and decision tree-based approaches (Random Forest, XGBoost).
4. Model Evaluation: Comparing the performance of trained models using metrics such as RMSE (Root Mean Square Error) against actual values in a testing period.
5. Benchmark Study: Including benchmark studies using GARCH or Kalman Filter methodologies to assess model performance.
6. Trading Rules: Designing trading rules incorporating buy-and-hold, long-short, or day trading strategies using XGBoost models.
7. Trading Signal Generation: Generating trading signals using the developed machine learning models and comparing their Profit and Loss (PnL).
