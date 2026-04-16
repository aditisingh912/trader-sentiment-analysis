#  Trader Performance vs Market Sentiment Analysis

## Objective

The goal of this project is to analyze how market sentiment (Fear vs Greed) influences trader behavior and performance on the Hyperliquid platform. The analysis aims to uncover patterns that can inform better trading strategies.

---

##  Datasets Used

### 1. Bitcoin Market Sentiment Dataset

 Columns: `date`, `classification`
 Categories: Fear, Greed

### 2. Historical Trader Data (Hyperliquid)

Includes: account, execution price, size, side, timestamp, closed PnL, etc.

---

##  Data Preparation

 Cleaned column names (converted to lowercase and snake_case)
Parsed timestamps using `DD-MM-YYYY HH:MM` format
 Extracted date from timestamp for alignment
 Merged datasets on `date`
 Filtered sentiment into two categories: **Fear** and **Greed**

---

##  Key Metrics Created

 **PnL (Profit & Loss)**: Closed profit per trade
 **Win Rate**: Percentage of profitable trades
 **Trade Frequency**: Number of trades per sentiment
 **Trade Size (USD)**: Proxy for risk-taking behavior
 **Long/Short Ratio**: Market direction bias

---

##  Analysis & Findings

### 1. Performance vs Sentiment

Trader profitability differs between Fear and Greed periods
 Greed periods often show higher activity but inconsistent returns

###  2. Behavioral Changes

 Traders increase trade size during Greed → higher risk exposure
 Fear periods show more cautious trading behavior

###  3. Win Rate Trends

 Win rate tends to decline during Greed → possible overtrading
 Fear periods show relatively stable outcomes

---

##  Key Insights

 Market sentiment significantly impacts trading decisions
 Overconfidence during Greed leads to increased risk and lower efficiency
 Conservative behavior during Fear helps limit losses

---

##  Strategy Recommendations

###  Strategy 1: Risk Control in Fear

 Reduce trade size
 Focus on high-confidence trades

### ✅ Strategy 2: Avoid Overtrading in Greed

 Limit number of trades
 Apply strict stop-loss mechanisms

###  Strategy 3: Adaptive Trading

 Adjust position sizing based on sentiment
 Monitor behavioral shifts to avoid emotional trading

---

##  Project Structure

```
├── analysis.ipynb       # Main analysis notebook
├── README.md            # Project documentation
├── data/                # Datasets (if included)
└── outputs/             # Charts and visualizations
```

---

##  How to Run

1. Clone the repository
2. Install required libraries:

   ```
   pip install pandas matplotlib seaborn
   ```
3. Open `analysis.ipynb` in Jupyter Notebook
4. Run all cells to reproduce results

---

##  Conclusion

This analysis demonstrates that trader performance and behavior are strongly influenced by market sentiment. By incorporating sentiment-aware strategies, traders can improve decision-making and risk management.

---

##  Author

**Aditi Singh**
Machine Learning & Data Science Enthusiast
