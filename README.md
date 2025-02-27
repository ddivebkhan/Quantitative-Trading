# Stock Analysis and Trading Strategy Project

This project analyzes historical stock data for Apple (AAPL) using Python and several popular data science libraries. It fetches stock data, calculates technical indicators, and implements a basic trading strategy.

## Project Overview

The project performs the following key tasks:

1.  **Data Fetching**: Retrieves Apple's historical stock data from Yahoo Finance using the `yfinance` library.
2.  **Moving Averages Calculation**: Calculates 20-day and 50-day moving averages to smooth out price fluctuations and identify trends.
3.  **Relative Strength Index (RSI) Analysis**: Computes the RSI, a momentum oscillator, to gauge overbought and oversold conditions.
4.  **Trading Strategy Implementation**: Develops a simple strategy that generates buy signals when the 20-day moving average crosses above the 50-day moving average, and the RSI is below 30. Sell signals are generated when the 20-day MA crosses below the 50-day MA, and the RSI is above 70.
5.  **Performance Evaluation**: Calculates and plots the cumulative returns of the strategy against the market to assess its performance.

## Libraries Used

The following Python libraries are used in this project:

*   `pandas`: For data manipulation and analysis using DataFrames.
*   `yfinance`: For fetching financial data from Yahoo Finance.
*   `matplotlib`: For creating visualizations such as line plots of price data, moving averages, RSI, and trading signals.
*   `numpy`: For numerical operations.
*   `scipy`: For scientific and technical computing, although only the `linregress` function was used, although not displayed in the output.

## Project Structure

The project is contained within a single Jupyter Notebook file. The notebook is structured into the following sections:

*   **Fetching Financial Data**: Downloads historical stock data for Apple (AAPL).
*   **Calculating Moving Averages**: Computes and plots 20-day and 50-day moving averages.
*   **Analyzing Momentum with RSI**: Calculates and plots the Relative Strength Index (RSI).
*   **Trading Strategy**: Implements a trading strategy based on moving averages and RSI, then plots buy and sell signals.
*   **Performance Evaluation**: Calculates and plots the cumulative strategy returns against the market returns.

## How to Run the Project

1.  **Install Libraries**: Ensure you have the required libraries installed. You can install them using !pip install

## Key Concepts

*   **Moving Averages (MA)**: Used to smooth out price data and identify trends.
*   **Relative Strength Index (RSI)**: A momentum indicator used to identify overbought and oversold conditions.
*   **Trading Strategy**: A set of rules for making buy and sell decisions.
*   **Cumulative Returns**: The total returns of an investment over time, calculated by multiplying the daily returns and adding them to the previous day's total return.

## Notes

*   This is a simplified analysis and trading strategy for demonstration purposes. It does not take into account transaction costs, taxes, or other real-world factors.
*   The performance of the trading strategy is dependent on the selected parameters and market conditions and might not be profitable.
