# 🛒 BlinkIT Grocery Sales Analysis Dashboard

An interactive Power BI dashboard analyzing sales performance for BlinkIT (India's last-minute delivery app), built from a grocery outlet dataset of 8,523 records. The dashboard uncovers sales trends across item categories, outlet types, locations, and establishment years to support data-driven business decisions.

## 📊 Dashboard Preview

<img width="1312" height="722" alt="image" src="https://github.com/user-attachments/assets/762fa238-2c72-4500-babb-e1600270c1a9" />


## 📌 Project Overview

This project analyzes grocery sales data to answer key business questions:
- Which item types and outlet types generate the most revenue?
- How does outlet size, location tier, and fat content affect sales?
- What is the sales trend across outlet establishment years?
- Which outlets/items have the highest customer ratings?

## 🎯 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Total Sales | $1.20M |
| Average Sales | $141 |
| Number of Items | 8,523 |
| Average Rating | 3.9 |

## 🧩 Dashboard Features

- **Filter Panel** – Slice data by Outlet Location Type, Outlet Size, and Item Type
- **Multi-view Toggle** – Switch between Total Sales, Avg Sales, No. of Items, and Avg Rating views
- **Fat Content Analysis** – Sales split by Low Fat vs Regular, and by outlet tier
- **Item Type Breakdown** – Sales performance across categories like Fruits & Vegetables, Snack Foods, Dairy, Frozen Foods, etc.
- **Outlet Establishment Trend** – Sales trend line by year (2012–2022)
- **Outlet Size & Location Distribution** – Donut charts for Medium/Small/High size and Tier 1/2/3 location breakdown
- **Outlet Type Summary Table** – Total Sales, No. of Items, Avg Sales, Avg Rating, and Item Visibility by outlet type (Grocery Store, Supermarket Type 1/2/3)

## 🗂️ Dataset

**File:** `BlinkIT_Grocery_Data.csv` / `.xlsx`
**Records:** 8,523 rows | **Columns:** 12

| Column | Description |
|---|---|
| Item Fat Content | Low Fat / Regular |
| Item Identifier | Unique item ID |
| Item Type | Product category (Dairy, Snacks, Frozen, etc.) |
| Outlet Establishment Year | Year the outlet was set up |
| Outlet Identifier | Unique outlet ID |
| Outlet Location Type | Tier 1 / Tier 2 / Tier 3 |
| Outlet Size | Small / Medium / High |
| Outlet Type | Grocery Store / Supermarket Type 1, 2, 3 |
| Item Visibility | % visibility of item on shelf |
| Item Weight | Weight of the item |
| Total Sales | Sales revenue generated |
| Rating | Customer rating |

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard design & DAX measures
- **Excel / CSV** – Data source and cleaning
- **DAX** – Calculated KPIs (Total Sales, Avg Sales, Avg Rating)

## 📁 Repository Structure

├── BlinkIT_Grocery_Data.csv # Raw dataset (CSV format)

├── BlinkIT_Grocery_Data.xlsx # Raw dataset (Excel format)

├── blinkit-power-bi-project.pbix # Power BI project file

├── images required for dashboard # Dashboard images

└── README.md # Project documentation


## 🔍 Key Insights

- Tier 3 outlets generate the highest total sales ($472.13K), followed by Tier 2 ($393.15K) and Tier 1 ($336.40K).
- Supermarket Type 1 dominates revenue with $787.55K in total sales across 5,577 items.
- Regular fat content items outsell Low Fat items across all outlet tiers.
- Fruits & Vegetables and Snack Foods are the top-performing item categories.
- Outlets established in 2018 recorded a peak sales spike ($205K).

## 🚀 How to Use

1. Clone this repository:
```bash
   git clone <your-repo-url>
```
2. Open `blinkit-power-bi-project.pbix` in **Power BI Desktop**.
3. Use the filter panel to explore sales by Outlet Location Type, Outlet Size, or Item Type.
4. Toggle between Total Sales, Avg Sales, No. of Items, and Avg Rating views for different insights.

## 👤 Author

**[Ch.Sai Sireesha]**
[LinkedIn](https://www.linkedin.com/in/sireesha-chinni/)
