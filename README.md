# 📈 Power BI Dashboards - Global Sales & Operations Hub

A centralized web-based portal for real-time analytics, forecasting, and business intelligence. This project hosts interactive Power BI dashboards covering sales performance, forecast accuracy, and operational efficiency across all business regions.

---

## 🚀 Project Overview

This project provides a **unified dashboard portal** that aggregates multiple business intelligence views:

1. **Sales & Forecast Performance Dashboard** - Monitor actual sales vs. P50 forecast projections across regions and product segments
2. **Operational Efficiency Dashboard** - Real-time operational metrics, supply chain performance, and resource allocation

The dashboards are accessible through a responsive web interface with modern UI design and embedded Power BI reports.

---

## 📁 Project Structure

```
PowerBI_Dashboards/
├── index.html              # Hub landing page - Navigation portal to all dashboards
├── dashboard1.html         # Sales & Forecast Performance Dashboard
├── dashboard2.html         # Operational Efficiency Dashboard
├── style.css              # Dashboard embedding styles and responsive layout
├── welcome.css            # Hub landing page styles - Grid background, tiles, typography
└── README.md              # This file
```

---

## 🔑 Key Dashboards

### 1️⃣ Sales & Forecast Performance Dashboard
**File:** [dashboard1.html](dashboard1.html)

**Purpose:** Provides a comprehensive view of **Actual Sales** compared against the **Forecast (P50)** with analysis across:
- Geography (Countries: North America, Mexico, Japan, Hong Kong, China, Australia)
- Product Categories (Sport, Silhouette)
- Sales Organizations (United States, Mexico, Others)
- Demographics (Boys, Girls, Ladies)

**Time Range:** January 2025 – December 2028 (including confidence interval forecasts)

**Key Metrics:**
- Actual Sales (realized revenue)
- Forecast P50 (50% probability achievement target)
- Confidence Intervals (Upper/Lower bounds for forecast variability)

**Main Visualizations:**
| Chart | Description |
|-------|-------------|
| **Geographical Map** | Regional activity and data source distribution |
| **Monthly Performance** | Actual Sales vs. Forecast P50 bar chart |
| **Forecast Range** | Area chart with confidence interval bounds (2025-2028) |
| **Product Breakdown** | Pie chart showing forecast distribution by silhouette/product line |
| **Sales Org Distribution** | Forecast split across organizational structure |

### 2️⃣ Operational Efficiency Dashboard
**File:** [dashboard2.html](dashboard2.html)

**Purpose:** Gain consolidated visibility into orders, revenue, and profit across store locations and product categories,
with interactive filters to explore specific months and operational segments.

---

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3
- **Styling:** Custom CSS with modern design patterns (Space Grotesk font, glass-morphism effects)
- **Responsive Design:** Mobile-first approach with flexible grid layouts
- **Analytics:** Power BI embedded reports
- **Color Scheme:** Dark theme with accent colors (Gold: #f5b452, Blue: #52acf5)

---

## 📖 How to Use

### Accessing the Hub
1. Open [index.html](index.html) in any modern web browser
2. View the dashboard portal with navigation tiles for available dashboards

### Viewing Dashboards
- Click **"Open Dashboard →"** on any dashboard tile to embed and view the Power BI report
- Dashboards are embedded directly in the page for seamless viewing

### Filtering & Interaction
- Use the **Filters** pane (right side) to narrow data by region, sales organization, or product category
- **Click elements** in visualizations (e.g., country on map, bar in chart) to cross-filter all other visuals
- **Drill-down capabilities** available where enabled (right-click if supported)
- Use Power BI's internal filter controls (top-right) for time period selection

### Data Updates
- Reports are connected to live Power BI data sources
- Refresh frequency depends on your Power BI service refresh schedule
- Authentication may be required if accessing from restricted networks

---

## 🎨 Design & Styling Features

The portal uses modern design principles:
- **Dark Theme:** High contrast, easy on the eyes for extended viewing
- **Glass-morphism Effects:** Frosted glass aesthetic with backdrop blur
- **Responsive Grid Layout:** Automatically adjusts for desktop, tablet, and mobile
- **Custom Typography:** Space Grotesk font family for clean, modern appearance
- **Interactive Tiles:** Hover effects and smooth transitions
- **Accessibility:** Semantic HTML and color-coded tags (Strategic View, Daily Ops, Deep Dive)

---

## 📊 Data Scope & Dimensions

**Measured Values:**
- Sum of Actual Sales
- Sum of Forecast P50
- Confidence Intervals (Upper & Lower)

**Dimensional Analysis:**
- **Geography:** Country, Region
- **Organization:** Sales Org
- **Product:** Sport, Silhouette (specific product line)
- **Demographics:** Gender (Boys, Girls, Ladies)
- **Time:** Monthly breakdown, Annual trends through 2028

---

## 🔄 Initial View & Navigation

**Default Behavior:**
- Dashboards aggregate data across **all Sales Organizations** by default
- Full product portfolio view unless filters are applied
- Left panel filters available within each Power BI report
- Top-right Power BI control panel for advanced filtering

**Recommended Workflows:**
1. **Executive Summary** → View dashboard landing page for overview
2. **Regional Deep-Dive** → Filter by region on the geographic map
3. **Time-Series Analysis** → Focus on specific months or quarters
4. **Product Performance** → Compare sales by sport/silhouette category

---

## 🔐 Access & Permissions

- Dashboards require appropriate **Power BI service access**
- If reports show authentication prompts, verify your org's Power BI permissions
- Hosting page and reports must share access permissions for seamless embedding
- Contact your BI team if you encounter access issues

---

## 📝 Notes

- Dashboard data reflects actuals through the current date with forward-looking forecasts
- P50 forecast represents the 50th percentile (median) probability of achievement
- Confidence intervals provide risk assessment for long-term projections
- Product categories may vary by regional classification
- For detailed data exports or custom reporting, use Power BI's native export features

---

## 📧 Support & Questions

For issues, feature requests, or questions about dashboard data:
- Contact your Business Intelligence team
- Verify Power BI service status and connection
- Check browser compatibility (Chrome, Edge, Safari recommended)
- Ensure JavaScript is enabled for embedded content

---

**Last Updated:** December 26, 2025
