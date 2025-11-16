# 📊 Data-Visualization-Dashboard-Using-Power-BI

This project demonstrates how to build a compelling Data Visualization dashboard using **Power BI** and communicate insights through effective visual storytelling.

---

## 🎯 Task Objective
- Create clear and meaningful visualizations
- Highlight key business insights
- Focus on data storytelling, not just charts
- Deliver visual report (dashboard screenshots)

Dataset used: **Sales_Dataset_2024_cleaned.csv**

---

## 🛠 Tools Used
| Tool | Purpose |
|------|--------|
| Power BI | Dashboard & Data Visualization |
| DAX | Measures & Calculations |
| GitHub | Version control & project hosting |
| CSV Dataset | Sales data used for analysis |

---

## 📌 Dashboard Features
✔ KPI Cards (Revenue, Profit, Units Sold, Margin%)  
✔ Monthly Revenue Trend (Line Chart)  
✔ Revenue by Region (Bar Chart)  
✔ Top 10 Products by Revenue (Horizontal Bar)  
✔ Category Profitability (Bar/Donut Chart)  
✔ Salesperson Performance Ranking  
✔ Slicers for interactive filtering

---

## 📈 Core DAX Measures
```DAX
Total Revenue = SUM('Sales_Dataset_2024_cleaned'[Revenue])
Total Profit = SUM('Sales_Dataset_2024_cleaned'[Profit])
Total Units = SUM('Sales_Dataset_2024_cleaned'[Units_Sold])
Avg Price per Unit = AVERAGE('Sales_Dataset_2024_cleaned'[AvgPricePerUnit])
Profit Margin = DIVIDE([Total Profit], [Total Revenue], 0)
