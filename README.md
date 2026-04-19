ACC102 US Listed Companies Financial Health Analysis
## Problem & User 
This project assesses the financial health and investment risk of 10 major U.S. listed companies using key financial ratios and a custom risk score model. The target users include individual investors, finance students, and junior financial analysts seeking data-driven corporate risk comparisons.
## Data
Source: WRDS Compustat (funda table)
Access date: 2025 (latest 5 fiscal years)
Key fields: Ticker, company name, stock price, market cap, EBITDA, total debt, net income, revenue, shareholders’ equity, data date
## Methods
Connect to WRDS and extract historical financial data via SQL query
Clean data: remove missing values and filter valid records
Calculate debt-to-equity ratio, profit margin, and ROE
Compute a weighted risk score and rank companies by safety
Visualize indicators with Matplotlib line chart
Output full analyzed dataset and results
## Key Findings 
Technology companies (AAPL, MSFT, NVDA) show low debt and high ROE with the lowest risk scores
Financial firm JPMorgan Chase has the highest leverage and overall risk score
Consumer staple companies (WMT) maintain stable but moderate profitability
Risk score effectively differentiates financial safety across industries
Visualization clearly displays variation in debt, profitability, and risk across firms
## How to run
Install packages: pip install wrds pandas matplotlib
Enter your WRDS username in the connection code
Run the full script sequentially
View printed financial results and generated line chart
## Product link / Demo
Local Python script output: console results + Matplotlib comparative line chart (no external link)
## Limitations & next steps
Limitations: No sector classification data; simple weighted risk model; static cross-sectional analysis
Next steps: Add industry labels; build advanced risk model; include time-series trends; use interactive Plotly charts
est financial safety. JPMorgan Chase (JPM) in the financial sector has relatively high leverage and the highest risk score. The results are consistent with real-world industrial financial characteristics.
 ## Note 
For academic use only. All data are from public financial databases.
