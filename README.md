# **Value at Risk (VaR)** Analysis of Nifty50 Portfolio

This project provides a comprehensive **Value at Risk (VaR)** analysis for an equally weighted portfolio of Nifty50 stocks. The analysis is performed using three widely accepted methods: Variance-Covariance, Historical Simulation, and Monte Carlo Simulation. The project is implemented in Python and leverages daily adjusted closing prices sourced from Yahoo Finance.

# **Project Overview**

## Objective: Quantify the market risk of a Nifty50 portfolio using VaR.

## Portfolio: Equally weighted, comprising all available Nifty50 stocks.

## Data Source: Yahoo Finance (daily adjusted close prices).

## Analysis Period: 2023-08-29 to 2024-08-29.

# **VaR Methods:**

1. Variance-Covariance
2. Historical Simulation
3. Monte Carlo Simulation

# **Features**

1. Robust handling of ticker failures—stocks with missing data are excluded automatically.
2. Calculation of daily returns for each stock.
3. Construction of an equally weighted portfolio.
4. VaR calculation at user-defined confidence levels.
5. Visualization of Monte Carlo results using Matplotlib.
