# Financial & Management Dashboard - Power BI

## Overview

An interactive Power BI reporting solution designed for executive-level visibility into business performance. The solution spans two core dashboards - Financial Analysis and Management - delivering real-time insights across revenue, profitability, cost management, and operational efficiency.

---

## Dashboards

### Financial Analysis Dashboard
Provides a granular view of project-level financial health, including:
- Revenue Under Contract and Earned Revenue tracking
- Cash flow and accrued income analysis
- Total margin and project cost breakdown
- Aging receivables monitoring

### Management Dashboard
Delivers high-level operational and strategic KPIs, including:
- Gross Revenue and Net Project Revenue (NPR)
- EBITA and EBITA Margin
- Billing Ratio and Project Profitability
- Order Book, Support Cost, and Working Capital Days
- Organic Growth Trends

---

## Data Sources

| Dataset | Description |
|---|---|
| Projects | Core project metadata and attributes |
| Invoices | Invoice records linked to projects |
| Members | Employee and resource data |
| Expenses | Project-level expenditure records |
| Products | Products procured during project execution |
| Time Entries | Member time tracking across tasks |
| Cost to Date | Cumulative cost data for progress analysis |
| KPIs Data | Financial and operational performance metrics |
| Geo Weights | Geographic distribution data for regional reporting |

---

## Data Transformation & Modeling

- Built a **Calendar Table** to support time-intelligence calculations
- Defined **table relationships** to ensure accurate cross-dataset reporting
- **Merged KPI data with geographic weights** for regional analysis
- Applied **filtering logic** to scope reporting to post-2020 projects
- Calculated key financial measures including Revenue, Profit, and Cost metrics

---

## Visuals & Interactivity

- Dynamic Year and Month slicers for flexible period selection
- Comparative metric tables for side-by-side performance analysis
- Line and bar charts for trend identification
- Gauge charts for KPI threshold monitoring
- Custom visualizations tailored to financial reporting standards

---

## Reference Documents

- [Custom Dashboard Design](Custom%20Dashboard%203%20(Financial%20Analysis).docx)
- [Reference Dashboard Design](Reference%20Dashboard%20Design%20(Financial%20Analysis).docx)
- [Management Dashboard Instructions](Assignment%205%20-%20Managment%20Dashboard%20CD1.pdf)
- [Medical Data Instructions](Medical%20Data%20-Instructions-9-June.pdf)
