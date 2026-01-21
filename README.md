# UPI Transactions Analysis – Power BI Dashboard

## Project Overview
This project presents an **interactive Power BI dashboard** built to analyze **UPI (Unified Payments Interface) transactions**.  
The dashboard provides insights into transaction trends, user behavior, bank-wise performance, payment methods, and transaction success rates using real-world styled transactional data.

The goal of this project is to demonstrate **data cleaning, modeling, visualization, and business insight generation** using **Microsoft Power BI**.

---

## Project Files
<pre>
UPI-Transactions-Analysis
├── UPI_Transactions_Analysis.pbix # Power BI Dashboard file
├── UPI Transactions.xlsx # Source dataset
└── README.md # Project documentation
</pre>
---

## Dataset Description
The dataset contains simulated UPI transaction records with the following key attributes:

| Column Name | Description |
|------------|-------------|
| TransactionID | Unique transaction identifier |
| TransactionDate | Date of transaction |
| Amount | Transaction amount |
| BankNameSent | Sender bank |
| BankNameReceived | Receiver bank |
| RemainingBalance | Balance after transaction |
| City | User city |
| Gender | Customer gender |
| TransactionType | Payment / Transfer |
| Status | Success / Failed |
| DeviceType | Mobile / Tablet |
| PaymentMethod | UPI ID / Phone Number / QR Code |
| MerchantName | Merchant involved |
| Purpose | Purpose of transaction |
| CustomerAge | Age of customer |
| PaymentMode | Instant / Scheduled |
| Currency | Currency used |
| CustomerAccountNumber | Customer account number |
| MerchantAccountNumber | Merchant account number |

---

## Project Objectives
- Analyze **UPI transaction trends over time**
- Identify **top-performing banks**
- Understand **customer behavior** by city, gender, and age
- Monitor **transaction success vs failure**
- Evaluate **payment methods and device usage**

---

## Dashboard Features

### Transaction Insights
- Total number of transactions
- Total transaction amount
- Success vs Failed transaction ratio

### Bank Analysis
- Transactions by sender bank
- Transactions by receiver bank
- Inter-bank vs same-bank transactions

### Customer Insights
- Transactions by city
- Gender-wise transaction distribution
- Age-group based analysis

### Payment Analysis
- Payment method usage
- Device type distribution
- Transaction purpose analysis

### Time-Based Analysis
- Daily transaction trends
- Monthly transaction trends
- Peak transaction periods

---

## Tools & Technologies Used
- **Microsoft Power BI**
- **Microsoft Excel**
- **Power Query** (Data cleaning and transformation)
- **DAX** (Calculated measures and KPIs)

---

## Data Processing Steps
1. Imported Excel dataset into Power BI  
2. Cleaned and transformed data using Power Query  
3. Created calculated columns and measures using DAX  
4. Built KPIs and summary cards  
5. Designed interactive visuals, filters, and slicers  

---

## Key Insights (Sample Observations)
- Certain banks dominate UPI transaction volume
- Mobile devices are the most preferred transaction medium
- Majority of transactions are **instant payments**
- Transaction failures increase during peak usage hours
- Urban cities contribute the highest transaction volume

---

## How to Use the Project
1. Download or clone this repository
2. Open `UPI_Transactions_Analysis.pbix` using **Power BI Desktop**
3. Use slicers and filters to explore different insights

---

## Use Cases
This project can be used for:
- Data Analytics and Power BI portfolios
- Interview demonstrations
- Learning Power BI dashboards and DAX
- Business transaction analysis scenarios

---


