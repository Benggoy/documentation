# 📁 Portfolio Import Guide - Moving from Seeking Alpha to RSI Tracker

## 🎯 Overview

This guide shows you how to transfer your Seeking Alpha portfolio symbols into your RSI Stock Tracker app using various methods.

## 🚀 Quick Start - Launch the New Version

```bash
# Navigate to your app directory
cd ~/Documents/Claude-Access

# Make the script executable
chmod +x launch_portfolio_import.sh

# Launch the enhanced app with portfolio import
./launch_portfolio_import.sh
```

## 📊 Method 1: Manual Portfolio List (Easiest)

### Step 1: Get Your SA Portfolio Symbols
1. Open your Seeking Alpha portfolio
2. Make a list of all your stock symbols
3. Example: AAPL, GOOGL, TSLA, MSFT, AMZN, etc.

### Step 2: Use Bulk Add Feature
1. In your RSI app, click **"📋 Bulk Add"** button
2. Enter symbols one per line:
```
AAPL
GOOGL
TSLA
MSFT
AMZN
NVDA
META
```
3. Click **"Add Stocks"**
4. Done! 🎉

## 📄 Method 2: CSV Import (Best for Large Portfolios)

### Option A: If Seeking Alpha Has Export
1. Go to your SA portfolio
2. Look for "Export", "Download", or "Settings" button
3. Export as CSV file
4. In RSI app, click **"📁 Import Portfolio"**
5. Select your CSV file

### Option B: Create Your Own CSV
1. Create a file called `my_portfolio.csv`
2. Add your symbols:
```csv
Symbol
AAPL
GOOGL
TSLA
MSFT
AMZN
NVDA
META
AMD
PLTR
COIN
```

3. Save the file
4. In RSI app, click **"📁 Import Portfolio"**
5. Select your CSV file

## 📝 Method 3: Text File Import

### Create a Simple Text File
1. Create `my_stocks.txt`
2. Add one symbol per line:
```
AAPL
GOOGL
TSLA
MSFT
AMZN
NVDA
META
AMD
PLTR
COIN
```

3. In RSI app, click **"📁 Import Portfolio"**
4. Select your text file

## 🔍 Method 4: Browser Copy-Paste (Creative)

### If SA Shows Symbols on Screen:
1. Open your SA portfolio
2. Select and copy all visible symbols
3. Paste into a text editor
4. Clean up the formatting (one symbol per line)
5. Save as text file
6. Import using Method 3

## 🛠 Sample Files Created for You

I've created sample files you can use as templates:

### Sample CSV Format (`sample_portfolio.csv`):
```csv
Symbol,Name
AAPL,Apple Inc
GOOGL,Alphabet Inc
TSLA,Tesla Inc
MSFT,Microsoft Corp
AMZN,Amazon.com Inc
```

### Sample Text Format (`sample_stocks.txt`):
```
AAPL
GOOGL
TSLA
MSFT
AMZN
```

## 💡 Pro Tips

### 🎯 Best Practices:
- Use the **Bulk Add** feature for small portfolios (< 20 stocks)
- Use **CSV Import** for large portfolios (> 20 stocks)
- Always validate symbols before importing
- Remove any duplicate symbols

### ⚡ Speed Tips:
- Copy symbols from SA and paste into Bulk Add dialog
- Use keyboard shortcuts (Ctrl+A, Ctrl+C, Ctrl+V)
- Keep a backup text file of your symbols

### 🔧 Troubleshooting:
- **Invalid symbols**: Check for typos or delisted stocks
- **Import fails**: Try different file format (CSV vs TXT)
- **Missing symbols**: Manually add any missed stocks

## 📈 After Import - What's Next?

### 1. **Verify Your Portfolio**
- Check that all symbols imported correctly
- Remove any invalid or unwanted symbols
- Add any missing stocks manually

### 2. **Explore New Features**
- View Market Cap data for portfolio weighting
- Monitor Daily Volume for trading opportunities
- Check Bid/Ask spreads for optimal entries
- Use RSI signals combined with volume data

### 3. **Set Up Seeking Alpha Links**
- Double-click any stock to open SA analysis
- Use "Seeking Alpha" button for quick access
- Research individual stocks while monitoring RSI

## 🔄 Staying Synced

### Manual Sync Process:
1. **When you buy new stocks**: Add them to RSI tracker
2. **When you sell stocks**: Remove from RSI tracker
3. **Periodic review**: Compare SA portfolio with RSI tracker
4. **Bulk updates**: Use import feature for major changes

### Future Enhancement Ideas:
- Automatic SA portfolio sync (if API becomes available)
- Portfolio value tracking
- Position size integration
- Performance analytics

## 📋 Sample Portfolio Templates

### Conservative Growth Portfolio:
```
AAPL
MSFT
GOOGL
JNJ
PG
KO
WMT
```

### Tech Growth Portfolio:
```
AAPL
GOOGL
MSFT
AMZN
TSLA
NVDA
META
AMD
CRM
SNOW
```

### Dividend Focus Portfolio:
```
JNJ
PG
KO
PEP
WMT
VZ
T
XOM
CVX
```

## 🆘 Need Help?

### Common Issues:
1. **App won't launch**: Check Python installation
2. **Import fails**: Verify file format and symbol validity
3. **Symbols not found**: Yahoo Finance may not have data
4. **Performance slow**: Reduce update frequency or stock count

### File Locations:
- App files: `~/Documents/Claude-Access/`
- Portfolio files: Save anywhere, import via file dialog
- Watchlist backup: `watchlist.json` (automatic)

---

## 🎉 Ready to Import Your Portfolio!

Choose the method that works best for you:
- **Quick & Easy**: Manual Bulk Add
- **Large Portfolio**: CSV Import  
- **Simple List**: Text File Import

Your RSI tracker will now show comprehensive financial data for all your Seeking Alpha portfolio stocks! 📈✨
