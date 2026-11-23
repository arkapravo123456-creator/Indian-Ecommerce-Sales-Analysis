# Indian E-Commerce Sales Analysis

**Author:** Arkapravo Chakraborty  
**Project Type:** Excel-Based Data Analysis and Interactive Dashboard  
**Tools:** Microsoft Excel

---

## Project Overview

The **Indian E-Commerce Sales Analysis** project explores order-level sales data from an Indian e-commerce business and presents key business metrics through an Excel dashboard. The workbook is organised into three worksheets—`Raw_Data`, `Pivot_Data`, and `Dashboard`—to separate the source records, summarized analysis, and visual reporting.

The project is designed to help users review sales and profit performance, compare product categories and Indian states, understand customer and payment patterns, and monitor order fulfilment.

## Project Objectives

- Organise and analyse e-commerce order data in a structured Excel workbook.
- Evaluate sales, profit, order volume, quantity, and customer ratings.
- Compare performance across product categories, states, salespeople, and customer segments.
- Examine monthly sales trends and order-status distribution.
- Present key findings in a consolidated dashboard for easier interpretation.

## Workbook Structure

| Worksheet | Description |
|---|---|
| `Raw_Data` | Contains 300 order-level records and 18 fields, including order ID and date, customer, state and city, region, product category and product, quantity, unit price, sales amount, discount, profit, customer segment, payment method, salesperson, order status, and rating. |
| `Pivot_Data` | Contains summarized analysis, including monthly sales, sales and profit by product category, salesperson performance, customer-segment sales, sales by Indian state, payment-method order counts, and order-status counts. |
| `Dashboard` | Presents headline KPIs and written key insights drawn from the workbook's summarized analysis. |

## Key Performance Indicators

The dashboard is designed around the following metrics:

- **Total Sales** – value of sales recorded.
- **Total Profit** – profit generated from the recorded orders.
- **Total Orders** – number of orders.
- **Total Quantity** – total units ordered.
- **Average Rating** – average customer rating.

## Analysis Areas

The workbook includes the following analysis views:

1. **Monthly Sales Trend** – compares sales across the twelve months shown in the pivot summary.
2. **Product Category Performance** – compares sales and profit across product categories.
3. **Salesperson Performance** – reviews sales and profit totals by salesperson.
4. **Customer Segment Analysis** – compares sales across Consumer, Corporate, and Small Business segments.
5. **State-wise Sales** – compares sales across the Indian states represented in the dataset.
6. **Payment Method Analysis** – compares order counts across payment methods.
7. **Order Status Analysis** – reviews counts for Delivered, Shipped, Cancelled, and Returned orders.

## Key Insights Presented in the Workbook

The dashboard's written insights report that:

- Uttar Pradesh recorded the highest state-wise sales at approximately **₹19.87 lakh**.
- Home Appliances was the leading product category, with approximately **₹70.45 lakh** in sales.
- Home Appliances also recorded the highest category profit, at approximately **₹59.40 lakh**.
- Pooja was identified as the top-performing salesperson by sales, at approximately **₹16.46 lakh**.
- Cash on Delivery was the most-used payment method, accounting for **24%** of orders.
- The dashboard reports that **70.3%** of orders were delivered successfully, while **16%** were cancelled or returned.
- Refrigerators were identified as the highest-selling product, with approximately **₹25.20 lakh** in sales.

These are the findings displayed in the supplied workbook; they have not been independently recalculated for this README.

## Dataset Scope

The supplied workbook contains **300 order records**, with order dates running from **24 November 2026 to 19 September 2027**. The dataset includes records from multiple Indian states, regions, product categories, customer segments, payment methods, and order statuses.

## How to Use the Workbook

1. Open the Excel workbook.
2. Select `Raw_Data` to review the underlying order records.
3. Select `Pivot_Data` to inspect the summarized tables used for analysis.
4. Select `Dashboard` to view the headline metrics and key insights.
5. Use the source and summary sheets together when validating or extending the analysis.

## Data and Dashboard Validation Note

A review of the supplied workbook identified a range mismatch that should be checked before the dashboard is used for official reporting:

- The `Raw_Data` worksheet contains 300 records (rows 2–301).
- The headline KPI formulas on `Dashboard` currently reference only rows **276–301** of `Raw_Data` (the final 26 records).
- The `Pivot_Data` summaries show totals for **300 orders**.
- The dashboard subtitle says **2026**, while the source order dates extend into **2027**.

Consequently, the dashboard KPI cards may not represent the same full dataset as the pivot summaries. Before publishing or relying on the dashboard, update and verify the KPI formula ranges and confirm the reporting period. The written key insights above are transcribed from the workbook and should also be validated against the final corrected data.

## Tools and Skills Demonstrated

- Microsoft Excel
- Structured data organisation
- Spreadsheet formulas and calculations
- Pivot-table-style summary analysis
- KPI reporting
- Dashboard development
- Business data interpretation and insight communication

## Future Improvements

- Correct and validate dashboard KPI formulas against the full dataset.
- Align the dashboard reporting title with the actual reporting period.
- Add interactive filters or slicers for state, category, month, and order status, where appropriate.
- Include additional measures such as average order value, profit margin, and cancellation/return rate.
- Add a brief data-cleaning and validation log to improve transparency and reproducibility.

## Author

**Arkapravo Chakraborty**

This project is presented as an Excel-based e-commerce sales analysis and dashboard portfolio project.
