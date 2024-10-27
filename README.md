# MLTradingBot
# 1. Trading Bot Development 💹

### 📄 Project Overview
- This AI-driven trading bot, developed using Lumibot and the Alpaca API, automates trading based on real-time market sentiment, leveraging FinBERT for sentiment analysis. By implementing bracket orders, it enhances risk management and optimizes profits, providing a robust solution for high-frequency trading.

### ✨ Features

- Sentiment Analysis: Uses FinBERT for real-time sentiment-based strategy adjustments.
- Risk Management: Implements stop-loss and take-profit with bracket orders.
- Backtesting: Extensive backtesting on historical data ensures reliability across various market conditions.

### ⚙️ Setup

 Clone the repository and navigate to the project directory.
 
 Install dependencies:
 
 bash
 
     pip install lumibot alpaca-finance transformers
 
 Configure <code>config.py</code> with your Alpaca API key and secret key.

### 🚀 Usage
Start the bot by running:

bash

    python trading_bot.py

### 📊 Backtest Results
Detailed backtest reports are available in the <code>backtest_results/</code> folder.
