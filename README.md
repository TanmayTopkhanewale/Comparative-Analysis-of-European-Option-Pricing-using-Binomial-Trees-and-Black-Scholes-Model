# Comparative-Analysis-of-European-Option-Pricing-using-Binomial-Trees-and-Black-Scholes-Model
European Option Pricing Models in Python Implements and compares Black-Scholes and Binomial Tree models for pricing European options. Includes sensitivity analysis, real market data (JPM, HPQ, AAPL), and pricing error visualization using Yahoo Finance.
# European Option Pricing Models: Black-Scholes vs Binomial Tree

This repository contains a Python-based quantitative finance project that implements and compares two widely-used methods for pricing European-style vanilla options:

- Black-Scholes Model (closed-form analytical solution)
- Binomial Tree Model (numerical step-based approximation)

The models are applied to real market data for selected US equities, including JPMorgan Chase (JPM), HP Inc. (HPQ), and Apple Inc. (AAPL). The project includes pricing accuracy comparisons, sensitivity analysis, and convergence evaluation.

---

## Objectives

- Implement pricing logic for European call and put options using both Black-Scholes and Binomial Tree models
- Analyze the mathematical assumptions and computational properties of each method
- Evaluate sensitivity of option prices to key parameters such as volatility, strike price, time to maturity, and risk-free rate
- Compare model outputs to real option market prices fetched via Yahoo Finance
- Draw insights into model performance under different conditions

---

## Key Features

- Black-Scholes and Binomial Tree implementations in Python
- Sensitivity analysis for volatility, time to maturity, strike price, and interest rate
- Visualization of model outputs and error plots against market data
- Real-time option chain data retrieval using yfinance
- Convergence analysis of Binomial Tree to Black-Scholes model
- Clean, modular code with plotting utilities

---

## Requirements

- Python 3.8+
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - yfinance
  - datetime

