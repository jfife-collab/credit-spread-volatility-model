# Credit Spread Volatility Forecasting Model

### Executive Summary
An end-to-end data pipeline and machine learning model designed to forecast volatility in High-Yield Credit Spreads (OAS). This project demonstrates the transition from raw macro indicators to a structured risk-vault (SQL) and predictive signals.

### Key Technical Features
* **Automated ETL Pipeline:** Pulls live macro data from FRED API into a persistent SQLite "Risk Vault."
* **Relational Database Design:** Implements a normalized schema with asset metadata to ensure data integrity and scalability.
* **Feature Engineering:** Utilizes SQL Window Functions (LAG, LEAD) to handle time-series shifts and prevent look-ahead bias.
* **Predictive Modeling:** (In Progress) Leveraging Random Forest Regressors to identify non-linear relationships between the VIX and Credit Spreads.

### Tech Stack
Python (Pandas, Scikit-Learn), SQL (SQLite), FRED API