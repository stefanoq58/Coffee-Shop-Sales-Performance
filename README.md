# Coffee-Shop-Sales-Performance
A Data Analytics Project Using Excel, Power Query &amp; PivotTables
---

## Overview
The objective of this project was to analyze a full year of café transaction data and uncover insights related to revenue trends, item performance, customer purchasing behavior, and operational patterns. 

Using Excel as the primary analytics environment, the project focused on transforming a large raw transactional dataset into a clean, interactive dashboard that highlights key business metrics, including total revenue, transaction volume, item popularity, and monthly performance trends. 

The final deliverable is a fully interactive Excel dashboard powered by slicers, KPI cards, and PivotCharts, enabling users to explore sales behavior across items, months, locations, and payment methods.

Data Source extracted from Kaggle: https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training/code

---

## Objectives
The project aimed to:
- Clean and standardize raw café transaction data for accurate reporting
- Analyze revenue generation across different menu items
- Identify which items drive the highest number of transactions
- Evaluate monthly sales performance and spending patterns
- Understand customer behavior through average transaction value trends
- Build an interactive dashboard that allows dynamic filtering by item, month, location, and payment method
- Present insights in a visually clear and business‑ready format
---

## Tools & Technologies
- **Data Source** - A transactional dataset containing:
  - Transaction IDs
  - Items purchased
  - Quantity and price per unit
  - Total spent
  - Payment method
  - Location (In‑store, Takeaway, Other)
  - Transaction date and derived month
- **Excel Formulas & Data Modeling**
  - Filled NA values using a structured, dependency‑based approach with nested IF formulas, ensuring quantities, prices, and totals were only completed when mathematically valid.
  - Established logical links across related fields (e.g., Qty × Price = Total) to prevent data corruption and maintain PivotTable accuracy.
  - Created month grouping using TEXT() to convert dates into consistent month labels for chronological analysis.
- **Power Query (Excel)** - Used for data cleaning and preparation:
  - Removed rows containing ambiguous or invalid values (e.g., “Unknown”)
  - Ensured consistent categorical values across items, locations, and payment methods
  - Validated numeric fields and corrected inconsistencies
  - Loaded the cleaned dataset into an Excel table for analysis
- **Excel PivotTables & PivotCharts** - Used to build the interactive dashboard:
  - KPI cards highlight total revenue and total transactions
  - Bar charts compare revenue by item and item popularity
  - Line chart visualizes average transaction value trends across months
  - Column chart shows monthly revenue performance
  - Slicers allow filtering by item, month, location, and payment method
---

## Key Insights
Based on 9,044 transactions and $79,921 in total revenue, the analysis reveals several meaningful business insights:
1. Salad is the top revenue‑generating item
    - Salad produced $18,200, the highest among all items
    - Sandwiches and smoothies also performed strongly, generating $13,068 and $12,776, respectively
2. Coffee is the most frequently purchased item
    - Coffee appears in 1,234 transactions, making it the most popular item by volume
    - Salad, cookie, and tea also show strong transaction counts
3. Monthly revenue is stable with a peak in October
    - October generated the highest monthly revenue at $7,040
    - Most months fall between $6,100–$6,900, indicating consistent customer demand
4. Average Transaction Value (ATV) remains steady
    - ATV ranges from $8.64 to $9.20 throughout the year
    - April shows the highest ATV at $9.20, suggesting higher‑value purchases during that period
5. Payment methods and locations show diverse customer behavior
    - Customers use a mix of cash, credit cards, and digital wallets
    - In‑store purchases dominate, but takeaway and “other” locations contribute meaningfully
---

## Conclusion
This project demonstrates the ability to transform raw transactional data into a polished, interactive dashboard that supports business decision‑making. Through data cleaning/standardization, PivotTable modeling, and thoughtful dashboard design, the analysis provides clear insights into item performance, customer behavior, and revenue trends.
The final dashboard enables café managers or stakeholders to quickly answer questions such as:
- Which items drive the most revenue?
- Which items are most frequently purchased?
- How does revenue vary month‑to‑month?
- What is the average customer spend?
- How do payment methods and locations influence sales?
  
This project showcases strong skills in data cleaning, Excel analytics, dashboard design, and business insight generation.

---

## Visual Dashboard Preview
![Coffe_Sales_Dashboard](<img width="1934" height="897" alt="image" src="https://github.com/user-attachments/assets/7b4110c7-ae19-44e2-b650-99b89037bba5" />
)

