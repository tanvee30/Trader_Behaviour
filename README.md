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


Trading Insights:
1.Traders perform worst during extreme emotions
When the market is in Extreme Fear or Extreme Greed, traders lose more and win less.

2.Best performance happens in normal conditions
Trades made during Fear or Greed (not extreme) have better win rates and higher average profits.

3.Too much trading during Extreme Greed
Traders place more trades during Extreme Greed, but profits do not increase—this shows overconfidence.

4.Fear leads to cautious trading
During Extreme Fear, traders reduce trade size and frequency, often missing good opportunities.

5.Buy and sell behavior changes with sentiment
More BUY trades happen during Fear, while more SELL trades happen during Greed.

6.Higher activity does not mean higher profit
Periods with the most trades do not always generate the best returns.

7.Sentiment affects behavior more than price
Market sentiment influences how traders act, not just market direction.

Simple Trading Strategy (Based on Insights)

1.Avoid heavy trading during Extreme Fear & Extreme Greed
2.Trade normally during Fear and Greed
3.Reduce position size during emotional market phases
4.Use sentiment as a risk control tool, not a buy/sell signal

Trading works best when emotions are controlled and sentiment is used to manage risk, not chase profits.