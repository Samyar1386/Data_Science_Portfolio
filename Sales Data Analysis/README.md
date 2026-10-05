# 🛒 Sales Performance & Revenue Analytics

A Python data analysis project (**Pandas, Seaborn, Matplotlib**) evaluating e-commerce sales performance, category revenue contributions, Average Order Value (AOV) metrics, and monthly time-series trend profiling.

---

## 🎯 Key Analytics & Business Questions
1. **KPI Benchmarking:** Compute foundational commercial metrics including Total Revenue, Total Order Count, and Average Order Value (AOV).
2. **Category Performance:** Identify high-performing product verticals (`Clothing`, `Home & Kitchen`) versus lower revenue generators.
3. **Monthly Seasonality:** Analyze month-over-month revenue dynamics to evaluate demand stability across the fiscal year.

---

## 🛠️ Technical Stack & Workflow
- **Data Wrangling:** `pandas` (`groupby`, `to_period`, date parsing, aggregations), `numpy`
- **Visualization:** `seaborn` (`barplot`, `lineplot`), `matplotlib`
- **Feature Engineering:** Calculated item-level revenue (`TotalSales = UnitPrice * Quantity`) and time aggregations (`Month`).

---

## 📊 Business Insights
- **Top Revenue Driver:** The **Clothing** category generated the highest total revenue ($66,730), followed closely by **Home & Kitchen** ($64,734).
- **Average Order Dynamics:** The average revenue per order stood at **$597.85**, indicating multi-item purchasing behaviors.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone (https://github.com/samyar1386/sales-data-analysis.git)