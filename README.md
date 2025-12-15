# 📈 Global Sales and Forecast Performance Dashboard

This Power BI dashboard provides a comprehensive view of **Actual Sales** compared against the **Forecast (P50)**. It allows users to analyze performance across key dimensions, including geography, product categories (Sport, Silhouette), sales organizations, and gender. The time-series data spans from 2025 into 2027 and includes long-term forecast projections up to 2028.

---

## 🔑 Key Metrics and Objectives

The primary goal of this dashboard is to track two core metrics:

1.  **Actual Sales:** Realized revenue over time.
2.  **Forecast P50:** The projected sales based on a 50% probability (P50) of achievement.

### **Time Range Covered**
* **Actuals/Monthly Forecast:** January 2025 – Dec 2028
* **Confidence Interval Forecast:** 2025 – 2028

---

## 🗺️ Dashboard Visualizations and Breakdown

The dashboard is organized into distinct sections to provide both detailed breakdowns and high-level time-series analysis.

### I. Geographical and Categorical Breakdown (Left Panel)

This section focuses on the distribution of the **FORECAST\_P50** across various structural categories:

| Visualization | Focus | Key Categories Shown |
| :--- | :--- | :--- |
| **Count of Region by Country and Country (Map)** | Geographical activity and data source locations. | North America, Mexico, Japan, Hong Kong, China, Australia. |
| **Sum of FORECAST\_P50 by SALESORG** | Forecast distribution by internal sales structure. | United States, Mexico, Others. |
| **Sum of FORECAST\_P50 by SPORT** | Forecast distribution by product line/sport category. | Baseball, PP-Novo, Football. |
| **Sum of FORECAST\_P50 by GENDER** | Forecast distribution by demographic. | Boys, Girls, Ladies. |

### II. Time-Series and Financial Analysis (Right Panel)

This section provides the overall financial picture and performance over time:

| Visualization | Description | Key Insight |
| :--- | :--- | :--- |
| **Actual Sales vs. Forecast P50 (Year and Month)** | A bar chart comparing monthly **Sum of ACTUAL\_SALES** (light blue) against **Sum of FORECAST\_P50** (dark blue). | Direct comparison of realized performance against monthly goals. |
| **Upper Lower Confidence Intervals** | An area chart showing the **Forecast P50** range, bounded by the Upper (CI\_UPPER) and Lower (CI\_LOWER) Confidence Intervals. | Assesses the risk and potential variability (min/max) of the long-term forecast up to 2028. |
| **Sum of FORECAST\_P50 by SILHOUETTE** | A detailed pie chart breaking down the total Forecast P50 value by specific product silhouettes or categories. | Shows the percentage and absolute contribution of each product line to the overall forecast. |

---

## ⚙️ How to Use

* **Filtering:** Use the **Filters** pane on the right or click on any segment/bar within a chart (e.g., clicking 'Mexico' on the map) to cross-filter all other visuals on the dashboard.
* **Drill Down:** (If enabled) Check if visuals allow right-click 'Drill Through' for more granular detail.
