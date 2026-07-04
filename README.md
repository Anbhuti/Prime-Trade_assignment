# Bitcoin Market Sentiment vs Trader Performance Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using Hyperliquid historical trading data.

The objective is to determine whether market sentiment influences trading profitability and identify patterns that can support smarter trading decisions.

---

## Datasets

### 1. Bitcoin Fear & Greed Index
- Date
- Sentiment Classification
- Sentiment Value

### 2. Hyperliquid Historical Trading Data
- Account
- Coin
- Execution Price
- Trade Size
- Closed PnL
- Fee
- Timestamp
- Trade Direction
- Side

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Data Preprocessing
4. Dataset Merging
5. Exploratory Data Analysis (EDA)
6. Statistical Analysis
7. Business Insights
8. Recommendations

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## Key Findings

- Extreme Greed recorded the highest average profit per trade.
- Fear market conditions generated the highest cumulative profit.
- Extreme Fear had the lowest win rate.
- Coin @107 produced the highest total profit.
- Fee is strongly correlated with trade size.
- Statistical testing indicates that the difference between Fear and Greed profitability is not statistically significant (p > 0.05).

---

## Repository Structure

```
PrimeTrade_Assignment/
│
├── data/
├── notebook.ipynb
├── report.pdf
├── requirements.txt
└── README.md
```

---

## Author

Anubhuti Pal
