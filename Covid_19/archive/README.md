# 🦠 COVID-19 Time-Series Data & Mortality Analytics

A Python data analysis project (**Pandas, Seaborn, Matplotlib**) evaluating COVID-19 cumulative progression metrics, time-series line plotting, country-level aggregations (`groupby` max), and handling division-by-zero anomalies in cumulative rates.

---

## 🎯 Project Objectives & Core Questions
1. **Cumulative Aggregation:** Extract final cumulative counts for confirmed, death, and recovery metrics using `groupby` with `max`.
2. **Time-Series Progression:** Track daily trajectory curves of virus spread across major affected regions.
3. **Mortality Rate Profiling:** Compute and compare country-specific death-to-confirmed ratios (`Final_Mortality_Rate (%)`).

---

## 🛠️ Technical Stack & Methods
- **Data Manipulation:** `pandas` (`groupby`, `agg`, `to_datetime`, sorting), `numpy`
- **Visualization:** `seaborn` (`lineplot`, `barplot`), `matplotlib`
- **Data Preprocessing:** Datetime casting, handling zero-division anomalies (`inf` replacement).

---

## 📊 Key Insights
- **Mortality Divergence:** Final mortality rates range from **0.90% (Turkey)** to **2.87% (UK)** among top-affected countries.
- **Trajectory Differences:** Linear vs. exponential growth trajectories highlight regional policy and testing differences.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone (https://github.com/samyar1386/covid19-time-series-analysis.git)