# HR Attrition Analysis Dashboard

An interactive Power BI dashboard analyzing employee attrition 
across 5 departments to identify key turnover drivers and 
support data-driven HR retention decisions.

## Tech Stack
- Power BI Desktop (DAX, Power Query)
- Microsoft Excel
- GitHub

## Data Source
Excel spreadsheet containing 100 employee records with fields 
including department, region, gender, attrition status, and 
monthly exit data.

## Highlights
- 24% overall attrition rate identified across 100 employees
- HR West region flagged as highest risk with 75% attrition rate
- Marketing East showed 50% attrition — signaling workload issues
- Peak employee exits detected in July, October, and November
- Built interactive slicers for Department, Region, Gender, 
  and Status with a bookmark-based Reset button

## Business Problem
Organizations lose significant time and money when employees 
leave unexpectedly. Without clear visibility into which 
departments, regions, or employee groups are most at risk, 
HR teams cannot act before attrition becomes a crisis. 
This dashboard solves that by turning raw HR data into 
clear, actionable insights.

## Goal of the Dashboard
To help HR managers and leadership quickly identify:
- Which departments and regions have the highest attrition
- When during the year resignations peak
- How gender and region interact with turnover
- Where to focus retention efforts first

## Features
- KPI Cards — Total Employees, Active Employees, 
  Left Employees, Attrition Rate at a glance
- Bar Chart — Total employees by department for 
  quick headcount comparison
- Pie Chart — Gender distribution across the workforce
- Line Chart — Monthly trend of left employees 
  to spot resignation spikes
- Attrition Data Table — Department-wise breakdown 
  with total employees, attrition rate, and region
- Interactive Slicers — Filter by Department, Status, 
  Region, and Gender
- Reset Button — Bookmark-based button to clear 
  all filters in one click

## Walkthrough of Visuals

**KPI Cards (Top Row)**
Five cards show the most critical numbers at a glance — 
100 total employees, 76 active, 24 left, 5 departments, 
and 24% attrition rate. Decision makers see the health 
of the workforce in under 5 seconds.

**Total Employees by Department (Bar Chart)**
Marketing has the largest headcount, followed by Sales, 
HR, IT, and Finance. This gives context to attrition 
numbers — a small department losing a few people can 
have a much higher attrition rate than a large one.

**Total Employees by Gender (Pie Chart)**
53% Female, 47% Male — nearly equal split. This tells 
HR that attrition is not driven by gender imbalance 
and focus should shift to department and region factors.

**Left Employees by Month (Line Chart)**
Exits peak in July, October, and November with 4 
departures each. January and April also show early 
spikes. This pattern helps HR plan recruitment drives 
before peak resignation months.

**Attrition Data Table**
Breaks down every department by region with exact 
attrition rate. HR West shows 75% — the single 
highest risk segment in the entire dataset. 
Marketing East shows 50%. These two rows alone 
tell HR exactly where to act first.

## Business Impact and Insights

**Insight 1 — HR West is a crisis, not a trend**
75% attrition in HR West means 3 out of every 4 
employees in that segment left. This requires 
immediate investigation — exit interviews, manager 
review, and workload audit.

**Insight 2 — Marketing East needs attention**
50% attrition in Marketing East despite Marketing 
being the largest department overall suggests a 
regional management or workload problem, not a 
company-wide issue.

**Insight 3 — Plan hiring before July and Q4**
The line chart shows consistent exit spikes in 
mid-year and year-end. HR can get ahead of this 
by opening recruitment pipelines 2 months before 
these windows.

**Insight 4 — Finance and IT need monitoring**
Both show 33-50% attrition in specific regions. 
Not yet critical but trending in a dangerous direction 
without intervention.

**Overall Business Impact**
This dashboard reduces the time HR needs to identify 
at-risk segments from hours of spreadsheet analysis 
to under 60 seconds. With interactive slicers, any 
HR manager can filter by their own department or 
region and get an instant picture of their attrition 
situation — no data skills required.
