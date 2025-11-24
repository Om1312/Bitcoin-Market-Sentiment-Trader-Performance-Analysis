# Bitcoin-Market-Sentiment-Trader-Performance-Analysis

📌 Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trade data from Hyperliquid.
The goal is to understand how market mood impacts trading profitability and identify patterns that can be used to build better trading strategies.

📁 Files Included
1. bitcoin_sentiment_trader_performance_analysis.ipynb

Jupyter Notebook containing:

Data loading & cleaning

Feature engineering

Exploratory Data Analysis (EDA)

Visualizations

Insights

Strategy suggestions

2. fear_greed_index.csv

Daily Bitcoin market sentiment data.
Columns:

date, value, classification, timestamp

3. historical_data.csv

Trade-level dataset from Hyperliquid.
Contains:

Trade time

Coin traded

Buy/Sell information

Position sizes

Fees

Closed PnL

Account ID

🚀 How to Run the Notebook

Install the required libraries:

pip install pandas numpy matplotlib


Place all files in the same folder.

Open the notebook:

jupyter notebook


Run all cells (Kernel → Restart & Run All).

📊 Key Insights

Trader performance is highest during Fear and Extreme Fear days.

Greed days show lower PnL and more losses.

Sentiment value alone has a weak correlation with daily PnL.

Large profits often occur in 20–70 sentiment range.

Market sentiment can act as a filter to improve trading decisions.

🎯 How This Can Be Used

Build trading rules that increase activity during fear periods.

Reduce position sizes during Greed conditions.

Backtest sentiment-based entry filters.

Extend analysis using features like leverage, coin type, and volatility.

👤 Author

Om Laxman Khairnar
Aspiring Data Analyst | BCA Graduate
Email: Khairnarom1312@gmail.com
