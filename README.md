# Extracting and Visualizing Stock Data

**Short Description:**  
A Python project to extract, clean, and visualize historical stock and revenue data for companies like Tesla and GameStop using interactive graphs.

## Features
- Extract historical stock prices using `yfinance`
- Web scrape quarterly revenue data from online sources
- Clean and preprocess data for visualization
- Plot interactive graphs comparing stock prices and revenue trends
- Reusable `make_graph` function for dual-axis stock and revenue charts

## Technologies Used
- Python 3.x
- yfinance
- BeautifulSoup4
- pandas
- Plotly
- HTML5lib

## Structure
1. **Graphing Function** – Defines `make_graph` for stock vs revenue visualization
2. **Stock Data Extraction** – Using `yfinance` for Tesla and GameStop
3. **Revenue Data Extraction** – Web scraping quarterly revenue tables
4. **Visualization** – Interactive Plotly graphs for Tesla and GameStop
