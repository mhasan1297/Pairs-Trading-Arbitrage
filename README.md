# Pairs Trading Strategy

This repository contains a Python implementation of a pairs trading strategy based on cointegration analysis. The strategy focuses on two stocks, applying a rolling window for calculations and simulating trading decisions over historical data.

## Overview

Pairs trading is a statistical arbitrage strategy that involves identifying two stocks whose prices are cointegrated. Cointegration implies a long-term relationship between the stock prices, allowing for the identification of potential trading opportunities.

The code uses the following main components:

- Data retrieval using the Yahoo Finance API.
- Cointegration analysis to determine the relationship between two stocks.
- Simulation of trading decisions based on cointegration parameters.
- Calculation and tracking of gross and net returns over time.

## Dependencies

- `numpy`
- `pandas`
- `yfinance`
- `statsmodels`
- `scipy`
- `matplotlib`

Install dependencies using:

```bash
pip install numpy pandas yfinance statsmodels scipy matplotlib
