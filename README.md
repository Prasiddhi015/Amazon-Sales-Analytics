# Amazon-Sales-Analytics
Analyzed 80,000+ Amazon India orders using Power BI, SQL, Excel and DAX. Covers revenue, fulfillment, returns and B2B vs B2C analysis.


## Project Overview
This project analyzes Amazon India sales data for March to May 2022 
covering 79,353 order records. The goal was to find business insights 
across revenue, orders, fulfillment, returns and customer segmentation.

## Tools Used
- Power BI — Dashboard and visualization
- SQL (MySQL Workbench) — Data validation and analysis
- Microsoft Excel — Data cleaning and preparation
- DAX — Custom measures in Power BI

## Dataset
- Source: Amazon India Sales Data
- Period: March to May 2022
- Total Records: 79,353 rows
- Columns: Order ID, Date, Status, Fulfilment, Sales Channel, 
  Category, Size, Courier Status, Qty, Amount, Ship City, 
  Ship State, B2B, Fulfilled By

## Dashboard Pages
1. Overview — Total revenue, orders, sales trend, order status
2. Revenue — Category wise, state wise, fulfillment wise revenue
3. Orders — Order volume by category, size, state and status
4. Fulfillment — Amazon vs Merchant comparison
5. Returns — Return rate, category and state wise returns
6. B2B vs B2C — Customer segment comparison

## Key Insights Found

**Revenue**
- T-shirt is the top category at 24.52M — contributes 51% of total revenue
- Maharashtra is the highest revenue state at 8.2M
- April was the peak month — revenue dropped 31% in May

**Fulfillment**
- Amazon cancellations (6,400) are higher than Merchant (4,300)
- 100% of returns came from Merchant fulfilled orders
- Amazon fulfilled orders have zero returns

**Returns**
- Overall return rate is only 1.92%
- T-shirt and Shirt make up 78% of all returns
- Every return happened on Standard shipping — zero returns on Expedited

**B2B vs B2C**
- B2B average order value is 749 vs B2C 645 — 16% higher
- B2B is only 0.69% of total orders — big growth opportunity

## Recommendations
1. Reduce Amazon fulfillment cancellation rate
2. Expand Expedited shipping to reduce returns
3. Focus marketing on top 5 states
4. Grow B2B customer segment
5. Fix size guides for T-shirt and Shirt categories
6. Investigate May revenue drop

## How to View the Dashboard
1. Download the `.pbix` file
2. Open it in Power BI Desktop (free download from Microsoft)
3. All 6 dashboard pages will be visible with full interactivity

