# Real-Time Cryptocurrency Market Analysis Using CoinMarketCap API
This project provides a real-time data pipeline and analysis for cryptocurrency markets, leveraging the CoinMarketCap API to extract, process, and visualize data trends. The code captures the latest metrics for the top 15 cryptocurrencies, including price changes across various time frames (1 hour, 24 hours, 7 days, 30 days, 60 days, and 90 days) and appends the data to a CSV file to maintain a historical record.

# Key Features:
Data Extraction: The script extracts data in real-time from the CoinMarketCap API at intervals and stores it in CSV format for future analysis.
Data Processing: After collection, data is normalized and aggregated to track each cryptocurrency's percent change over different intervals.
Visualization: The project uses Seaborn and Matplotlib to generate insightful visualizations:
A comparative line plot for percent change across different timeframes for the top cryptocurrencies.
A time-series line chart tracking Bitcoin's price movements over time.
This project is ideal for monitoring market trends, performing data-driven predictions, and aiding in cryptocurrency analysis. The use of Python, pandas, and visualization libraries makes it accessible and extensible, while CoinMarketCap’s real-time API ensures the information is up-to-date.
