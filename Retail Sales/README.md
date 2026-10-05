# 🛍️ Retail Sales Performance & Demographic Analytics

A Python data analysis project (**Pandas, Seaborn, Matplotlib**) evaluating retail sales dataset metrics, multi-dimensional pivot table summaries, customer demographic traits (Age & Gender), and monthly revenue seasonality trends.

---

## 🎯 Project Objectives & Core Questions
1. **Multi-Dimensional Pivot Aggregation:** Utilize `pivot_table` to cross-examine `Total Amount` sums and `Age` means across categorical intersections (`Product Category` vs. `Gender`).
2. **Seasonality Mapping:** Measure monthly sales progression across a 12-month cycle using explicit chronological reindexing.
3. **Demographic Profiling:** Identify top revenue-generating product verticals alongside customer demographic compositions.

---

## 🛠️ Technical Stack & Methods
- **Data Manipulation:** `pandas` (`pivot_table`, `groupby`, `dt` month/day parsing, `reindex`), `numpy`
- **Visualization:** `seaborn` (`barplot`, `lineplot`), `matplotlib`
- **Data Preprocessing:** Datetime casting, feature creation (`Total Amount = Quantity * Price`), missing value checks.

---

## 📊 Key Insights
- **Category Leaders:** **Electronics** and **Clothing** generate the majority share of total store revenue.
- **Demographic Uniformity:** Buyer age profiles exhibit steady distributions across all product verticals (mean age ~40–45 years).

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
     git clone (https://github.com/samyar1386/retail-sales-analysis.git)