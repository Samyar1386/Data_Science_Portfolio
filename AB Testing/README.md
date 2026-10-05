# 🧪 A/B Testing & Statistical Hypothesis Analytics

A Python data analysis project (**Pandas, Seaborn, Matplotlib, Pure Python Math**) evaluating landing page design variations, user conversion rates, two-proportion Z-tests, and p-value statistical significance.

---

## 🎯 Key Analytics & Business Questions
1. **Conversion Benchmarking:** Calculate baseline conversion rates between `Control` ($N=25,053$) and `Treatment` ($N=24,947$) groups.
2. **Hypothesis Testing:** Conduct a two-sample Z-test for proportions to evaluate whether observed uplift is statistically significant ($p < 0.05$).
3. **Business Recommendation:** Provide data-backed recommendations on deploying the new feature/landing page version to production.

---

## 🛠️ Technical Stack & Workflow
- **Data Manipulation:** `pandas` (`groupby`, `agg`), `numpy`
- **Statistical Analytics:** Pure Python mathematical error functions (`math.erf`, `z-score` pooling) to bypass C-library dependency restrictions.
- **Visualization:** `seaborn` (`barplot`), `matplotlib`

---

## 📊 Key Results & Insights
- **Baseline Uplift:** Conversion rate increased from **11.73%** (Control) to **12.47%** (Treatment).
- **Statistical Significance:** Z-score of **2.5619** yielded a p-value of **0.01041** ($p < 0.05$), confirming a statistically significant improvement with 95%+ confidence.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone (https://github.com/samyar1386/ab-testing-analytics.git)