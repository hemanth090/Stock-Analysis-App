# Stock Analysis Application

A Streamlit-based web application for analyzing stock market data. This application allows users to fetch and visualize stock prices for any publicly traded company using their ticker symbol.

## Features

- Interactive stock price visualization using Altair charts
- Customizable date range selection
- Real-time data fetching using Yahoo Finance API
- Data table view with all stock information
- CSV export functionality
- Responsive layout with side-by-side chart and data view

## Prerequisites

Before running the application, make sure you have Python installed on your system. The application requires the following Python packages:

- streamlit
- yfinance
- altair
- pandas

## Installation

1. Clone this repository or download the source code.

2. Install the required packages using pip:
```bash
pip install streamlit yfinance altair pandas
```

## Usage

1. Run the application using Streamlit:
```bash
streamlit run stock.py
```

2. The application will open in your default web browser.

3. Enter a stock ticker symbol (e.g., AAPL for Apple, GOOGL for Google, MSFT for Microsoft)

4. Select your desired date range using the date pickers

5. Click "Fetch and Analyze Data" to view the stock information

6. The application will display:
   - An interactive line chart showing the stock's closing prices
   - A data table with detailed stock information
   - A download button to export the data as a CSV file

## Data Source

This application uses the Yahoo Finance API (via yfinance package) to fetch real-time stock market data.

## Example Ticker Symbols

- AAPL (Apple Inc.)
- GOOGL (Alphabet Inc.)
- MSFT (Microsoft Corporation)
- AMZN (Amazon.com Inc.)
- TSLA (Tesla Inc.)
- META (Meta Platforms Inc.)

## Note

The stock data is fetched in real-time, so the application requires an active internet connection to function properly. 
