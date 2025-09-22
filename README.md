# Fraud Analysis Dashboard

## Overview
This project analyzes financial transactions to detect and visualize fraudulent activity.  
The dataset includes transaction-level details such as amount, type, device, location, account age, and fraud labels.  
The goal is to identify fraud patterns and provide decision support for risk management.

## Dataset
**Columns:**
- `Transaction_ID`: Unique ID for each transaction  
- `User_ID`: Unique ID for the user  
- `Transaction_Amount`: Amount of the transaction  
- `Transaction_Type`: ATM Withdrawal, POS Payment, Bill Payment, Bank Transfer, Online Purchase  
- `Device_Used`: Mobile, Desktop, Tablet, Unknown  
- `Location`: City of transaction  
- `Previous_Fraudulent_Transactions`: Count of past frauds by the user  
- `Number_of_Transactions_Last_24H`: User transaction count in last 24 hours  
- `Payment_Method`: Credit Card, Debit Card, UPI, etc.  
- `Fraudulent`: 1 = Fraud, 0 = Not Fraud  

## Dashboard Highlights
- **Total Transactions (Last 24H):** 374,820  
- **Fraudulent Cases :** 2,460  
- **Previous Fraud Transactions Recorded:** 99,823  

### Key Insights
- **Transaction Type vs Amount:** Bank transfers and bill payments show the largest amounts.  
- **Fraud by Device:** Mobile has the highest fraud volume, followed by Desktop and Tablet.  
- **Fraud by Location:** Chicago and Los Angeles show higher fraud counts compared to other cities.  
- **Fraud by Amount Range:** Most fraud cases occur in low-to-medium transaction ranges (5.03–10,005.03).  
- **Fraud Rate:** ~4.92% of transactions flagged as fraud.  

## Repository Contents
- `Fraud_Analysis.xlsx` → Report file.  
- `dataset.csv` → Source dataset.  
- `Fruad Analysis.png` → Dashboard preview.  
- `README.md` → Project documentation.  

## Dashboard Preview
![Fraud Analysis Dashboard](Fruad%20Analysis.png)

## How to Use
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/fraud-analysis-dashboard.git
