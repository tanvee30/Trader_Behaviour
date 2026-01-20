# Trader_Behaviour
This project analyzes historical trader data to understand trading behavior, performance, and patterns under different market sentiment conditions (Fear & Greed Index).

The analysis focuses on:

Core trader metrics (as required in the assignment)
Trader behavior patterns (buy vs sell, holding vs frequent trading)
Performance analysis (PnL, win rate)
Impact of market sentiment on trading decisions and outcomes


Dataset Used

The project uses two CSV files:

1.historical_data.csv
 Trade-level data including:
 Side (BUY / SELL)
 Size USD
 Size Tokens
 Execution Price
 Fee
 Closed PnL
 Timestamp (IST)

2.fear_greed_index.csv
 Daily market sentiment data with:
 Date
 Fear & Greed value
 Classification (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)


Tools & Libraries
 Python
 Pandas
 NumPy
 Matplotlib

Assignment Requirements:
The following basic trader metrics were calculated as required:

Total volume traded (USD)
Total tokens bought and sold
Weighted average buy price
Total fees paid
Number of BUY vs SELL trades
Holding vs frequent trading behavior
Measured using average time gap between trades
These metrics form the core of the assignment.

Additional Analysis:
🔹 Sentiment-Based Analysis

Merged trader data with Fear & Greed Index using trade date
Trade distribution across sentiment categories
Buy vs Sell behavior under different sentiments
Total traded volume by sentiment

🔹 Performance Metrics

Total PnL
Average and median PnL per trade
Win rate (% profitable trades)
Win rate by market sentiment
Average PnL by sentiment

🔹 Visualizations

Win rate vs market sentiment
Average PnL across sentiment categories
Trade activity distribution across sentiments

These visualizations help identify how trader performance changes under different market emotions.