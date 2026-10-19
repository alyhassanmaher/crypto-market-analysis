# Crypto Market Analysis

Exploratory analysis of the cryptocurrency market in Python, built for the Introduction to Artificial Intelligence course at ESLSCA University (FinTech major).

## What it does
- Loads and cleans a market dataset of cryptocurrencies, converting price and market-cap strings to numbers
- Groups coins into price bands ($0–1, $1–10, $10–100, $100–1,000, over $1,000) and charts the distribution
- Ranks the top 10 coins by market capitalisation
- Checks the dataset for missing values
- Pulls daily closing prices for **BTC, ETH, BNB, SOL and XRP** from Yahoo Finance (Jan 2023 – Mar 2024) and maps how their prices move together in a correlation heatmap

## Tech
Python · pandas · NumPy · matplotlib · seaborn · yfinance · Jupyter

## Run
```bash
pip install -r requirements.txt
jupyter notebook crypto_market_analysis.ipynb
```
The notebook reads `CryptocurrencyData.csv`, which isn't included in this repo. Place a copy next to the notebook before running it. The Yahoo Finance section works without it.
