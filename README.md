# binance-trade-analysis
Binance trade data analysis, ranking top-performing accounts using financial metrics.

Binance Trade Analysis & Account Ranking 🚀

Overview

This project analyzes Binance trading data over a 90-day period to evaluate account performance. Key financial metrics were calculated, and accounts were ranked based on their overall performance.

Objective
The goal was to:

✅ Clean and preprocess the provided dataset.

✅ Calculate key financial metrics for each account.

✅ Develop a ranking algorithm to identify the top 20 accounts.

✅ Present insights through a detailed report.

Dataset Information
The dataset contains Binance trade data with details such as:

Port_IDs: Unique account identifiers
Trade_History: Historical trade details like timestamps, asset type, side (BUY/SELL), and prices

realizedProfit: Indicates profit or loss for each trade

Metrics Calculated

The following financial metrics were calculated for each account:

ROI (Return on Investment)

PnL (Profit and Loss)

Sharpe Ratio

Maximum Drawdown (MDD)

Win Rate

Win Positions

Total Positions

Ranking Algorithm

Accounts were ranked based on a weighted scoring system:

ROI → 30%

Sharpe Ratio → 30%

Win Rate → 20%

PnL → 10%

MDD (Risk) → -10% (negative weight as lower values are better)


Insights & Results
📊 Identified the top 20 performing accounts based on profitability, risk-adjusted returns, and efficiency.
📈 The analysis provides valuable insights for identifying high-performing traders.
