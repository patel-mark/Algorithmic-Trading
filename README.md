# Algorithmic Trading Strategy using Backtesting & Risk Analysis

Welcome to my project repository for developing and evaluating an algorithmic trading strategy using historical financial and macroeconomic data. The goal of this project was to create a robust trading model that integrates technical indicators and macroeconomic signals, and then test its performance through backtesting and risk evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Project Objectives](#project-objectives)
- [Data Acquisition and Preparation](#data-acquisition-and-preparation)
- [Feature Engineering](#feature-engineering)
- [Modeling Approach](#modeling-approach)
- [Backtesting and Risk Analysis](#backtesting-and-risk-analysis)
- [Results and Insights](#results-and-insights)
- [Conclusion](#conclusion)
- [How to Run the Project](#how-to-run-the-project)


## Introduction

In this project, I developed an algorithmic trading strategy focused on the QQQ ETF (tracking the NASDAQ-100). The strategy incorporates both technical and macroeconomic indicators and uses machine learning to generate buy/sell signals. I evaluated the performance through rigorous backtesting and drawdown analysis.

## Project Objectives

- Retrieve and clean historical financial and macroeconomic data
- Engineer relevant trading features using TA-Lib and custom formulas
- Train a predictive model using XGBoost for market movement classification
- Backtest the strategy over historical periods and benchmark against a buy-and-hold strategy
- Analyze performance, returns, and risk metrics

## Data Acquisition and Preparation

- **Sources**:
  - Yahoo Finance (`yfinance`) for QQQ historical data
  - FRED API for macroeconomic indicators (VIX, CPI, Fed Rate, etc.)

- **Cleaning**:
  - Forward-filled missing macroeconomic data
  - Aligned indicators with price time series

## Feature Engineering

- **Technical Indicators**: RSI, MACD, Bollinger Bands, SMA/EMA
- **Macroeconomic Features**: VIX Index, Industrial Production, Fed Rate, CPI
- **Rolling Features**: Lagged returns, volatility, and trend strength metrics

## Modeling Approach

- **Model**: XGBoost Classifier to predict binary labels (buy or no-buy signal)
- **Evaluation**:
  - Train/test split with `TimeSeriesSplit`
  - Metrics: Accuracy, Precision, Confusion Matrix

## Backtesting and Risk Analysis

- Applied trading logic based on predicted signals
- Calculated daily returns from QQQ price data
- Assessed cumulative returns and drawdowns
- Compared results against a buy-and-hold benchmark
- Plotted performance curves and risk metrics

## Results and Insights

- The strategy captured major uptrends and avoided significant drawdowns
- XGBoost improved predictive accuracy when macro indicators were added
- Cumulative returns outperformed passive investing in several market phases
- Strategy is robust but sensitive to feature scaling and economic shocks

## Conclusion

This project demonstrates the effectiveness of combining technical and macroeconomic signals with machine learning for algorithmic trading. While the strategy shows promise, further enhancements could include real-time signal processing and additional risk controls.

## How to Run the Project

1. Clone the repository
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Algorithmic Trading Strategy using Backtesting & Risk Analysis.ipynb`
4. Insert your FRED API key if prompted
5. Run all cells sequentially



---

I hope you find this project insightful and valuable for your algorithmic trading strategies. Contributions and feedback are welcome!

