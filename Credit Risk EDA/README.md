# 💳 Credit Risk Assessment & Banking Default Analytics

An in-depth Python data analysis project (**Pandas, Seaborn, Matplotlib**) evaluating commercial credit application data, default probability determinants, financial feature engineering, log-scale transformations, and age cohort risk profiling.

---

## 🎯 Key Analytics & Business Questions
1. **Default Risk Profiling:** Determine critical risk drivers across credit grades (`loan_grade`), intent categories (`loan_intent`), and age cohorts.
2. **Financial Ratio Engineering:** Construct `loan_to_income_ratio` and `income_per_emp_year` metrics to identify unsustainable debt exposure.
3. **Logarithmic Scaling:** Apply log-scale distributions to analyze income disparities between defaulted and non-defaulted loan accounts.

---

## 🛠️ Technical Stack & Workflow
- **Data Wrangling:** `pandas` (`cut` binning, `pivot_table`, `transform`, `describe`), `numpy`
- **Feature Engineering:** Ratio metrics, logarithmic axis mapping, categorical age binning.
- **Data Visualization:** `seaborn` (`heatmap`, `boxplot` with log scale, `barplot`, `scatterplot`), `matplotlib`

---

## 📊 Business Insights
- **Grade Transition Risk:** A steep default risk increase occurs when moving from Grade C (~30%) to Grade D (~60%) across all loan intents.
- **Age Cohort Vulnerability:** Senior and retired cohorts exhibit significantly higher default rates when combined with lower credit grades.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone (https://github.com/samyar1386/credit-risk-eda.git)