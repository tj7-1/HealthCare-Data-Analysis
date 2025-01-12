**Crypto Data Fetcher and Trend Analyzer**
What’s This About?
This is a Python project that helps you fetch, analyze, and visualize real-time cryptocurrency data from the CoinMarketCap API. Whether you’re a crypto enthusiast, investor, or just curious about the market, this tool simplifies the process of gathering data and understanding trends.

**What Can It Do?**
🚀 Fetch Real-Time Crypto Data
Get up-to-date information for the top cryptocurrencies, including prices and percentage changes over different time frames.

📊 Analyze Trends
See how cryptocurrencies perform over time (1 hour, 24 hours, 7 days) and identify patterns.

🕒 Track Historical Prices
Plot the price movement of your favorite cryptocurrency (e.g., Bitcoin) over time.

📂 Save Your Data
Export everything to a CSV file so you can analyze it later or share it with friends.

**What’s in the Code?**
fetch_crypto_data()
Grabs cryptocurrency data from the CoinMarketCap API. Think of this as the "data collector."

normalize_data(data)
Cleans up the raw data and organizes it into a neat table.

append_data(df, new_data)
Combines new data with what you’ve already collected.

run_api_loop()
Runs the data collector repeatedly. By default, it collects data every minute for 10 runs (you can change this).

save_to_csv(df)
Saves all your collected data into a CSV file so you can use it later.

analyze_trends(df)
Groups the data to calculate average percent changes over specific time periods (like 1 hour, 24 hours, and 7 days).

plot_trends(df)
Creates a chart showing how cryptocurrencies are performing over different time frames.

plot_price_over_time(df, coin_name)
Draws a chart of the price history for the cryptocurrency you’re interested in (default is Bitcoin).

**What You’ll Get**
Trend Analysis
A chart showing how different cryptocurrencies have changed over various time periods.

Historical Price Plot
A line graph of price movements for a specific cryptocurrency, like Bitcoin.

CSV Export
All the data saved in an easy-to-read file format.

