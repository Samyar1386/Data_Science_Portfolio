# 👥 Employee Attrition & Workforce Retention Analytics

A Python data analysis project (**Pandas, Seaborn, Matplotlib**) evaluating IBM HR Analytics metrics, employee attrition drivers, income disparities, and workload stress impact (`OverTime`).

---

## 🎯 Project Objectives & Core Questions
1. **OverTime Impact Analysis:** Measure attrition rate multipliers across employee groups working structural overtime.
2. **Compensation Thresholds:** Compare mean and median monthly incomes of retained vs. departed personnel.
3. **Satisfaction Matrix Breakdown:** Pivot attrition rates across multi-variable categorical intersections (`JobSatisfaction` vs. `OverTime`).

---

## 🛠️ Technical Stack & Methods
- **Data Manipulation:** `pandas` (`groupby`, `agg`, `unstack`, binary target creation), `numpy`
- **Visualization:** `seaborn` (`barplot`, `boxplot`), `matplotlib`
- **Data Preprocessing:** Filtering zero-variance columns (`EmployeeCount`), target string-to-binary mapping.

---

## 📊 Key Insights
- **Overtime Risk Factor:** Employees working overtime present an attrition rate exceeding **30%**, roughly 3x higher than non-overtime staff.
- **Pay Differential:** Departed employees exhibit a significantly lower median monthly income (~$3,200) compared to retained counterparts (~$5,200).

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone (https://github.com/samyar1386/hr-attrition-analytics.git)