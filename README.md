## Summary
This project analyzes credit card transaction data to identify fraudulent transactions and understand fraud patterns using Python, SQL, and PowerBI. The project focuses on transaction distribution, fraud cases, transaction amounts, and fraud patterns over time.

---
## Tool Used

- Python
- Pandas
- SQL
- Power BI

---
## Dataset

- Total transactions: 284,807
- Normal transactions: 284,315
- Fraudulent transactions: 492
- Target column: 'Class'
- 'Class 0' = Normal transactions
- 'Class 1 = Fraudulent transactions

---
## Data Cleaning

- Checed the dataset structure and data types.
- Checed missing values.
- Verfied the target variable distribution.
- Prepared the dataset for SQL analysis and Power BI visualization.

---
## SQL Analysis

The transaction data was analyzed using SQL to answer business-related questions, including:

- What is the total number of transactions?
- How many transactions are fraudulent?
- How many transactions are normal?
- What percentage of transactions are fraudulent?
- Are fraudulent transactions concentrated in particular time ranges?
- How are transaction amounts distributed?

---
## Power BI Dashboard

The Power BI dashboard provides an interactive overview of credit card transactions.

---
### Dashboard Visuals

- *Transaction Type Distribution* – Shows the distribution of normal and fraudulent transactions.
- *Average Transaction Amount* – Shows the average transaction value.
- *Fraud Cases by Hour* – Shows how fraudulent transactions are distributed across elapsed hours.
- *Fraudulent Transaction Amount Over Time* – Shows the transaction amounts associated with fraudulent transactions over time.
  
---
## Business Insights

- Fraudulent transactions represent a very small portion of the total transactions.
- The dataset contains a strong imbalance between normal and fraudulent transactions.
- Fraud cases can be analyzed across different time periods to identify patterns.
- Transaction amount analysis helps understand the monetary value associated with fraudulent transactions.

---
## Conclusion

This project demonstrates how Python, SQL, and Power BI can be used together to clean, analyze, and visualize financial transaction data. The analysis helps identify fraudulent transactions and provides useful insights into fraud patterns and transaction amounts.
