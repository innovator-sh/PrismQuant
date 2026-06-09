# PrismQuant — Premium Stock Intelligence Dashboard

> **See Beyond the Market**

PrismQuant is a Python-based stock intelligence dashboard that combines live market data, technical analysis, news insights, and statistical pattern discovery in a clean dark-themed interface.

---

## Features

| Feature | Description |
|----------|-------------|
| 📊 **Technical Analysis** | 50/200-day Moving Averages, breakout detection, and volatility scoring |
| 📰 **News Intelligence** | Live company news with sentiment analysis |
| 🧠 **AI Summary** | Data-driven market summaries |
| 📂 **CSV Upload** | Analyze custom stock datasets with automatic column detection |
| 🔍 **Deep Insights Engine** | Uncovers hidden patterns and market behavior |
| 📄 **PDF Export** | Export analysis reports as PDFs |
| 📈 **Interactive Charts** | Price charts with technical overlays |
| ⚡ **Live Market Strip** | Track major stocks and cryptocurrencies |
| 🗂️ **Multi-Page Interface** | Dashboard, Insights, Watchlist, News, and more |
| 🔄 **Responsive UI** | Background processing keeps the UI smooth |

---

## Deep Insights Engine

PrismQuant runs eight statistical analyses on historical price data:

- Day-of-Week Effect
- Monthly Seasonality
- Volume vs Price Signal
- Volatility Regime
- Overnight Gap Analysis
- Streak & Reversal Analysis
- Drawdown Profile
- Anomaly Detection

Results are presented as insight cards with supporting visualizations and sentiment labels.

---

## Getting Started

```bash
git clone https://github.com/innovator-sh/PrismQuant.git
cd PrismQuant

python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

pip install -r requirements.txt

python main.py
```

### Optional: Finnhub API Key

```bash
export FINNHUB_API_KEY="your_api_key_here"
```

Without a key, news-related features are disabled while all core analysis tools remain available.

---

## Tech Stack

- Python 3.10+
- CustomTkinter
- yfinance
- Finnhub API
- pandas & NumPy
- Matplotlib
- ReportLab

---

## Disclaimer

PrismQuant is for educational and informational purposes only and should not be considered financial advice.
