# ML-Powered Market-Making Algorithm for Equity Markets

## Overview

This project showcases the development and implementation of an advanced machine learning (ML)-powered market-making algorithm for equity markets. Leveraging historical market data and sophisticated ML techniques, this algorithm aims to optimize market-making strategies through accurate price predictions, efficient portfolio management, and risk mitigation. The project is designed to demonstrate skills in quantitative finance, backtesting, and data science.

## Table of Contents

1. Introduction
2. Data Collection and Preprocessing
3. Feature Engineering
4. Model Development
5. Understanding the Results
6. Backtesting
7. Portfolio Construction and Performance Evaluation
8. Conclusion and Next Steps

## Key Features

### Introduction
- Utilizes seminal work of McLean and Pontiff (2016) to identify effective market signals.
- Focuses on predictive signals categorized into Event, Market, Valuation, and Fundamental types.

### Data Collection and Preprocessing
- Collects historical trade data using yfinance.
- Cleans and preprocesses data to ensure readiness for analysis.

### Feature Engineering
- Identifies and derives key features that impact market movements, such as 52-Week High, Momentum, Volume Trend, and Beta.

### Model Development
- Trains various ML models including Linear Regression, Ridge Regression, RandomForest, GradientBoosting, and XGBoost.
- Employs feature selection with cross-validation to prevent overfitting and ensure robustness.

### Understanding the Results
- Analyzes model performance through metrics like R² and Mean Squared Error (MSE).
- Selects Ridge Regression as the optimal model due to its balance of high predictive power and regularization capabilities.

### Backtesting
- Implements a backtesting strategy to evaluate model performance using historical data.
- Simulates trading strategies (buy, short) and calculates annualized returns.

### Portfolio Construction and Performance Evaluation
- Constructs a weighted portfolio using PyPortfolioOpt.
- Compares optimized portfolio performance against the S&P 500 on return, volatility, and Sharpe ratio.

## Conclusion and Next Steps
- Demonstrates skills in quantitative research, model development, portfolio construction, and financial acumen.
- Suggests areas for improvement, such as incorporating multiple data sources and sentiment analysis, refining model training, and developing trading strategies.

## Requirements
- Python libraries: yfinance, pandas, numpy, statsmodels, scikit-learn, xgboost, joblib, matplotlib, seaborn, cvxpy, PyPortfolioOpt.

This project highlights a comprehensive approach to developing a market-making algorithm, offering insights into the practical application of machine learning in quantitative finance.
