# Crypto Market Analysis

## Overview
An automated data pipeline that pulls live cryptocurrency market data 
from the CoinMarketCap API, stores it over time, and visualizes 
price trends and percentage changes across multiple timeframes.

## Features
- Automated API calls using a scheduled loop
- Data appended to CSV for time-series tracking
- Percentage change analysis across 1h, 24h, 7d, 30d, 60d, 90d
- Price trend visualization using Seaborn and Matplotlib

## Tools & Technologies
- Python (requests, json, pandas, seaborn, matplotlib)
- CoinMarketCap API
- Jupyter Notebook

## How to Run
1. Get a free API key from coinmarketcap.com
2. Replace `YOUR_API_KEY_HERE` in the code with your key
3. Run all cells in the Jupyter notebook
4. Adjust `range()` and `sleep()` values for longer data collection

## Notes
For meaningful price trend visualization, run the API loop 
with longer intervals (e.g. range(333), sleep(60)) to collect 
data over several hours.

## Author
Ahmed Salem
