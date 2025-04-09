# U.S. Treasury Activity and Macroeconomic Analysis

**Authors:** Eli Chadick, Elliot Paschal, Josh Eckmann  
**Course:** BUSN 321210 Final Project, University of Chicago Booth School of Business  
**Date:** March 10, 2025

## Project Overview

This project analyzes the economic influence of the U.S. Treasury Department using daily transaction data alongside key macroeconomic indicators such as inflation, unemployment, and interest rates.  
We build predictive models to understand the impact of Treasury security issuance and redemption on broader economic conditions from 2006–2024.

The target audience includes U.S. policymakers, especially those at the Treasury Department and Federal Reserve, who require a clear understanding of how government borrowing strategies interact with macroeconomic health.

## Repository Structure

- `Final_ChadickPaschalEckmann.ipynb` – Full analysis notebook including data exploration, SQL queries, and model building (logistic and linear regressions).
- `presentation/Presentation_ChadickPaschalEckmann.pdf` – Final compiled presentation summarizing key results and insights.

## Main Findings

- Treasury debt issuance shows a strong relationship with macroeconomic variables, especially during times of economic uncertainty.
- Logistic regression successfully predicts whether net Treasury issuance will increase month-to-month with an accuracy of **81%**.
- Linear regression modeling reveals significant links between debt issuance and future inflation trends (CPI), providing insights into government borrowing and inflation management.

## Data Sources

- [U.S. Treasury Debt Transactions Data](https://fiscaldata.treasury.gov)
- [Consumer Price Index (CPI)](https://fred.stlouisfed.org/series/CPIAUCSL)
- [30-Year Mortgage Rate](https://fred.stlouisfed.org/series/MORTGAGE30US)
- [Unemployment Rate](https://fred.stlouisfed.org/series/UNRATE)

