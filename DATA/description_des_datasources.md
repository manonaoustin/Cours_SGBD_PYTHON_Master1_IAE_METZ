# Dataset Description — BNP Paribas Trading Positions

## What is this dataset ?

This file contains fictional but realistic trading positions representing the type of data BNP Paribas manages every single day as a Global Systemically Important Bank (G-SIB).

It was created to illustrate our database architecture proposal and demonstrate BCBS 239 compliance.

---

## File Information :

| Detail | Value |
|--------|-------|
| File name | Sample dataset.csv |
| Format | CSV (semicolon separated) |
| Number of rows | 6 positions |
| Date of positions | 07/04/2025 |
| Currency | Euros (EUR) |

---

## Column Description

| Column | Type | Description |
|--------|------|-------------|
| Position_ID | Text | Unique identifier for each transaction |
| Asset_Class | Text | Type of financial instrument |
| Counterparty | Text | The other party in the transaction |
| Country | Text | Country of the counterparty  |
| Notional_EUR | Number | Face value of the contract at trade date |
| Market_Value | Number | Current value of the position today (can be negative) |
| Rating | Text | Credit rating of the counterparty by S&P or Moody's |
| VaR_Contribution | Number | Maximum daily loss on this position under normal conditions |

---

## Asset Classes Covered

| Asset Class | Description |
|-------------|-------------|
| Corporate Bond | Debt issued by a company |
| Sovereign | Government debt |
| Derivative | Contract whose value depends on an underlying asset |
| Equity | Shares |
| FX | Foreign exchange |
| Credit Default Swap | Insurance against a counterparty default |

---

## BCBS 239 Connection

This dataset directly illustrates the following BCBS 239 principles :

| Principle | How this dataset illustrates it |
|-----------|--------------------------------|
| P3 — Accuracy | Each position has precise values with no rounding errors |
| P4 — Completeness | All asset classes and geographies are represented |
| P5 — Timeliness | Market values reflect same-day pricing |
| P6 — Adaptability | Data can be filtered by country, asset class, or counterparty instantly |

---

## Important Note

All data in this file is **fictional and created for educational purposes only**. It does not represent real BNP Paribas positions or exposures.

Bibliography: 

Kaggle: https://www.kaggle.com/datasets
