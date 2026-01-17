# Supermarket Sales Dashboard (Power BI)

## Overview
This project presents a comprehensive Power BI dashboard built using a supermarket (Superstore-style) sales dataset. The dashboard analyzes sales, profit, discount impact, customer segments, and regional performance to support business decision-making.

This project focuses heavily on profit analysis and understanding how discounts and categories impact overall business performance.

---

## Key Insights
- Overall sales, profit, profit margin, and quantity sold
- Sales and profit trends over time
- Category and sub-category performance
- Identification of loss-making sub-categories
- Impact of discounts on profit
- Customer and regional sales distribution

---

## Dashboard Features
- KPI cards for Sales, Profit, Profit Margin, Quantity, and Discount
- Line chart for sales trend over time
- Bar charts for category and sub-category analysis
- Scatter chart to analyze Discount vs Profit
- Map visualization for state-wise sales distribution
- Top 10 customers by sales
- Interactive slicers for Segment, Category, Region, Date, and Ship Mode
- Detailed transaction-level table

---

## Tools & Technologies
- Power BI Desktop
- Power Query for data preparation
- DAX for calculated measures (Profit Margin)
- CSV / Excel dataset

---

## Dataset
The dataset contains:
- Order and ship dates
- Sales, profit, quantity, and discount
- Customer and product details
- Category, sub-category, segment, and region information

---

## Key DAX Measure
```DAX
Profit Ratio = 
DIVIDE(
    SUM('Tableau Superstore'[Profit]),
    SUM('Tableau Superstore'[Sales])
)
