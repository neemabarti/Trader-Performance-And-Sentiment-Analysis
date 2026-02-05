# Trader Performance and Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between market sentiment (Fear/Greed) and trader behavior and performance using historical trading data from Hyperliquid.

The main objective is to uncover behavioral patterns and actionable insights that can inform smarter trading strategies.

The analysis includes:

- Data preparation and feature engineering
- Performance comparison across sentiment conditions
- Behavioral segmentation of traders
- Visualization-driven insights
- Strategy recommendations
- Bonus predictive modeling using Machine Learning

---

## Project Structure

- Trader_Performance_Sentiment_Analysis.ipynb — Complete analysis notebook
- README.md — Project explanation and methodology

---

## Dataset Description

Two datasets were used:

1. **Bitcoin Market Sentiment Dataset**
   - Date
   - Classification (Fear / Greed)

2. **Historical Trader Data**
   - Account
   - Execution Price
   - Size USD
   - Side (BUY/SELL)
   - Timestamp
   - Closed PnL
   - Direction
   - Other trading metrics

---

## Project Workflow

The analysis is divided into three main parts followed by a bonus machine learning section.

---

# ✅ Part A — Data Preparation & Processing

Steps performed:

- Loaded both datasets using pandas
- Checked number of rows, columns, missing values, and duplicates
- Converted timestamps into datetime format
- Created daily-level date column
- Merged sentiment data with trader data using date alignment
- Engineered key metrics:

  - Daily PnL per account
  - Win rate
  - Average trade size
  - Number of trades per day
  - Long vs Short distribution

---

# ✅ Part B — Exploratory Analysis

## Performance Comparison

Analyzed whether trader performance differs between Fear and Greed market sentiment:

- Grouped performance metrics by sentiment classification
- Compared Closed PnL distributions
- Visualized performance using boxplots and summary statistics

Key Question:
Does performance vary across market sentiment?

Answer:
Yes — performance distributions vary and volatility patterns change depending on sentiment.

---

## Behavioral Analysis

Examined how trader behavior changes based on sentiment:

- Trade frequency comparison
- Position size analysis
- Long vs Short bias across sentiment

Visualizations included:

- Bar charts
- Distribution plots
- Crosstab comparisons

---

## Trader Segmentation

Identified behavioral segments:

- Frequent vs Infrequent traders
- High volatility vs low volatility behavior patterns
- Consistent vs inconsistent performance profiles

Visualization-backed insights were provided.

---

# ✅ Part C — Strategy Recommendations

### Observation 1:
Frequent traders show both larger profits and larger losses.

**Interpretation:**
Higher trading frequency increases exposure to volatility and risk.

**Strategy Recommendation:**
Focus on controlled trading frequency and stronger risk management instead of excessive trading during uncertain market conditions.

---

### Observation 2:
Traders tend to increase position size during Greed sentiment periods.

**Interpretation:**
Market optimism may lead to overconfidence and larger positions.

**Strategy Recommendation:**
Maintain disciplined position sizing during Greed sentiment to avoid large losses during sudden reversals.

---

# ⭐ Bonus — Predictive Modeling

Implemented a simple predictive model to classify trader profitability.

Steps performed:

- Created target variable based on profitability
- Split dataset into training and testing sets
- Applied Logistic Regression model
- Identified class imbalance issue
- Improved model using:

  - Class weight balancing
  - Threshold analysis
  - Random Forest classifier

Result:

Random Forest improved prediction balance across classes compared to Logistic Regression.

---

## Key Findings Summary

- Trader behavior changes across Fear vs Greed sentiment.
- Frequent traders show higher profit potential but increased volatility risk.
- Position sizes tend to increase during Greed periods.
- Machine learning models demonstrate moderate predictive signal from sentiment and behavioral features.

---

## How to Run

1. Clone the repository
2. Install required libraries:
3. Open notebook:
4. Run cells sequentially.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---




