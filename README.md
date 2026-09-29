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
<img width="586" height="548" alt="Screenshot 2026-09-28 133745" src="https://github.com/user-attachments/assets/da437e9f-5659-4e2a-9106-abe777163616" />
<img width="636" height="365" alt="Screenshot 2026-09-28 133859" src="https://github.com/user-attachments/assets/50dc402f-1ff9-48c7-af9f-b20aa9a48000" />


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
<img width="1771" height="805" alt="Screenshot 2026-09-28 132317" src="https://github.com/user-attachments/assets/7d784672-9632-4e32-8981-fec40afff374" />


---
### Dashboard Visuals

- *Transaction Type Distribution* – Shows the distribution of normal and fraudulent transactions.
- *Average Transaction Amount* – Shows the average transaction value.
- *Fraud Cases by Hour* – Shows how fraudulent transactions are distributed across elapsed hours.
- *Fraudulent Transaction Amount Over Time* – Shows the transaction amounts associated with fraudulent transactions over time.
  
---
## Business Insights

1. What is the overall distribution of normal and fraudulent transactions?
       Normal transactions make up the vast majority of the dataset, while fraudulent transactions represent a very small portion.

2. Are fraudulent transactions concentrated in particular time periods?
     Fraud cases vary across different elapsed hours, with some time periods showing higher numbers of fraudulent transactions.

3. What is the average transaction amount?
    The average transaction amount provides an overview of the typical value of transactions in the dataset.

4. How does the amount involved in fraudulent transactions change over time?
      The fraudulent transaction amount varies across the recorded time period, helping identify periods with higher-value fraudulent activity.

---
## Conclusion

This project demonstrates how Python, SQL, and Power BI can be used together to clean, analyze, and visualize financial transaction data. The analysis helps identify fraudulent transactions and provides useful insights into fraud patterns and transaction amounts.
