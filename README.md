# 🛒 Blinkit Grocery Sales Dashboard – Power BI Project

## 📌 Objective

To conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution using Power BI. This dashboard helps identify key business insights and opportunities for optimization based on various KPIs and interactive visualizations.

---

## 📁 Project Files

- `Dataset.xlsx` – Contains raw sales and inventory data  
- `Blinkit Grocery Data Analysis.pbix` – Power BI file with dashboard and visuals  
- `README.md` – Project documentation

---

## 📊 Business KPIs

| KPI                | Description                                               |
|--------------------|-----------------------------------------------------------|
| **Total Sales**     | Overall revenue generated from all items sold             |
| **Average Sales**   | Average revenue per sale                                  |
| **Number of Items** | Count of different items sold                             |
| **Average Rating**  | Average customer rating for items sold                    |

---

## 📈 Visualizations

1. **Total Sales by Fat Content** – Donut chart analyzing impact of fat content (Low Fat, Regular) on sales, along with other KPIs  
2. **Sales by Item Type** – Stacked Bar chart showing item-wise performance in terms of revenue, quantity, and rating  
3. **Fat Content by Outlet** – Clustered bar chart comparing fat content sales across outlets  
4. **Sales by Outlet Establishment Year** – Line chart evaluating outlet age impact on sales  
5. **Sales by Outlet Size** – Donut chart analyzing how outlet size (Small, Medium, Large) affects total sales  
6. **Sales by Outlet Location** – Funnel chart showing geographic sales distribution (Tier 1, Tier 2, Tier 3)  
7. **Outlet Type Metrics** – Matrix card showing all KPIs by outlet type (Supermarket Type 1, 2, 3, Grocery Store)

---

## 🗃 Dataset Overview

| Column Name              | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `Item Fat Content`       | Type of fat (Regular, Low Fat)                                              |
| `Item Identifier`        | Unique code for item                                                        |
| `Item Type`              | Category of item (e.g. Fruits, Frozen Foods, Hygiene, etc.)                 |
| `Outlet Establishment Year` | Year the outlet started operating                                      |
| `Outlet Identifier`      | Unique outlet code                                                          |
| `Outlet Location Type`   | Tier-based location classification (Tier 1–3)                               |
| `Outlet Size`            | Store size (Small, Medium, Large)                                           |
| `Outlet Type`            | Type of store (Supermarket Type 1/2/3, Grocery Store)                       |
| `Item Visibility`        | Relative visibility/popularity of item                                      |
| `Item Weight`            | Item weight in grams or kilograms                                           |
| `Sales`                  | Sales amount for the item                                                   |
| `Rating`                 | Customer rating for each item                                               |

> 📊 The dataset contains 8,000+ rows and 12 columns.

---

## 🔍 Insights Uncovered

- Items with **Low Fat** generated more sales volume than Regular items.  
- **Fruits and Vegetables** and **Snack Foods** are top-performing item types.  
- Sales are **highest in Tier 3 cities**, and medium/large outlets perform better.  
- **Supermarket Type 1** stores dominate sales across all KPIs.  
- **Outlet establishment year** shows that 2018 established stores shown stronger performance 

---

## 🛠 Tools Used

- **Power BI**  
  - Data modeling  
  - Measures (DAX)  
  - Interactive charts  
  - Drill-downs & tooltips  

---

## 🚀 How to Use

1. Open `Blinkit Grocery Data Analysis.pbix` in Power BI Desktop  
2. Interact with filters and visuals to explore metrics  
3. Use tooltips and drill-downs for deeper insights

---

## 📦 Repository Structure (Recommended)

