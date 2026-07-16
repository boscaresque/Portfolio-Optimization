# Portfolio-Optimization

## Overview
This project uses historical stock data to construct a portfolio, evaluate its performance, and find the risk-adjusted optimal weighting between four stocks through large-scale simulation — a core technique in quantitative finance and portfolio management.

## Key Features
Portfolio construction from imported historical price data for 4 stocks
Performance visualization of portfolio value and returns over time
Risk/return metrics, including daily returns and the Sharpe ratio
Monte Carlo simulation: 10,000 portfolios generated with randomized asset weightings
Optimization: identifies the weight allocation that maximizes the Sharpe ratio
Scatterplot visualization of all 10,000 simulated portfolios, highlighting the optimal one

## Tech Stack
Python
Jupyter Notebook
pandas / NumPy — data handling and calculations
Matplotlib — data visualization

## Methodology
Import historical price data for four selected stocks
Construct a portfolio and calculate daily returns
Compute portfolio-level metrics, including cumulative returns and the Sharpe ratio
Generate 10,000 randomized weight combinations across the four stocks
Calculate the Sharpe ratio for each simulated portfolio
Identify the portfolio with the highest Sharpe ratio and its corresponding weights
Visualize all simulated portfolios on a scatterplot, highlighting the optimal allocation

##Results
Optimal Sharpe ratio: [fill in value]
Optimal weight allocation: [Stock A: __%, Stock B: __%, Stock C: __%, Stock D: __%]

(Add a screenshot of your scatterplot here for extra visual impact — recruiters respond well to seeing the output.)

[Sharpe Ratio Scatterplot](images/sharpe_scatterplot.png)

## Getting Started
bashgit clone https://github.com/[your-username]/[repo-name].git
cd [repo-name]
pip install -r requirements.txt
jupyter notebook

## Project Structure
├── portfolio_optimization.ipynb   # Main analysis notebook
├── data/                          # Stock price data
├── images/                        # Saved plots
└── README.md

