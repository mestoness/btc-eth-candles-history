# BTC & ETH Perpetual Futures OHLCV Data (Bybit)

This repository contains **historical OHLCV data** for **BTCUSDT** and **ETHUSDT**
**Perpetual Futures (PERP)** markets, fetched directly from **Bybit**.

The dataset is suitable for:
- Algorithmic trading
- Strategy backtesting
- Quantitative research
- Market structure analysis
- Machine learning & time-series modeling

---

## 📊 Included Markets

- **BTCUSDT Perpetual**
- **ETHUSDT Perpetual**

**Exchange:** Bybit  
**Market Type:** USDT-M Perpetual Futures

---


## ⏱ Timeframe Mapping

| File Suffix | Timeframe |
|------------|-----------|
| `15`  | 15 Minutes |
| `30`  | 30 Minutes |
| `60`  | 1 Hour |
| `240` | 4 Hours |
| `D`   | 1 Day |
| `W`   | 1 Week |
| `M`   | 1 Month |

---

## 📊 Data Fields

Each CSV file contains the following columns:

| Field | Description |
|------|------------|
| `timestamp` | Candle open time (UTC, milliseconds) |
| `open` | Open price |
| `high` | High price |
| `low` | Low price |
| `close` | Close price |
| `volume` | Traded volume (base asset) |
| `turnover` | Traded value (USDT) |

---
