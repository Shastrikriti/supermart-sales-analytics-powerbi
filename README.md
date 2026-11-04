# 🛒 SuperMart Sales Analytics Dashboard

An end-to-end sales analysis of a US supermarket chain, built with **Excel** and **Microsoft Power BI**. The dashboard turns 5,901 order lines (2019–2020) into one interactive page covering sales, profit, quantity, delivery speed, payment behaviour and geography.

## 📌 Project Overview
- **Goal:** find what drives sales and profit, and where margin is being lost
- **Data:** `SuperMart_sales_datatset.xlsx`: 5,901 rows × 21 columns, 3,003 orders, 773 customers, 49 states
- **Period:** 1 Jan 2019 – 31 Dec 2020
- **Dashboard:** `Dashboard_SuperMart.pbix`: one page with 6 KPI cards, 3 donut charts, 2 area charts, bar, column, funnel and map visuals, plus a Region slicer

## 📊 Key Metrics
| Metric | Value |
|---|---|
| Total Sales | $1,565,804 |
| Total Profit | $175,262 |
| Profit Margin | 11.2% |
| Total Quantity | 22,317 units |
| Average Sale (per line) | $265.35 |
| Average Delivery Time | 3.9 days |

## 🔍 Key Insights
- Sales grew **77%** in 2020, but profit grew only **14%**, so margin fell from 14.5% to 9.3%.
- **Technology** has the best margin (19.2%); **Furniture** earns just 2.2%.
- **Tables, Supplies and Bookcases** are loss-making sub-categories.
- **West** leads in sales and margin; **Central** has the weakest margin (8.0%).
- **California** is the top state ($335K), followed by New York and Texas.
- **Cash on delivery** is the largest payment mode (43% of sales).

## 🧩 Dashboard Contents
KPI cards (Avg Sale, Avg Profit, Avg Quantity/State, Avg Delivery Days, Quantity by Category and Sub-Category) · Sales by Region, Payment Mode and Segment (donuts) · Sales and Profit trends (area) · Sales by Ship Mode, Category and Sub-Category · Sales & Profit by State (map) · Region slicer

## 🗂️ Repository Structure
```
├── SuperMart_sales_datatset.xlsx     # Source dataset
├── Dashboard_SuperMart.pbix          # Power BI dashboard
├── SuperMart_Documentation.pdf       # Full documentation (PDF)
└── README.md
```

## ▶️ How to Use
1. Clone or download this repository.
2. Open `Dashboard_SuperMart.pbix` in **Power BI Desktop**.
3. If prompted, point the data source to your local copy of the Excel file.
4. Use the **Region** slicer to filter all visuals.

## 🛠️ Tools
Microsoft Excel · Microsoft Power BI (data modelling, DAX, visuals) · Python/pandas (documentation analysis)

## 📸 Screenshot
<img width="1352" height="772" alt="image" src="https://github.com/user-attachments/assets/7b8c1bab-036d-416a-ac70-1e8bfb1ff411" />


## Author

[Kriti Shastri] · [https://github.com/Shastrikriti]
