# 📈 Reddit-Powered NLP based Trading Simulator Bot

A Python-based trading bot that simulates stock trading decisions based on sentiment analysis of live Reddit posts from subreddits like [r/wallstreetbets](https://www.reddit.com/r/wallstreetbets), [r/stocks](https://www.reddit.com/r/stocks), and [r/stockmarket](https://www.reddit.com/r/stockmarket). The bot fetches posts in real-time, analyzes their sentiment using NLP techniques, and makes buy/sell decisions in a simulated trading environment.

---

## 🚀 Features

- 🔍 Scrapes Reddit posts in real-time using the Reddit API (PRAW)
- 🧠 Uses `VADER Sentiment Analysis` to evaluate bullish/bearish sentiment
- 💰 Simulates buying/selling stocks using real-time price data from `yfinance`
- 📊 Stores historical trading data and decisions
- 💾 Saves and resumes trading sessions across runs
- 📉 Tracks portfolio value and logs trades in a readable format

---
