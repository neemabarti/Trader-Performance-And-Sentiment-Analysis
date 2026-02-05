# Trader Performance and Market Sentiment Analysis

## 📊 Project Overview

This project analyzes the relationship between market sentiment (Fear/Greed) and trader behavior and performance using historical trading data.  

The goal is to uncover patterns that can help understand:

- How sentiment affects trading decisions
- Performance differences across sentiment conditions
- Behavioral patterns of traders
- Potential predictive insights using machine learning

---

## 🚀 Project Workflow

The analysis was structured into three main parts followed by bonus machine learning experimentation.

---

# ✅ Part A — Data Preparation & Processing

### What I Did:

- Loaded historical trading dataset and sentiment dataset
- Converted timestamp fields into datetime format
- Created standardized date columns for merging
- Merged trader activity with sentiment classification
- Generated daily-level data for analysis

### Purpose:

To align trader performance data with market sentiment for meaningful comparison.

---

# ✅ Part B — Exploratory Analysis & Behavioral Insights

## Step 1 — Performance Metrics Creation

- Calculated Closed PnL metrics
- Created win/loss indicator
- Computed win rate per trader
- Average trade size analysis
- Trade frequency analysis

---

## Step 2 — Performance Comparison by Sentiment

Analyzed differences across sentiment categories:

- Closed PnL distribution by sentiment
- Position size differences
- Trade direction behavior (Long vs Short)
- Visualization using boxplots and charts

Key goal:

Understand whether Fear or Greed environments influence trading outcomes.

---

## Step 3 — Behavioral Segmentation

Identified trader behavior patterns:

- Frequent vs Infrequent traders
- Trade frequency analysis
- PnL distribution comparison
- Market participation differences

---

# ✅ Part C — Strategy Recommendations

Based on observed patterns:

### Case 1 — Frequent vs Infrequent Traders

Observation:

- Frequent traders showed higher profit potential but also larger losses.

Interpretation:

- Higher trading frequency increases exposure to volatility.

Recommendation:

- Focus on selective, high-confidence trades and stronger risk management.

---

### Case 2 — Sentiment-Based Position Sizing

Observation:

- Traders increased position size during Greed sentiment.

Interpretation:

- Overconfidence during bullish sentiment may increase risk.

Recommendation:

- Maintain disciplined position sizing regardless of sentiment.

---

# ⭐ BONUS — Predictive Modeling

To extend the analysis, a lightweight machine learning approach was implemented.

## Models Used:

- Logistic Regression (baseline model)
- Random Forest Classifier (improved performance)

### Steps:

- Feature selection from sentiment and behavioral metrics
- Train-test split
- Model training and evaluation
- Accuracy and classification report analysis
- Addressed class imbalance issues

### Key Finding:

- Logistic Regression initially showed class bias.
- Random Forest improved prediction balance and classified both classes effectively.

---

# 📈 Visualizations Included

- PnL distribution by sentiment
- Trade size comparison charts
- Long vs Short distribution
- Trader frequency segmentation
- Model evaluation metrics

---

# 🧠 Key Insights

- Market sentiment influences trader behavior patterns.
- Frequent traders experience higher volatility.
- Risk management becomes critical during Greed sentiment.
- Behavioral features contain some predictive signal.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📌 How to Run

1. Clone repository
2. Install dependencies:
3. Open notebook:
4. Run all cells squentially.
