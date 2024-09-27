# Quantitative Momentum Strategy

This repository contains a quantitative momentum strategy implementation that uses stock data to compute momentum scores and determine optimal stock positions. The strategy is built using Python, with the IEX Cloud API to fetch real-time financial data and calculations for position sizing based on portfolio constraints.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Installation](#installation)
- [Usage](#usage)
- [Notebook Walkthrough](#notebook-walkthrough)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The quantitative momentum strategy is designed to analyze stock momentum by calculating various financial metrics such as return percentiles, price momentum, and volatility. These metrics are used to rank stocks and determine optimal positions for purchase, given a portfolio size.

The project implements:
- Fetching stock data in batches from IEX Cloud API.
- Calculating momentum scores based on price movements over time.
- Determining optimal position sizes for each stock.
- Building a detailed DataFrame for financial analysis.

## Key Features
- **Real-time Data Fetching**: Leverages the IEX Cloud API to retrieve up-to-date stock information in bulk.
- **Momentum Calculation**: Uses momentum scores to evaluate stock performance and potential returns.
- **Position Sizing**: Calculates position sizes based on portfolio constraints, ensuring proper risk management.
- **Comprehensive Data Analysis**: Constructs a detailed DataFrame with financial metrics like volatility, momentum, and return percentiles for informed decision-making.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shivamchaubey100/QuantitativeMomentumTrading.git
   ```
2. Navigate to the project directory:
   ```bash
   cd QuantitativeMomentumTrading
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Get an API key from [IEX Cloud](https://iexcloud.io/) and set it in your environment:
   ```bash
   export IEX_API_KEY='your_api_key'
   ```

## Usage
To run the notebook, open it in Jupyter:
```bash
jupyter notebook quantitative_momentum_strategy.ipynb
```
Follow the steps in the notebook to fetch stock data, calculate momentum scores, and determine optimal stock positions.

## Notebook Walkthrough
The notebook is structured into the following sections:
1. **API Setup**: Configuring and testing the IEX Cloud API.
2. **Data Fetching**: Fetching stock price data in batches.
3. **Momentum Calculation**: Calculating momentum scores and financial metrics.
4. **Position Sizing**: Calculating optimal stock position sizes based on the portfolio.
5. **Data Visualization**: Analyzing and visualizing key metrics for decision-making.
