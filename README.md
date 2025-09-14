# Employee Utilization and PTO Dashboard

This project simulates a business intelligence engagement at a regional professional services firm. The firm recently introduced unlimited Personal Time Off (PTO), creating the need for more robust utilization tracking and reporting to maintain profitability and improve decision-making.

This project is aimed at designing and delivering Power BI dashboards that provide utilization insights to stakeholders across the organization.

## Business Goal

To report and analyze % utilization by employee, branch, and division across any date range, with the ability to:

- Identify trends and forecasts.
- Compare utilization against dynamic targets.
- Provide drilldowns into employee-level and project-level detail.
- Empower managers to make informed decisions regarding PTO approvals and resource allocation.

## Stakeholders

- Project Sponsor: Chief Financial Officer (CFO)
- Partners & Executive Management – require executive-level summaries and trends.
- Division Managers – need breakdowns by branch, employee type, and project codes.
- Branch Managers – focus on branch-level and employee-level utilization metrics.

## Requirements

- Track % utilization by employee, branch, division, and project code.
- Provide filtering by date range, branch, division, employee type.

Executive Summary page:

- Overall % utilization (calendar year)
- Monthly utilization trends
- Comparison across branches and divisions

Division Manager View:

- Hours & utilization by project code and employee type
- Breakdown of hours by billable time, PTO, non-billable project time, bench time, sales support

Branch Manager view:

- Hours & utilization by employee

Drilldowns into employee-level and project-level details

## Tools and Technologies

- Power BI Desktop – dashboard design and visualisation
- DAX – measures for % utilization, target comparisons, and trend analysis
- Power Query (M Language) – ETL for cleaning and shaping time report data
- Excel / CSV – mock employee time and budget datasets

## Dashboard Design

Executive Summary

- KPI Card: Current Year-to-Date Utilization %
- Line Chart: Monthly Utilization Trend
- Bar Chart: Utilization by Branch & Division
- Slicer: Target Utilization (dynamic input)

Division Manager View

- Matrix: Hours by Project Code & Employee Type
- Donut Chart: Breakdown of Billable vs Non-Billable vs PTO
- Bar Chart: Total Hours by Branch

Branch Manager View

- Table: Employee Utilization % (branch-specific)
- KPI: Branch-wide Utilization % vs Target

Drilldown Pages

- Employee-level detail (hours, billable %, PTO usage)
- Project code detail (allocation and utilization trends)
