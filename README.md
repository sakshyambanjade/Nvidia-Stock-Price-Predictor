# Nvidia Stock Price Predictor

This is a simple stock price prediction project using Python. It uses historical stock data of Nvidia (NVDA) from Yahoo Finance and applies a linear regression model to predict the stock price for the next 30 days.

## Overview

- Downloads Nvidia stock data from January 2022 to April 2025 using the `yfinance` library.
- Uses only the 'Close' prices for analysis.
- Adds a 'Days' column to track the number of days since the start date.
- Fits a Linear Regression model using scikit-learn.
- Predicts and visualizes the next 30 days of stock prices.

## Technologies Used

- Python
- yfinance
- pandas
- matplotlib
- scikit-learn

## How to Run

1. Clone the repository:
2. 
```
git clone https://github.com/sakshyambanjade/Nvidia-Stock-Price-Predictor.git 
cd Nvidia-Stock-Price-Predictor

```

2. Install the required libraries:
```
pip install yfinance pandas matplotlib scikit-learn

```

3. Run the script:
```
python stock_price_predictor.py

```

## Notes

This is a basic example for learning purposes. It does not account for external factors or market changes. The model assumes linear trends which may not reflect actual stock behavior.
