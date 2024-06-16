# Banking Transaction Data Analysis Using Power BI

## Project Overview

This document presents the analysis of banking transaction data conducted using Power BI. The project aims to provide insights into customer behavior, transaction patterns, and overall banking performance to help the bank improve customer service, detect fraudulent activities, and optimize operations.

### Data Source:

The `BankingDataset1.xlsx` file contains the following columns:

1. **TransactionID**: A unique identifier for each transaction.
2. **AccountNumber**: The account number associated with the transaction. (Foreign Key)
3. **TransactionType**: The type of transaction (e.g., Transfer, Deposit, Withdrawal, Payment).
4. **Amount**: The amount of money involved in the transaction.
5. **TransactionDate**: The date when the transaction occurred.
6. **BranchCode**: The code of the bank branch where the transaction took place.
7. **Currency**: The currency in which the transaction was made.
8. **TransactionTime**: The time of day when the transaction occurred (in hours).

The `AccountDetails.xlsx` file contains the following columns:

1. **AccountNumber**: A unique identifier for each account, corresponding to 'AccountNumber' in `BankingDataset1.xlsx`. (Primary Key)
2. **AccountHolder**: The name of the account holder.
3. **AccountType**: The type of account (e.g., Credit, Loan, Checking).
4. **Balance**: The current balance of the account.
5. **InterestRate**: The interest rate applicable to the account.
6. **CreditScore**: The credit score of the account holder.
7. **OpeningDate**: The date when the account was opened.
8. **LoanAmount**: The amount of loan associated with the account (if applicable).
9. **AccountHolderDetails**: Details about account holders - employment sector, years at current residence, and city of residence, etc.

## Key Objectives

### Understand Customer Behavior:
- Analyze customer transaction patterns to identify spending habits and preferences.
- Segment customers based on transaction frequency and volume.

### Transaction Analysis:
- Track and visualize the volume and value of transactions over time.
- Identify peak transaction periods and trends across different branches.

### Fraud Detection:
- Detect unusual transaction patterns that may indicate fraudulent activities.
- Monitor high-value transactions and flag anomalies for further investigation.

### Performance Metrics:
- Evaluate the performance of different branches and ATMs.
- Assess the effectiveness of various banking products and services.



### **Dashboard Overview**
![image](https://github.com/ANDUGULA-SAI-KIRAN/PowerBI_Dashboard_on_Financial_Insights_in_Banking_Data/assets/143734802/402d3725-964a-4b84-b093-b3d4010569ad)

#### **Transaction and Balance Analysis: Displays transaction volume and value trends over time.**

![image](https://github.com/ANDUGULA-SAI-KIRAN/PowerBI_Dashboard_on_Financial_Insights_in_Banking_Data/assets/143734802/ee1f115a-8177-4239-ade0-0401fc061067)

#### **Credit score,Interest rate and and Loan Analysis: Displays credit score and Loan analysis.**

![image](https://github.com/ANDUGULA-SAI-KIRAN/PowerBI_Dashboard_on_Financial_Insights_in_Banking_Data/assets/143734802/6df57140-5c15-4479-9575-b993bf220b0c)

#### **Branch and customer Analysis: Evaluates branch and ATM efficiency and performance.**

![image](https://github.com/ANDUGULA-SAI-KIRAN/PowerBI_Dashboard_on_Financial_Insights_in_Banking_Data/assets/143734802/01d2f76a-0a62-4188-96bf-6d5cbb40c0ae)


