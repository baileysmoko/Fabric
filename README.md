# Systematic Crypto Trading Research

This repository contains all research, code, and analysis developed during my quantitative research internship.  
The project spans data engineering, single-asset strategies, statistical arbitrage, and regime-adaptive portfolio construction.

---

## 📊 Data Pipelines

### Top 100 Coin Universe
Identifies all cryptocurrencies that appeared in the Top 100 by market cap over a rolling 31-day window.
- `Top_100_coins.ipynb`

### Dune Analytics Dataset
Downloads large Dune Analytics query results, stores them as Parquet shards, and queries them using DuckDB.
- `Dune_Dataset.ipynb`

All datasets are stored in a centralized Google Drive folder:
👉 **https://drive.google.com/drive/folders/1dFicbmTXsIMf2f33rj8bo4AarItNmatN**

---

## 📈 Trading Strategies

### 1. Momentum Strategy
EMA(20/50) crossover, long-only trend following.
- `LTC_Momentum_strategy.ipynb`
- Report: *https://fabricinvest.atlassian.net/wiki/x/AYA9Ag*

### 2. Donchian Channel Breakout
Long-only breakout strategy applied across the crypto universe.
- `Donchian_Channel_breakout_strategy.ipynb`
- Report: *https://fabricinvest.atlassian.net/wiki/x/AQAcAw*

### 3. Statistical Pairs Trading
Cointegration-based mean-reversion with walk-forward validation.
- `Mean_Reversion_Pairs_Trading.ipynb`
- Report: *https://fabricinvest.atlassian.net/wiki/x/EAA-B*

### 4. Regime-Adaptive Portfolio
Multi-asset portfolio with regime detection and dynamic allocation.
- `Final_Portfolio_Strategy.ipynb`
- Report: *https://fabricinvest.atlassian.net/wiki/x/AYAsBg*

---

## 🧠 Key Themes
- Survivorship-bias-free universe construction
- Out-of-sample and walk-forward validation
- Risk-aware portfolio design
- Institutional quantitative research methodology

---

## ⚠️ Disclaimer
This repository is for research and educational purposes only.  
Nothing herein constitutes investment advice.
