# 02 - Pivot Tables

## Overview

This workbook focuses on using Excel Pivot Tables to summarize, group and cross-tabulate data across multiple dimensions. It serves as the analytical bridge between raw data and the final interactive dashboard, building the aggregation logic that powers the Call Center Report.

---

## Dataset

**Source:** Call Center Operations Data  
**Size:** 1,000 call records (2023)  
**Fields:** Call Number, Customer ID, Duration, Representative, Date of Call, Purchase Amount, Satisfaction Rating, Day of Week, Duration Bucket, City, Gender, Age

---

## What This Workbook Covers

The pivot tables built here answer the core business questions behind the dashboard:

- **Volume analysis** — total calls, total purchase amount, total call duration
- **Time trends** — calls by month and by day of week to identify peak periods
- **Rep performance** — calls and revenue broken down by each of the 5 representatives (R01–R05)
- **Customer demographics** — female vs male caller breakdown across Cincinnati, Cleveland and Columbus
- **Satisfaction distribution** — count of calls by rating (1–5 stars)
- **Customer-level revenue** — total purchase amount per customer per representative

---

## Key Skills Demonstrated

- Creating and structuring Pivot Tables from raw data
- Grouping data by time periods (month, day of week)
- Cross-tabulation across multiple dimensions (city × gender, customer × rep)
- Using calculated fields and custom aggregations
- Connecting pivot output to charts and dashboard elements
- Using Slicers to make pivot summaries interactive and filterable

---

## Connection to Dashboard

All pivot tables in this workbook feed directly into the **03-Dashboard** Call Center Report. The KPI cards, trend charts, rep comparison bars, gender breakdown and rating distribution in the dashboard are all driven by the pivot summaries built here.
