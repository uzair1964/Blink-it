# Blink-it Dashboard 📊
## 🧭 Introduction
This repository contains a **Blinkit sales performance** analytics project. It focuses on cleaning sales data (Excel/Power Query), shaping it (optional SQL), and building an interactive **Power BI** dashboard.  
It helps stakeholders track **annual sales**, **category-wise contribution**, **top products**, and **basic nutrition/product attributes**, with slicers and drill-downs for fast decision-making.

## 🛠️ Project Type
Backend Analytics / BI (Excel + Power BI; optional SQL for data shaping)

## 🚀 Deployed App
- Frontend: Not applicable  
- Backend: Power BI Desktop (`.pbix`)  
- Data Source: CSV/Excel (and/or SQL export)


## 🚀 Dashboard Features:
## ✨ Features
- **KPI cards:** revenue, orders, AOV, margin (if available)  
- **Trends:** MoM/YoY sales and order count  
- **Category & product analysis:** top categories/SKUs, % contribution, Pareto (80/20)  
- **Interactive filters:** date, category, city/region, channel  
- **(Optional) Nutrition/attributes:** compare items by calories/weight if present in dataset  
- **Clean data pipeline:** Excel/Power Query steps documented; SQL script provided for reproducible shaping

### 📍 **Tier-wise Performance Breakdown:**
- **Outlet location filter**: Categorizes data by tier (Tier 1, 2, 3).
- Shows how each tier contributes to **total sales** and **item availability**.
- **Top-performing tier**: **Tier 3** recorded the highest total sales: **$472.13K**.

### 🏪 **Outlet Size Analysis:**
- **Pie chart** visualizing sales by **outlet size** (Small, Medium, Large).
- **Medium-sized outlets** contributed the most to total sales: **$507.90K**.

### 📅 **Outlet Establishment Trend:**
- **Line chart** showcasing sales growth or decline from **2010 to 2020**.
- **Peak sales** recorded in **2019**: **$205K**.

### 🍴 **Item Type Analysis:**
- **Bar chart** displaying average ratings across different **item types**.
- **Top-rated items** include: Meat, Breakfast, Seafood, with **ratings** above 4.0.

### 🥑 **Fat Content Insight:**
- **Doughnut chart** comparing low-fat vs regular item proportions.
- **Ratings** are consistent across fat content categories.

### 🔍 **Outlet Type Comparison Table:**
- A comparison of **sales and performance metrics** across various outlet types.

---

## 💡 Key Insights:
- **Tier 3 outlets** showed the highest total sales, while **medium-sized outlets** contributed significantly to the overall performance.
- **Sales peak** in 2019 highlights a significant growth period.
- **High-rated items** (Meat, Breakfast, Seafood) indicate customer preference for quality products.

---

Feel free to explore the dashboard and check out these insights visually!

🔗 **Project Link**: [Insert Link Here]

---

## 🎯 Design Decisions & Assumptions
- The dataset is stored locally in `data/raw/`. Update the **Power BI** data source path on first open.  
- Missing values handled via Power Query (type conversions, deduping, simple imputations).  
- DAX kept simple (YoY/MoM, % contribution).  
- If SQL is used, `sql/queries.sql` shows basic transformations before loading to Power BI.

## 🧪 Installation & Getting Started
1) **Clone the repo**
```bash
git clone https://github.com/uzair1964/Blink-it
cd Blink-it
### 🚀 Technologies Used:
- **Power BI**: For dashboard creation and data visualization.
- **Excel**: Data processing and analysis.
- **DAX**: Advanced calculations for filtering and analysis.

---

## 🔧 How to Use:
1. Clone the repository.
2. Open the `.pbix` file in Power BI.
3. Interact with the dashboard to explore the insights.

---

### 📩 Contact:
If you have any questions or need further assistance, feel free to reach out at [Your Contact Info].

---

### 🌟 Contributions:
Contributions are welcome! Feel free to fork the repo, submit issues, and make pull requests. Let's make this project even better!

