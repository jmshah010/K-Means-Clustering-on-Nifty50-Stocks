# K-Means-Clustering-on-Nifty50-Stocks
This project applies K-Means clustering to stocks from the Nifty50 index (India’s top 50 companies) to identify groups of stocks with similar returns and volatility over time.  The analysis leverages financial data from Yahoo Finance and uses scikit-learn for clustering.


------------------------------------------------------------------------------------------------------------------------
🚀 Features
------------------------------------------------------------------------------------------------------------------------
Fetches 5 years of historical stock data from Yahoo Finance.
Calculates:

Daily returns
Mean return (average profitability)
Volatility (risk/standard deviation)
Applies K-Means clustering to group stocks based on risk-return profiles.
Visualizes stock clusters in 2D plots.


------------------------------------------------------------------------------------------------------------------------
📦 Dependencies
------------------------------------------------------------------------------------------------------------------------
The following Python libraries are required:
yfinance – Stock data
pandas – Data handling
numpy – Numerical operations
scikit-learn – K-Means clustering
matplotlib – Visualization


------------------------------------------------------------------------------------------------------------------------
📊 Example Output
------------------------------------------------------------------------------------------------------------------------
Scatter plot of stocks grouped into clusters based on volatility vs. returns.
Insights on risk-return tradeoff across different sectors.


------------------------------------------------------------------------------------------------------------------------
📈 Insights
------------------------------------------------------------------------------------------------------------------------
Low-volatility, high-return stocks cluster together → stable performers.
High-volatility, high-return stocks → risky growth bets.
High-volatility, low-return stocks → underperformers.

------------------------------------------------------------------------------------------------------------------------
🔮 Future Enhancements
------------------------------------------------------------------------------------------------------------------------
Add sector-based coloring for better interpretability.
Try Hierarchical Clustering or DBSCAN.
Include Sharpe Ratio as an additional feature.
Build a dashboard for interactive clustering.
