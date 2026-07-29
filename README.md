# Markowitz Portfolio Optimizer
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abenezer1244-afk/markowitz-portfolio-optimizer/blob/main/markowitz_portfolio_optimizer.ipynb)
Institutional-style portfolio optimization using Modern Portfolio Theory in Python.

## Features

- Multi-asset portfolio optimization
- Efficient Frontier
- Maximum Sharpe Ratio portfolio
- Minimum Volatility portfolio
- Monte Carlo portfolio simulation
- Ledoit-Wolf covariance shrinkage
- Out-of-sample backtesting
- Interactive Plotly visualizations

## Technologies

- Python
- pandas
- NumPy
- SciPy
- scikit-learn
- Plotly
- yfinance

## Data Source

- Yahoo Finance
## Visualizations

### Efficient Frontier
Shows thousands of feasible portfolios generated through Monte Carlo simulation, the efficient frontier, the minimum-volatility portfolio, and the maximum-Sharpe portfolio.

![Efficient Frontier](efficient_frontier.png)

### Portfolio Allocations
Compares the optimal asset weights for the minimum-volatility and maximum-Sharpe portfolios.
![Portfolio Allocations](portfolio_allocations.png)

### Growth of $1
Compares the cumulative performance of optimized portfolios against an equal-weight portfolio and the SPY benchmark.
![Growth of $1](growth_of_1.png)
![Growth of $1](growth_of_1D.png)
## Results

This project generates:
- Efficient Frontier
- Portfolio allocation charts
- Correlation heatmap
- Growth of $1 backtest
- Performance metrics (Sharpe, Sortino, Calmar, Drawdown)

## Author

Abenezer Alemu
