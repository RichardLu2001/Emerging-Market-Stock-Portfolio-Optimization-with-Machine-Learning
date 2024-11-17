⚫Data Import: Retrieved two decades of fundamental data and adjusted closing prices of CSI 300 Index stocks from Bloomberg
⚫Stock Prediction and Selection: Trained an XGBoost model for each stock using its fundamental data from 2001-2020 and grid search, predicted quarterly returns for 2020-2024, and picked top 25% performing stocks to make up each quarter’s portfolio
⚫Portfolio Optimization: Utilized TA-Lib to calculate technical indicators for each stock in the portfolio, trained XGBoost model on the technical data to predict weekly returns, and used Markowitz mean-variance analysis in Riskfolio-Lib to optimize weekly
⚫Results: The optimized portfolio achieved significantly higher cumulative return and Sharpe ratio than the CSI 300 Index
