# 📈 Multi-Channel Marketing Campaign & ROI Analytics

A Python data analysis project (**Pandas, Seaborn, Matplotlib**) evaluating marketing performance metrics including Return on Investment (ROI), Customer Acquisition Cost (CAC), Click-Through Rate (CTR), and multi-channel budget allocation efficiencies.

---

## 🎯 Key Analytics & Business Questions
1. **Channel Efficiency:** Compare acquisition and revenue capabilities across `Google Ads`, `Meta Ads`, `Email Marketing`, `Influencer`, and `Organic Search`.
2. **Financial Metrics:** Compute critical performance metrics:
   - $\text{CTR (\%)} = (\frac{\text{Clicks}}{\text{Impressions}}) \times 100$
   - $\text{CAC} = \frac{\text{Total Spend}}{\text{Acquisitions}}$
   - $\text{ROI (\%)} = (\frac{\text{Revenue} - \text{Spend}}{\text{Spend}}) \times 100$
3. **Budget Optimization:** Recommend strategic budget reallocation to maximize portfolio-level revenue.

---

## 🛠️ Technical Stack & Workflow
- **Data Manipulation:** `pandas` (`groupby`, `agg`, custom conditional logic), `numpy`
- **Visualization:** `seaborn` (`barplot`), `matplotlib`
- **Feature Engineering:** Calculated unit economics ($CAC, CTR, ROI$).

---

## 📊 Key Results & Insights
- **Top ROI Channel:** **Google Ads** delivered the highest overall ROI (**2,221.55%**) with over **$2.33M** in total generated revenue.
- **Most Cost-Effective Acquisition:** **Meta Ads** recorded the lowest CAC (**$19.68/acquisition**) while scaling high volume (9,284 acquisitions).

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone (https://github.com/samyar1386/marketing-campaigns-analysis.git)