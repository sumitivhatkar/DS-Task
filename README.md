Project Overview

This project explores the relationship between trader performance and Bitcoin market sentiment using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.
The goal is to uncover hidden patterns, analyze trader behavior, and provide actionable insights that can contribute to smarter trading strategies.

Dataset Sources

Trader Historical Data: Provided by Hyperliquid

Bitcoin Fear & Greed Index: Market sentiment data provided in the assignment

Technologies Used

Python

Pandas

NumPy

Seaborn

Matplotlib

Jupyter Notebook

Key Steps
Data Cleaning & Preprocessing:

Converted timestamps to uniform datetime format

Merged datasets using nearest previous sentiment date with merge_asof

Feature Engineering:

Classified trades as wins or losses

Calculated daily and overall performance metrics per sentiment

Visualization:

Boxplots to analyze PnL distribution by sentiment

Bar plots for win rate and fee comparison

Line plots for daily PnL trends

Insights:

Trader performance is influenced by market sentiment

Win rates, fees, and average trade sizes vary across sentiment states

Traders tend to perform differently on Greed vs. Fear days

Visualizations
PnL Distribution by Sentiment

Win Rate Comparison

Average Fee by Sentiment

Daily PnL Trends

Files Included
DS_Task.ipynb – Full analysis notebook

trader_data.csv – Trader historical dataset

sentiment_data.csv – Fear & Greed Index dataset
