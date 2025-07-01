# 📊 NIFTY 50 Tariff Impact Analysis

This project explores how tariff events impact NIFTY 50 stock prices and sectors. We simulate trade war scenarios and analyze their effect on overall index trends, volatility, sectors, and sentiment using Python and data visualization tools.

---

## 🚀 What We Did

### 1. 📥 Data Collection (`01_get_stock_data.ipynb`)
- Collected daily close prices (Jan–Apr 2025) for all NIFTY 50 stocks using `yfinance`.
- Simulated 3 **tariff events** (e.g., US imposing tariffs, India retaliating).
- Saved clean datasets for analysis.

### 2. 📉 Visual Analysis (`02_visualize_tariff_impact.ipynb`)
- Plotted **NIFTY 50 average close price** with vertical lines for tariff dates.
- Measured **price changes before vs after** events (e.g., -2.18% after April 1 tariff).
- Analyzed **volatility spikes** around events.
- Compared **sector-wise performance** (Tech, Auto, Energy, etc.)—normalized for comparability.

### 3. 💬 Sentiment vs Market Reaction (`03_sentiment_vs_market.ipynb`)
- Created mock news headlines around event dates.
- Used **VADER Sentiment Analysis** to assign scores to headlines.
- Plotted **sentiment scores vs actual market % change**.
- Found weak to moderate correlation: some strongly negative sentiment led to stronger market drops.

### 4. 📘 Summary & Insights (`04_summary.ipynb`)
- Compiled conclusions and decisions based on data :
  - **Some sectors like FMCG and Energy remained resilient**.
  - **Market volatility rose post-events**, showing investor uncertainty.
  - Sentiment gives partial but useful context.

---

## 🔍 Key Insights

- 📉 **April 1st tariff escalation** led to the largest drop (-2.18%) in NIFTY 50 average.
- 📈 **Auto and Tech sectors** were hit harder; FMCG and Energy stayed relatively stable.
- 💬 Public sentiment mostly aligned with direction of market reaction but not magnitude.

---

## 💡 Future Plan

This analysis is the foundation for building an interactive AI-powered portfolio advisor:

- 📊 **Streamlit Frontend**: Explore impact on sectors, individual stocks.
- 🧠 **FastAPI Backend**: Use our findings to:
  - Analyze how your portfolio stocks reacted to trade events.
  - Suggest which stocks to **hold** vs **let go** based on historical reactions.
- 🧾 Extend to real news headlines and live sentiment APIs (Twitter, NewsAPI).

---

## 🛠️ Tech Stack

- Python · Pandas · Matplotlib · Seaborn
- VADER Sentiment · Streamlit (planned) · FastAPI (planned)

---

## 👩‍💻 Author

**Samradhi Sharma**  
Feel free to connect or contribute!
