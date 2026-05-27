# UPI Fraud & Spending Intelligence Dashboard

## Problem Statement
A digital payments company is experiencing a spike in fraudulent 
UPI transactions. This project analyzes 37,000+ transactions to 
identify fraud patterns and deliver actionable prevention strategies.

## Tools Used
- Python (Pandas, NumPy) — Data cleaning & feature engineering
- SQL (SQLite) — Business-focused fraud pattern analysis  
- Power BI — 3-page interactive dashboard

## Key Findings
1. Late Night transactions (11PM–6AM) have 2x higher fraud rate — 0.45% vs 0.19%
2. Delhi carries highest city fraud rate at 0.40% — 60% above average
3. Healthcare & Shopping are riskiest merchant categories at 0.38% and 0.36%
4. Small transactions (₹500–5K) have highest fraud rate at 0.50%
5. New accounts (<30 days) are 22% more fraud-prone than established accounts

## Recommendations
1. Step-up authentication for all transactions after 11PM
2. Real-time flagging for Delhi + Healthcare/Shopping combination
3. Transaction cap of ₹2,000 for accounts under 30 days old

## Dashboard Preview
<img width="1195" height="668" alt="image" src="https://github.com/user-attachments/assets/25f86c5e-e647-46b1-a837-9bcb649907cb" />


## Project Structure
upi-fraud-analytics/
├── upi_clean.csv          # Cleaned dataset
├── upi_fraud_analysis.ipynb  # Python + SQL analysis
├── UPI_Fraud_Dashboard.pbix  # Power BI dashboard
└── README.md
