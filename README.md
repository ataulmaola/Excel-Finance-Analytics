# 📊 Sales Analytics Dashboard in Excel

This project focuses on analyzing sales data using **Microsoft Excel**. It includes data cleaning with Power Query, data modeling with Power Pivot, and building an interactive report/ dashboard using PivotTables and DAX measures.

The goal is to extract meaningful business insights, track KPIs, and support strategic decision-making through clean reporting.


## 🧾 Project Summary

- Cleaned raw sales data using **Power Query**
- Transformed and loaded data into a model using **Power Pivot**
- Built relationships between tables to enable powerful calculations
- Used **DAX measures** to create dynamic metrics like product , division category wise Net sales 
- Created an **interactive report** with  pivot table


---

## 🛠️ Tools & Features Used

| Tool/Concept       | Purpose                                      |
|--------------------|----------------------------------------------|
| Excel              | Main platform for data analysis              |
| Power Query        | Data cleaning and transformation (ETL)       |
| Power Pivot        | Data modeling and managing relationships     |
| DAX (Data Analysis Expressions) | Calculations and KPIs         |
| PivotTables & Charts | Visualization of metrics and trends       |


### 📌 01 – P&L Report by Fiscal Year and Months

This report presents a detailed Profit & Loss (P&L) view for the fiscal years **2019** and **2020**, broken down by months and quarters.

#### 🔍 Key Metrics Displayed:
- **Net Sales** (in millions USD)  
- **COGS** (Cost of Goods Sold)  
- **Gross Margin (USD)**  
- **Gross Margin Percentage (GM %)**

#### 🎯 Features:
- Time series comparison across quarters (Q1 to Q4)  
- **Filters applied**:  
  - Region  
  - Division  
  - Market  
  - Customer  
  - Fiscal Year  
- Color-coded conditional formatting for better visual interpretation of margin performance  
- Grand Totals included at the right for each metric  
- Segregated into Pivot Table structure — note that "21 vs 20" metrics are excluded from this specific pivot


![P&L Report by Fiscal Year and Months](https://github.com/ataulmaola/Excel-Finance-Analytics/blob/140f3d324d012c3347e85f2d2282d74cdcbdda3d/1.png)

### 📌 02 –  P&L Summary by Division - AtliQ Hardware

This section summarizes the financial performance of AtliQ Hardware across its main product divisions.

## 🧩 Division-Wise P&L (FY 2021)

All values are in **USD**.

| Division           | Net Sales | COGS     | Gross Margin | GM %   |
|--------------------|-----------|----------|---------------|--------|
| Audio Equipment    | 99.78M    | 60.48M   | 39.30M        | 39.37% |
| Home Appliances    | 103.77M   | 70.87M   | 32.90M        | 31.70% |
| Phone              | 395.34M   | 249.36M  | 145.98M       | 36.92% |

**Filters Applied:**  
- Region: All  
- Market: All  
- Customer: All  


## 📝 Notes
- "GM %" = Gross Margin as a percentage of Net Sales.
- FY 2021 data shown for all divisions.
- Data is rounded to two decimal places and values are in millions.

![ P&L Summary by Division ](https://github.com/ataulmaola/Excel-Finance-Analytics/blob/77dd11ecaf9aabf54cb4b06b997b9515b0933c93/2.png)


### 📌 03 P&L Summary by Market - AtliQ Hardware

This dashboard highlights country-wise financial performance of AtliQ Hardware for FY 2021.


## 🏳️ Market-Wise P&L (FY 2021)

All values are in **USD**.

| Market        | Net Sales | COGS     | Gross Margin | GM %   |
|---------------|-----------|----------|---------------|--------|
| Australia     | 45.14M    | 29.92M   | 15.22M        | 33.70% |
| Bangladesh    | 25.53M    | 17.19M   | 8.34M         | 32.70% |
| China         | 49.34M    | 29.54M   | 19.80M        | 40.13% |
| Germany       | 54.48M    | 34.56M   | 19.92M        | 36.56% |
| India         | 141.48M   | 92.92M   | 48.56M        | 34.31% |
| Indonesia     | 30.48M    | 19.20M   | 11.28M        | 37.00% |
| Japan         | 13.53M    | 8.47M    | 5.06M         | 37.38% |
| Malaysia      | 30.45M    | 19.89M   | 10.56M        | 34.68% |
| Singapore     | 29.59M    | 18.80M   | 10.79M        | 36.45% |
| South Korea   | 13.50M    | 8.25M    | 5.25M         | 38.89% |
| USA           | 100.40M   | 59.17M   | 41.23M        | 41.08% |

**Filters Applied:**  
- Region: All  
- Division: All  
- Customer: All  


## 📝 Notes
- "GM %" = Gross Margin Percentage.
- Data corresponds to FY 2021.
- All amounts are in millions and rounded for readability.

![ P&L Summary by Market ](https://github.com/ataulmaola/Excel-Finance-Analytics/blob/88e302fa4b494fbd3198fe6bccdd5820ae7f99f3/3.png)


### 📌 03 GM by Quarter – Subzone-Level Analysis

# Dashboard 4: GM by Quarter – Subzone-Level Analysis

This dashboard visualizes the GM (Gross Margin ) percentage trends across each quarter of FY 2021 for various subzones within AtliQ Hardware's global operations.

## Key Insights

- Each subzone's GM performance is tracked for Q1, Q2, Q3, and Q4.
- It enables performance benchmarking between subzones across time.
- Aids in identifying seasonal or regional profitability fluctuations.
- Useful for financial planning and zone-specific strategy development.

## Filters Available

- Fiscal Year(FY)  

## Purpose

This view is essential for evaluating profitability dynamics at a granular regional level. It helps stakeholders understand which subzones consistently maintain healthy margins and which need attention.

![ GM by Quarter ](https://github.com/ataulmaola/Excel-Finance-Analytics/blob/1343c141fe10a864ee0a7ba5ee9fc3fde875a53e/4.png)

## 📬 Connect with Me

Thank you for exploring this project.

If you're interested in data analytics, working on similar projects, or hiring for data-related roles, feel free to connect with me:

- 📧 **Email**: ataulmanas@gmail.com  
- 🔗 **LinkedIn**: [Ataul Maola Anas](https://www.linkedin.com/in/ataul-anas/)

This repository is part of my journey in transitioning into the field of data analytics and showcasing hands-on learning through real-world projects.

