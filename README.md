# Financial Banking Transaction Data Analysis Using Power BI

## Project Description
FinInsight Group, a consultancy specializing in banking analytics, undertakes a project to analyze financial data using Power BI. The project utilizes two comprehensive datasets: 'Banking Transactions' and 'Customer Account Details'. The 'Banking Transactions' dataset includes detailed transaction data such as types, amounts, dates, and branch information. The 'Customer Account Details' dataset provides insights into account holders, covering account types, balances, interest rates, credit scores, and loan amounts. This analysis is crucial in a sector where financial data drives strategic decisions in customer relationship management, risk assessment, and product offerings.

## Project Objective
The primary objective of this project is to employ Power BI to analyze these banking datasets, aiming to unravel the intricate patterns and behaviors within the data. This involves in-depth data cleaning, robust data modeling, and strategic use of DAX for complex analytics. The goal is to create a comprehensive, interactive dashboard that not only illustrates transactional trends and customer profiles but also offers a holistic view of the banking ecosystem. The analysis includes understanding customer transaction behaviors, identifying relationships between account characteristics and financial health, and exploring factors influencing credit scores and loan management. These insights will guide FinInsight Group in advising banking institutions on optimizing their services, enhancing customer satisfaction, and managing financial risks effectively.

## Project Overview
This document presents the analysis of banking transaction data conducted using Power BI. The project aims to provide insights into customer behavior, transaction patterns, and overall banking performance to help the bank improve customer service, detect fraudulent activities, and optimize operations.



### Key Objectives
#### Understand Customer Behavior:
- Analyze customer transaction patterns to identify spending habits and preferences.
- Segment customers based on transaction frequency and volume.

#### Transaction Analysis:
- Track and visualize the volume and value of transactions over time.
- Identify peak transaction periods and trends across different branches.

#### Fraud Detection:
- Detect unusual transaction patterns that may indicate fraudulent activities.
- Monitor high-value transactions and flag anomalies for further investigation.

#### Performance Metrics:
- Evaluate the performance of different branches and ATMs.
- Assess the effectiveness of various banking products and services.


## **Dashboard Overview**
![image](https://github.com/ANDUGULA-SAI-KIRAN/PowerBI_Dashboard_on_Financial_Insights_in_Banking_Data/assets/143734802/402d3725-964a-4b84-b093-b3d4010569ad)

### **Transaction and Balance Analysis: Displays transaction volume and value trends over time.**
![image](https://github.com/ANDUGULA-SAI-KIRAN/PowerBI_Dashboard_on_Financial_Insights_in_Banking_Data/assets/143734802/ee1f115a-8177-4239-ade0-0401fc061067)
### Insights

#### Transaction Trend over Time - Hourly:
- Highest transaction volume occurs at **11am and 3pm.** 
- Highest transactions by amount have occurred at **2am and 11am. **

#### Transaction Trend over Time - Quarterly:
- **No wide fluctuations** in the transaction volume over time. 
- Trend in credit transactions is opposite to the trend in debit transactions. 

#### Historical Trend in Transaction Volume and Forecast for Next 1 Quarter:
- **Highest transaction volume** occurred in the **second half of the calendar year, i.e. from July to September. **
- Not much fluctuation in the trend of transaction volume.
**- Forecast for next quarter indicates a slight reduction in the transaction volume.**

#### Average Account Balance:
- **Highest average account balance** is of** "Savings" account type.**

#### High Value Transactions:
-**High-value transactions** have been defined as **transactions > USD 5000.**
- 2.5% of total transactions are unusual (or fraudulent) high-value transactions.
- **Total number of High-Value Transactions are lesser than Regular transactions.**

#### Rare Transaction Types:
- Rare transaction types are those for which the description was other than Transfer, Withdrawal, Deposit, and Payment.
- **Value of unusual transactions is not very high but those have mainly occurred under "Payment" category.**



### **Credit score,Interest rate and and Loan Analysis: Displays credit score and Loan analysis.**

![image](https://github.com/ANDUGULA-SAI-KIRAN/PowerBI_Dashboard_on_Financial_Insights_in_Banking_Data/assets/143734802/6df57140-5c15-4479-9575-b993bf220b0c)

## Insights - Interest Rate, Loan & Credit Score Analysis

### Interest rate and Balance correlation:
- There is no correlation between interest rate and USD Balance.

### Credit score and loan amount correlation:
- There is no correlation between Credit score and Loan amount.

### Account age and balance correlation:
- There is no correlation between Account age and Balance.

### Distribution of credit score among account holder by account type
- Analysis of credit score ranges and predominant account types:
  - **300-400:** Highest number of **Checking** account holders.
  - **800-900:** Highest number of **Loan** account holders.
  - **Others:** Highest number of **Savings** account holders.
- **Insight: Customers with high credit scores tend to get more loans, though their count is relatively small. Savings account holders have a wide range of credit scores, while the lowest credit scores belong to Checking account holders.**

### Distribution of Interest rate among account holder by account type:
- Most account holders have an interest rate between **1% and 3%**.

### Loan amount by City and Sector:
- **City Observation:**
  - **London** has the **highest loan amounts.**
  - Followed by Berlin, Sydney, and other cities.
- **Sector Observation:**
  - **Technology** sector has the **highest loan amounts.**
  - Followed by Education, Healthcare, and other sectors.



### **Branch and customer Analysis: Evaluates branch and ATM efficiency and performance.**

![image](https://github.com/ANDUGULA-SAI-KIRAN/PowerBI_Dashboard_on_Financial_Insights_in_Banking_Data/assets/143734802/01d2f76a-0a62-4188-96bf-6d5cbb40c0ae)

### Insights 
#### Branch Analysis:
- **Branch 479** has the highest number of **8 transactions.**

#### Customer Risk Assessment:
- **High-Risk Customers:** 9 customers (risk score > 10).
- **Low-Risk Customers:** 680 customers (risk score < 1).

#### Sector Transaction Behavior:
- **Technology Sector:** Customers in this sector have the highest transaction volume, and the amount is **884k**.
- **Finance Sector:** Customers in this sector have the **lowest transaction volume.**

#### Demographic Transaction Behavior:
- **Sydney** has the highest transaction count with **226 transactions.**
- **New York** and **London** have the same number of transactions, but the amount of transactions is greater for London.

#### Branch Performance:
- **Branch 57** is identified as the highest-performing branch.
- Highlight the top five performing branches using a funnel chart.

#### Loyalty Analysis:
- The longest association with the bank for the most loyal customers is **1649 days.**

