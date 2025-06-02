# 📈 RSI Stock Tracker - Quick Start Guide

## 🚀 How to Run Your RSI Tracker

### Option 1: Quick Launch (Recommended)
```bash
chmod +x launch_rsi_tracker.sh
./launch_rsi_tracker.sh
```

### Option 2: Manual Setup
```bash
# Install dependencies
pip3 install -r requirements_rsi.txt

# Run the application
python3 rsi_tracker_app.py
```

## 📊 How to Use the App

### Adding Stocks
1. Type any stock symbol (AAPL, GOOGL, MSFT, TSLA, etc.) in the input field
2. Click "Add" or press Enter
3. The app will validate the symbol and start tracking it

### Understanding RSI Values
- **🔴 Overbought (RSI > 70)**: Stock may be overvalued, consider selling
- **🟡 Neutral (RSI 30-70)**: Normal trading range, monitor trends
- **🟢 Oversold (RSI < 30)**: Stock may be undervalued, consider buying

### Features
- ✅ **Real-time updates** every 30 seconds
- ✅ **Persistent watchlist** - your stocks are saved
- ✅ **Price change tracking** with $ and % changes
- ✅ **Professional RSI calculation** using 14-period standard
- ✅ **Dark theme** for comfortable viewing

### Popular Stock Symbols to Try
- **AAPL** - Apple Inc.
- **GOOGL** - Alphabet (Google)
- **MSFT** - Microsoft
- **TSLA** - Tesla
- **AMZN** - Amazon
- **NVDA** - NVIDIA
- **META** - Meta (Facebook)
- **SPY** - S&P 500 ETF

## ⚠️ Important Notes

- **Educational Purpose**: This is for learning and analysis only
- **Not Investment Advice**: Always do your own research
- **Internet Required**: App needs internet for real-time data
- **Rate Limits**: Yahoo Finance may limit requests during heavy usage

## 🔧 Troubleshooting

### If app won't start:
```bash
# Check Python version (need 3.8+)
python3 --version

# Install missing dependencies
pip3 install yfinance pandas numpy

# Run with error output
python3 -v rsi_tracker_app.py
```

### If stocks won't load:
- Check your internet connection
- Verify stock symbol exists on Yahoo Finance
- Try again in a few minutes (rate limiting)

## 📚 What is RSI?

**RSI (Relative Strength Index)** is a momentum oscillator that measures the speed and change of price movements:

- **Range**: 0 to 100
- **Overbought**: Above 70 (stock may decline)
- **Oversold**: Below 30 (stock may rise)
- **Neutral**: 30-70 (normal range)

RSI helps traders identify potential reversal points, but should be used with other analysis tools.

---

**Happy Trading! 📈**

*Remember: Past performance doesn't guarantee future results. Trade responsibly!*
