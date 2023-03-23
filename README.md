# Financial Planning with APIs and Simulations

In this exercise the holdings and valuations of cryptocurrency and stocks & bonds within a portfolio were analyzed using APIs. Closing prices for Bitcoin and Ethereum were retrieved to evaluation the value of cryptocurrency while the valuations for SPY and AGG to evaluate the vale of stocks and bonds respectively. Closing prices were retrieved based on the specified time (08-07-2020) and were passed through a Pandas Dataframe. Portfolio Composition was analyzed as well by passing the savings_data list into the savings_df in order to highlight the holdings relative to each other.

A comparison between portfolio performances and valuations was then made by performing two separate Monte Carlo Simulations: one with atraditional 60/40 portfolio split: 60% stocks (SPY) and 40% bonds over a 30 year period and one with a riskier 80/20 portfolio split between stocks and bonds over a 10 year period.

The conclusions drawn from the analysis are detailed in the exercise.

## Technologies

This project leverages Python 3.7 (Jupyter Lab) and utilizes %matplotlib inline as well as the Pandas and NumPy libraries.

## Installation Guide

Import pandas, json, os, and requests from the Python library

From dotenv import load_dotenv

import alpaca_trade_api as tradeapi

From MCForecastTools import MCSimulation

%matplotlib inline

pip install python-dotenv

pip install alpaca-trade-api

Initiate Jupyter lab from the Gitbash Terminal

## Contributors

Kaushik Basavaraju
Email: kash.basavaraju@gmail.com

---

## License

MIT


