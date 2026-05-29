# Coffee Shop Sales Analysis

**Author:** Chinmay Kumar Gupta

**Tool:** Microsoft Excel (Pivot Tables, Charts, KPIs, Slicers)

---

## About This Project

The goal was to analyse retail sales data from a coffee shop chain to find actionable insights that can improve business performance. I worked with a raw transaction dataset, cleaned and enriched it in Excel, and built an interactive dashboard to answer key business questions.

---

## Dataset

The raw data had around 149,116 transactions across 3 store locations — Astoria, Hell's Kitchen, and Lower Manhattan — covering January to June.

| Column | Description |
|---|---|
| transaction_id | Unique transaction ID |
| transaction_date | Date of purchase |
| transaction_time | Time of purchase |
| transaction_qty | Number of items ordered |
| store_location | Store name |
| product_category | Category (Coffee, Tea, Bakery, etc.) |
| product_type | Specific type (Barista Espresso, Hot Chocolate, etc.) |
| unit_price | Price per item |
| Total_price | Qty x Unit price (calculated column) |

**Columns added during analysis:**
`Hour`, `Day Name`, `Month Name`, `Size`, `Total_price`

---

## Questions Answered

1. How do sales vary by day of the week and hour of the day?
2. Are there any peak times for sales activity?
3. What is the total sales revenue for each month?
4. How do sales vary across different store locations?
5. What is the average bill per person and average orders per person?
6. Which products are best-selling by quantity and revenue?
7. How do sales vary by product category and type?

---

## Key Findings

- **Total Revenue:** $698,812.33 across 149,116 transactions
- **Peak hours:** 9 AM and 10 AM have the highest order volume — morning rush drives most revenue
- **Best day:** Weekdays (Monday to Friday) consistently outperform weekends
- **Top location:** Hell's Kitchen leads with $236,511.17 — slightly ahead of the other two stores
- **Top category:** Coffee makes up 39% of all sales, followed by Tea at 28%
- **Best product:** Barista Espresso is the top seller by both quantity and revenue
- **Average bill per person:** $4.69 with 1.44 orders per visit on average
- **Size trend:** 61% of orders are "Not defined" size — mostly espresso-based drinks

---

## Dashboard

The Excel dashboard includes:
- Line chart — Quantity ordered by hour (peak time analysis)
- Pie chart — Sales distribution by product category
- Pie chart — Size distribution based on sales
- Bar chart — Sales and footfall by store location
- Bar chart — Top 5 products by revenue
- Bar + Line combo — Orders by weekday
- Slicers — Filter by month (Jan–Jun) and day name

![Dashboard Preview](Screenshot_2026-05-27_235651.png)

---

## Files in This Repository

| File | Description |
|---|---|
| `Raw_Data_of_Coffee_Shop_Sales.xlsx` | Original raw transaction data |
| `Cofee_shop_Sales.xlsx` | Cleaned data + pivot tables + dashboard |
| `Coffee_Shop_Sales_Analysis.pdf` | Project objective and analysis questions |
| `Screenshot_2026-05-27_235651.png` | Dashboard preview image |

---

## Skills Demonstrated

`Excel` `Pivot Tables` `Slicers` `KPI Cards` `Line Chart` `Bar Chart` `Pie Chart` `Data Cleaning` `Calculated Columns` `Business Analytics` `Data Storytelling`
