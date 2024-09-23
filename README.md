"# Derivative Pricing with Black-Scholes-Merton" 


Project Overview:

This project focuses on building a pricing model for European-style options using the Black-Scholes-Merton (BSM) model. The primary goal is to develop a robust framework for pricing options, conduct sensitivity analysis using Greeks, and explore extensions to the basic BSM model for more realistic pricing scenarios. The project also generates synthetic stock and options data using a Geometric Brownian Motion (GBM) process to simulate stock price movements.

Key Features:

Stock Price Simulation: Uses Geometric Brownian Motion (GBM) to generate synthetic stock prices for 252 trading days in a year.

Option Pricing: Implements the Black-Scholes-Merton formula for both European call and put options, using synthetic stock data.

Volatility Smile: Simulates implied volatility using a volatility smile for different strike prices, reflecting real market conditions.

Option Greeks: Calculates and visualizes the key option Greeks (Delta, Gamma, Vega, Theta, Rho) to understand the sensitivity of option prices.

Dataset Creation: Generates and saves synthetic stock and option data for  analysis.


Technologies Used:

Python
NumPy, SciPy
Matplotlib for visualizations
Pandas for data manipulation
Jupyter Notebook
