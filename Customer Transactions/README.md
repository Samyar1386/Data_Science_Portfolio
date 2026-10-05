# 💳 Customer Transactions & Payment Gateway Analytics

A Python data analysis project (**Pandas, Seaborn, Matplotlib**) evaluating financial payment gateway performance, transaction success/failure ratios, payment channel volume distributions, and transaction outlier profiling.

---

## 🎯 Key Analytics & Business Questions
1. **Gateway Health Profiling:** Measure transaction clearance efficiency through Success, Failure, and Refund rate breakdowns.
2. **Payment Channel Dominance:** Compare total settlement volumes across Credit Card, Debit Card, PayPal, Bank Transfer, and Crypto channels.
3. **Anomaly Identification:** Detect high-value transaction outliers across payment status classifications using distribution plots.

---

## 🛠️ Technical Stack & Workflow
- **Data Wrangling:** `pandas` (`groupby`, `value_counts` with normalization, `agg`), `numpy`
- **Visualization:** `seaborn` (`barplot`, `boxplot`), `matplotlib`
- **Data Modeling:** Exponential transaction amount modeling and status frequency distributions.

---

## 📊 Business Insights
- **Payment Dominance:** **Credit Card** transactions comprise the largest volume segment (**$67,469.88** across 407 transactions).
- **Failure Friction:** An overall **12.9% failure rate** and **5.9% refund rate** highlight technical or fraud-prevention friction requiring gateway optimization.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone (https://github.com/samyar1386/customer-transactions-analysis.git)