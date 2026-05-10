# **Comparable Company Valuation Tool**

A Python-based financial valuation tool that performs Comparable Company Analysis (Trading Comps) using real-time market data from Yahoo Finance.

**This project allows users to:**

1. Enter a target company
2. Enter comparable peer companies
3. Automatically fetch financial data
4. Calculate valuation multiples
5. Estimate implied valuation
6. Analyze upside/downside potential
7. Generate valuation charts
8. Export outputs to Excel
9. Features
10. Real-time financial data using yfinance
11. Comparable company valuation methodology
12. EV/EBITDA analysis
13. EV/Revenue analysis
14. P/E ratio analysis
15. Implied enterprise value calculation
16. Implied equity value calculation
17. Implied share price estimation
18. Upside/downside analysis
19. Visualization using Matplotlib
20. Excel export functionality
21. Interactive terminal-based inputs

## **Financial Concepts Used**

This project implements real-world valuation techniques including:

**Enterprise Value: **

    Enterprise Value = Market Cap + Debt − Cash

**EV/EBITDA Multiple**
        
    EV/EBITDA = EBITDA / Enterprise Value
	​
**Implied Enterprise Value**

    Implied EV = EBITDA × Peer Median EV/EBITDA

**Equity Value**

    Equity Value = EV − Debt + Cash

**Implied Share Price**

    Implied Share Price = Shares Outstanding / Equity Value
	​
## **Technologies Used:**

1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Yahoo Finance API (yfinance)
