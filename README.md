# Primetrade.ai – Data Science Internship Assignment

This repository contains my submission for the **Data Science Internship** at **Primetrade.ai**.  
The project analyzes how **crypto trader behavior varies under different market sentiment regimes (Fear vs Greed)** using historical trading data.

---

## 📌 Objective

The goal of this assignment is to:
- Analyze trader performance under different market sentiment conditions
- Understand how sentiment (Fear vs Greed) impacts profitability and risk
- Identify high-performing and contrarian traders
- Generate insights that can support smarter trading strategies

---

## 📊 Datasets Used

1. **Bitcoin Fear & Greed Index**
   - Daily market sentiment classified as Fear, Extreme Fear, Greed, or Extreme Greed
   - Used to label market conditions

2. **Historical Trader Data (Hyperliquid)**
   - Trade-level data including:
     - Trader account
     - Trade size
     - Profit & Loss (PnL)
     - Timestamps
   - Used to compute trader performance metrics

---

## 🛠️ Methodology

The analysis follows these steps:
1. Data cleaning and preprocessing
2. Mapping each trade to the corresponding market sentiment
3. Simplifying sentiment into two regimes: **Fear** and **Greed**
4. Computing trader-level metrics under each regime:
   - Total PnL
   - Win Rate
   - ROI
   - Sharpe Ratio
   - Maximum Drawdown
5. Ranking traders by performance
6. Identifying **contrarian traders** who perform differently across sentiment regimes
7. Visualizing key patterns and insights

---

## 📈 Key Metrics Analyzed

- **Total PnL**
- **Win Rate**
- **Return on Investment (ROI)**
- **Sharpe Ratio**
- **Maximum Drawdown**
- **Trade Frequency**
- **Contrarian Performance (Fear vs Greed)**

---

## 📁 Repository Structure
ds_ayush/

├── notebook_1.ipynb # Google Colab notebook with full analysis

├── csv_files/

│ └── trader_metrics.csv # Final computed trader metrics

├── outputs/

│ ├── pnl_by_sentiment.png

│ ├── avg_roi_by_sentiment.png

│ └── top_traders_by_roi.png

├── ds_report.pdf # Final summarized report and insights


---

## 📊 Visualizations Included

- PnL distribution by market sentiment
- Average ROI comparison (Fear vs Greed)
- Top traders by ROI under different sentiment regimes

---

## 📄 Report

The **`ds_report.pdf`** contains:
- Problem overview
- Dataset description
- Methodology
- Key findings
- Trader ranking logic
- Actionable insights for trading strategies

---

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

---

## 👤 Author

**Ayush Gupta**  
Data Science Intern Applicant – Primetrade.ai

---


