## 🪙 Real-Time Cryptocurrency Tracker

This project is a Python-based Cryptocurrency Tracker that fetches live market data using the **CoinGecko API** and provides visual insights into price trends and market volatility.

## 🚀 Features
- **Live Data Retrieval**: Fetches the top 10 cryptocurrencies by market capitalisation.
- **Data Analysis**: Processes raw JSON data into a clean, readable Pandas DataFrame.
- **Price Comparison**: Visualises current prices using a Log-Scale bar chart to handle the vast price difference between assets like Bitcoin and stablecoins.
- **Market Sentiment**: Analyses 24-hour price changes with colour-coded visualisation (Green for gains, Red for losses).

## 🛠️ Tech Stack
- **Python**: Core programming language.
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib & Seaborn**: Data visualization.
- **Requests**: Interacting with the CoinGecko REST API.

## 📋 Prerequisites
To run this notebook locally or in Colab, ensure you have the following libraries installed:
pip install requests pandas matplotlib seaborn.

## 📊 Usage
Run the data retrieval cell to fetch the latest market stats.
View the generated table for a snapshot of Price and Market Cap.
Run the visualisation cells to view current market trends.

## Disclaimer: This tool is for educational purposes only and does not constitute financial advice. 
