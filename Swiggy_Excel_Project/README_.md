# 🍊 Swiggy India Sales Dashboard | Excel

> An end-to-end Excel analytics project on 1,97,430 Swiggy orders across India — from raw data to an interactive dashboard with slicers, pivot-based analysis, and business insights.

---

## 📸 Dashboard Preview

![Swiggy India Sales Dashboard](dashboard_preview.png)

---

## 📁 Project Structure


```
03_Excel_Swiggy_Dashboard/
├── Swiggy_Raw_Data_Excel.xlsx   ← Source data + Analysis + Dashboard (all-in-one)
├── dashboard_preview.png        ← Dashboard screenshot
└── README.md
```

### Workbook Sheets

| Sheet | Description |
|---|---|
| `Swiggy Data` | Raw dataset — 1,97,430 rows × 13 columns |
| `Analysi` | Pivot tables & aggregations (KPIs, breakdowns) |
| `Dashboard` | Interactive dashboard with slicers |
| `Detail1` | Supporting pivot — Rating analysis by city/state |
| `Sheet2` | Category-level sales summary |

---

## 📊 Dataset Overview

| Field | Detail |
|---|---|
| Source | Swiggy India (simulated transactional dataset) |
| Period | January 2025 – August 2025 |
| Total Records | 1,97,430 orders |
| Geography | Pan-India — multiple states, regions, and cities |
| Columns | State, Region, City, Order Date, Day, Restaurant Name, Location, Category, Dish Name, Food Category, Price (INR), Rating, Rating Count |

---

## 🔢 Key Metrics

| Metric | Value |
|---|---|
| Total Sales | ₹5.30 Cr |
| Total Orders | 1,97,430 |
| Average Order Value | ₹268.51 |
| Average Rating | 4.34 |
| Total Rating Count | 55.9L |

---

## 💡 Key Insights

**1. Bengaluru is the undisputed sales capital**
At ₹54.6L, it leads the next city (Lucknow, ₹31.2L) by a massive margin — reflecting both order volume and higher-priced restaurant options.

**2. Veg dominates — 67.9% of total revenue**
Vegetarian orders (1,42,736) outnumber Non-Veg (54,694) by 2.6x. Veg contributes ₹3.60Cr vs Non-Veg's ₹1.70Cr — a clear signal for menu strategy.

**3. Saturday is peak order day**
Saturday clocks ₹77.8L — the highest of any day. Interestingly, weekday demand is remarkably stable (Mon–Fri range: ₹73.6L–₹76.6L), suggesting habitual ordering behaviour beyond just weekends.

**4. North region leads all four zones**
North: ₹1.66Cr > West: ₹1.31Cr > South: ₹1.24Cr > East: ₹1.09Cr. Despite South having the top city (Bengaluru), the North's distributed city contribution pushes it ahead overall.

**5. January peak, February dip**
Best month: January (₹68.3L). Weakest: February (₹62.7L) — a 8.3% drop, likely driven by the shorter month and post-holiday slowdown.

**6. KFC is the top-earning restaurant chain**
KFC: ₹42.5L → McDonald's: ₹33.4L → Pizza Hut: ₹21.3L → Burger King: ₹19.0L → Domino's: ₹18.3L. QSR chains collectively dominate the revenue leaderboard.

**7. Kochi leads on customer satisfaction**
Highest average rating: Kochi (4.44), followed by Kolkata (4.41) and Aizawl (4.41) — while high-sales cities like Bengaluru and Delhi rank lower on satisfaction.

---

## 🛠️ Tools & Techniques

- **Microsoft Excel** — entire project built end-to-end
- **Pivot Tables** — multi-dimensional aggregations (by city, state, region, day, month, category)
- **Dynamic Slicers** — Month, Food Category, State filters connected to all visuals
- **Named Navigation Buttons** — clickable links between Data, Analysis, and Dashboard sheets
- **Charts** — Line (monthly trend), Bar (category, regional, daily, city rankings)
- **KPI Cards** — custom formatted metric tiles
- **Dashboard Design** — dark theme, Swiggy brand colors, single-accent color discipline

---

## 🎯 Business Questions Answered

1. Which city and region generates the most revenue?
2. Does food category (Veg/Non-Veg) significantly impact sales volume?
3. Which day of the week drives peak orders?
4. How does monthly sales trend across the year?
5. Which restaurant chains dominate the platform?
6. Is there a gap between high-revenue cities and high-rated cities?

---

## 🔗 More Projects

| Project | Description |
|---|---|
| [SQL — Northwind](../01_SQL_Northwind/) | Complex SQL queries on Northwind DB — JOINs, subqueries, window functions |
| [Python EDA — Olist](../02_Python_EDA_Olist/) | E-commerce EDA using NumPy, Pandas, Matplotlib, Seaborn |
| [Power BI Dashboard](../04_PowerBI_Dashboard/) | *(Coming soon)* |

---

## 👤 Author

**Govind Aal**
B.Com (Finance & Accounting) | Data Analyst
🔗 [LinkedIn](https://www.linkedin.com/in/aalgovind05) · [GitHub](https://github.com/aalgovind05)
