# ACC102 Financial Health Analysis 
Financial indicator calculation, risk assessment and visualization for 10 U.S. listed companies 
## Project Overview 
This project is a Python-based financial analysis assignment. It retrieves historical financial data from WRDS, calculates core financial ratios, evaluates corporate financial risk through a scoring model, and visualizes key indicators to compare financial health across companies. 
## Data Source 
- Database: WRDS Compustat 
- Companies: AAPL, MSFT, GOOGL, AMZN, TSLA, JPM, JNJ, V, NVDA, WMT 
- Time Range: Latest 5 fiscal years 
- Fields: Price, Market Cap, EBITDA, Debt, Net Income, Revenue, Equity, etc. 
## Tools & Libraries
- Python 3 
- wrds (for data retrieval) 
- pandas (for data processing) 
- matplotlib (for visualization) 
## Core Functions 
1.Connect to WRDS and obtain standardized corporate financial data 
2.Data cleaning and missing value elimination 
3.Calculate three key financial indicators: 
- Debt-to-Equity Ratio 
- Profit Margin 
- ROE (Return on Equity) 
4.Build a weighted risk scoring model 
5.Sort companies by financial safety (lower score = safer) 
6.Visualize all indicators in a comparative line chart 
## Analysis Logic 
Risk Score = Debt-to-Equity × 0.5 + (1-Profit Margin) × 0.3 + (1-ROE) × 0.2 
## Output Results 
1.Financial indicators for each company 
2.Risk score ranking (from safest to riskiest) 
3.Comparative line chart of Debt/Equity, Profit Margin, ROE and Risk Score 
4.Cleaned and complete financial dataset 
## How to Run 
1.Install required packages: pip install wrds pandas matplotlib 
2.Log in with valid WRDS username 
3.Run the code sequentially 
4.View printed results and chart 
## Analysis Summary 
This analysis covers 10 major U.S. listed companies. Technology enterprises (represented by AAPL and NVDA) show low debt pressure, high profitability and strong shareholder return, thus achieving the lowest risk scores and the highest financial safety. JPMorgan Chase (JPM) in the financial sector has relatively high leverage and the highest risk score. The results are consistent with real-world industrial financial characteristics.
 ## Note 
For academic use only. All data are from public financial databases.
