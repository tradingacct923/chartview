# Tick Viewer 📊

A **TradingView-style** candlestick chart viewer that runs entirely in your browser. Upload any tick data or OHLCV CSV file and instantly visualize it with professional-grade charting.

![Tick Viewer](https://img.shields.io/badge/Charts-Lightweight_Charts_v4.1-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## Features

- 🕐 **8 Timeframes**: 1s, 5s, 30s, 1m, 5m, 15m, 1H, 4H
- 📊 **Candlestick + Line** chart modes
- 📈 **Volume histogram** with green/red coloring
- 🎯 **Crosshair** with OHLCV overlay
- 🌙 **Dark theme** matching TradingView
- 🔒 **100% client-side** — your data never leaves your browser
- 📁 **Drag & drop** CSV upload
- 🔄 **Auto-detect format** — works with NinjaTrader, TradingView, and generic OHLCV CSVs

## Supported CSV Formats

### NinjaTrader Tick Data
```
DateTime,Type,Price,Bid,Ask,Volume
2026-03-02 00:00:00.024000,Last,5368.50,5368.50,5368.60,1
```

### TradingView Export
```
time,open,high,low,close,Volume
2026-03-02T00:00:00,5368.50,5370.00,5365.20,5369.80,1234
```

### Generic OHLCV
```
timestamp,open,high,low,close,vol
1709337600,5368.50,5370.00,5365.20,5369.80,1234
```

## Keyboard Shortcuts

| Key | Timeframe |
|-----|-----------|
| 1 | 1 second |
| 2 | 5 seconds |
| 3 | 30 seconds |
| 4 | 1 minute |
| 5 | 5 minutes |
| 6 | 15 minutes |
| 7 | 1 hour |
| 8 | 4 hours |

## Deploy Your Own

This is a single static HTML file. Deploy it anywhere:
- **Render**: Static Site → point to this repo
- **GitHub Pages**: Enable in repo settings
- **Netlify**: Drag & drop

## Tech Stack

- [Lightweight Charts](https://github.com/nicenshtein/lightweight-charts) v4.1 by TradingView
- Vanilla JavaScript (no frameworks)
- Inter font from Google Fonts
