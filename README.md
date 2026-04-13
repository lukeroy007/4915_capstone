# Loan Loss Provisions and Macroeconomic Risk Recognition

## Overview

This project examines whether aggregate loan loss provisioning behavior in the U.S. banking system systematically reflects contemporaneous or lagged macroeconomic risk conditions.

The central question is:

> Do banks recognize macroeconomic deterioration in a timely manner through loan loss provisions?

The analysis uses publicly available time-series data from the Federal Reserve Economic Data (FRED) database and evaluates dynamic relationships between macroeconomic indicators and aggregate provisioning measures.

This study is descriptive in nature and does not attempt to make causal claims.

---

## Research Motivation

Loan loss provisions (LLP) are a key mechanism through which banks recognize expected credit risk. If provisioning behavior responds too slowly to macroeconomic deterioration, financial vulnerabilities may accumulate during expansions and amplify downturns.

Understanding the cyclical properties of LLP contributes to discussions surrounding:

- Procyclicality in banking
- Risk recognition timing
- Financial stability monitoring
- Macroprudential policy interpretation

---

## Data Sources

All data are sourced from:

- Federal Reserve Economic Data (FRED)
- Publicly available U.S. macroeconomic indicators

No confidential or bank-level microdata are used.

---

## Project Structure




---

## Environment & Reproducibility

This project uses:

- Python 3.11
- pandas
- statsmodels
- fredapi
- Quarto for final report generation

To replicate:

1. Clone repository
2. Create environment
3. Install requirements
4. Add FRED API key in `.env`
5. Run notebooks sequentially

---

## Status

Project setup and environment configuration complete.  
Data collection and cleaning in progress.
