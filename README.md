# EverTrust Financial Group | Fraud Detection Analysis

## Project Overview
This academic data analytics project focuses on examining synthetic financial transaction data to better understand fraudulent activity and the challenges financial institutions face when identifying suspicious transactions. The project was completed as part of DAT-223: Gathering Requirements and Collecting Data.

## Business Problem
EverTrust Financial Group is a fictional client seeking to better understand fraudulent transactions and identify what data is needed to support fraud prevention. The analysis focuses on transaction types, transaction amounts, account balances, and fraud indicators.

## Tools and Skills
- Python
- Pandas
- Jupyter Notebook
- CSV data import and inspection
- Data merging and preparation
- Data quality assessment
- Business requirements and stakeholder analysis
- Technical documentation

## Dataset
The project uses two synthetic financial transaction datasets containing transaction details and fraud indicators. The files were joined using the shared `nameOrig` field for exploratory analysis.

The combined dataset contained 4,999 rows and 11 columns. The initial inspection identified 40 transactions labeled as fraudulent and 4,959 labeled as non-fraudulent.

## Data Preparation
1. Imported both CSV files into Python using Pandas.
2. Reviewed dataset dimensions, column names, and sample records.
3. Identified the shared `nameOrig` field and merged the datasets.
4. Inspected the combined data for missing values.
5. Selected relevant variables for fraud analysis.
6. Reviewed the distribution of fraud labels.

## Preliminary Findings
- 40 of the 4,999 transactions were labeled fraudulent (approximately 0.8%).
- The dataset includes transaction types such as PAYMENT, TRANSFER, CASH_OUT, and DEBIT.
- Transaction amounts, account balances, and fraud indicators provide a starting point for investigating suspicious activity.
- The inspected merged dataset contained no missing values.

These findings are preliminary and do not establish the accuracy of any fraud detection system. The shared field should also be validated as a transaction-level matching key before relying on the merged records for further analysis.

## Limitations and Next Steps
Because the dataset is synthetic, the findings may not fully represent real financial activity. Additional information about transaction timing, account behavior, fraud investigation outcomes, and detection procedures could help strengthen future analysis.

Future work could include comparing fraud rates by transaction type, investigating unusual balance changes, validating data relationships, and creating visualizations to communicate findings.

## Project Context
This is an academic portfolio project using simulated financial data. EverTrust Financial Group is the fictional client in the coursework, and the project does not represent employment or consulting work performed for a real financial institution.
