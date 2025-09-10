# Stock & Revenue Analysis

## Project Overview
This project extracts and analyzes historical stock prices and revenue data for major companies such as **Tesla**, **GameStop**, and **Amazon**.  
The analysis includes:  
- Downloading stock data using the `yfinance` library.  
- Extracting revenue data from HTML web pages using `requests` and `BeautifulSoup`.  
- Cleaning and structuring data using `pandas`.  
- Displaying key stock and revenue information for further analysis.  

## Data Sources
- Historical stock prices from [Yahoo Finance](https://finance.yahoo.com/).  
- Quarterly revenue data from company-specific web pages.  

## Libraries Used
- `pandas` – for data manipulation and analysis  
- `yfinance` – for downloading stock price data  
- `requests` – for downloading web pages  
- `BeautifulSoup` – for parsing HTML content  

## Instructions
1. Open the Jupyter Notebook `stocks_revenue.ipynb`.  
2. Run each cell sequentially to download, parse, and display stock and revenue data.  
3. Review the extracted DataFrames:  
   - `amazon_data` – Amazon stock prices  
   - `tesla_data` – Tesla stock prices  
   - `tesla_revenue` – Tesla quarterly revenue  
   - `gme_data` – GameStop stock prices  
   - `gme_revenue` – GameStop quarterly revenue  
