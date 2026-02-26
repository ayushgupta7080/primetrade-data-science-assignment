Primetrade.ai – Sentiment-Based Trader Performance Analysis

This repository contains my submission for the Data Science Internship at Primetrade.ai.

The project evaluates how crypto trader performance changes under different market sentiment regimes (Fear vs Greed) and translates these behavioral insights into actionable, data-driven strategy recommendations.

🎯 Problem Statement

Market sentiment significantly influences trading behavior and risk exposure.

This project aims to:

Quantify how trader profitability and risk vary under different sentiment regimes

Measure the impact of sentiment on key performance metrics

Identify traders who outperform under specific market conditions

Detect contrarian traders with regime-dependent behavior

Generate structured insights that can support sentiment-aware trading strategies

📊 Data Sources
1️⃣ Bitcoin Fear & Greed Index

Daily sentiment classification: Extreme Fear, Fear, Greed, Extreme Greed

Used to label macro market conditions

Simplified into two analytical regimes: Fear and Greed

2️⃣ Historical Trade-Level Data (Hyperliquid)

Includes:

Trader account identifiers

Trade size

Profit & Loss (PnL)

Execution timestamps

This dataset enables computation of trader-level performance metrics and regime-based behavioral analysis.

⚙️ Analytical Approach

The project follows a structured analytics workflow:

1. Data Preparation

Cleaned and validated trade-level data

Handled timestamp alignment and missing values

Standardized sentiment classifications

2. Sentiment Mapping

Mapped each trade to its corresponding market sentiment

Consolidated into two regimes: Fear vs Greed

3. Metric Engineering (KPI Framework)

Computed trader-level metrics under each regime:

Total PnL

Win Rate

Return on Investment (ROI)

Sharpe Ratio (Risk-Adjusted Return)

Maximum Drawdown

Trade Frequency

4. Comparative & Regime-Based Analysis

Ranked traders by performance under each sentiment regime

Compared ROI and risk-adjusted returns across regimes

Identified contrarian traders who perform significantly better in opposing market conditions

5. Visualization & Insight Communication

Built visualizations to clearly highlight regime-based performance shifts

Structured findings into an interpretable decision-support report

📈 Key Insights Generated

Sentiment regimes materially impact profitability and drawdown behavior

Certain traders exhibit consistent performance across regimes

Contrarian traders demonstrate stronger performance during adverse sentiment periods

Regime-aware performance segmentation can improve trader evaluation frameworks

These insights can support:

Risk-adjusted allocation decisions

Strategy refinement based on market conditions

Identification of adaptive vs sentiment-sensitive traders

📁 Repository Structure
ds_ayush/

├── notebook_1.ipynb        # Full analysis notebook (Google Colab)

├── csv_files/
│   └── trader_metrics.csv  # Computed trader-level KPI dataset

├── outputs/
│   ├── pnl_by_sentiment.png
│   ├── avg_roi_by_sentiment.png
│   └── top_traders_by_roi.png

├── ds_report.pdf           # Final summarized analytical report
📊 Visualizations Included

PnL distribution by market sentiment

Average ROI comparison (Fear vs Greed)

Trader ranking by ROI

Regime-based performance segmentation

📄 Final Report

The ds_report.pdf includes:

Business context and objective

Dataset overview

Methodology and KPI logic

Trader ranking framework

Regime-based comparative analysis

Actionable insights and strategic implications

🧰 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Google Colab

👤 Author

Ayush Gupta
Data Analyst / Data Science Internship Applicant
