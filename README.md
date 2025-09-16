Multi-Timeframe Stock Market Analysis (NIFTY50)

📊 Quantitative backtesting project on NIFTY50 intraday data (2023–2025) using Python, Excel, and TradingView (Pine Script). The goal: design and evaluate a systematic trading strategy that delivers returns better than the NIFTY50 index.

🚀 Project Overview

Collected and processed 5-minute OHLCV data for NIFTY50 stocks. Resampled into 10-minute and 15-minute datasets for multi-timeframe analysis. Implemented a trend-following strategy in Python, replicating Pine Script logic: Entry: Close crosses above EMA200 and EMA5 slope angle > 5°. Exit: Take-Profit +36% or Stop-Loss −16% (first touch intrabar). Evaluated performance against NIFTY50 index (buy & hold benchmark).

🛠️ Tools & Tech

Python (Pandas, NumPy, XlsxWriter, OpenPyXL) Excel (for reports and dashboards) TradingView (Pine Script) (for strategy validation) Jupyter Notebook (reproducible workflow)

📈 Key Performance Indicators

Total Profit & Loss (P&L) Max Drawdown (absolute & %) Number of Trades Profitable Trades % Profit Factor
