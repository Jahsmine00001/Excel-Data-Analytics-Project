# Call Center Performance Dashboard (2023)

## Overview

A fully interactive Excel dashboard built on 1,000 call center records from 2023. The dashboard gives management a single-view summary of call volume, revenue, rep performance, customer demographics and satisfaction ratings — all filterable by representative using a slicer.

---

## Dashboard Preview

<img width="1316" height="624" alt="RO3" src="https://github.com/user-attachments/assets/04246a73-2c28-4bba-b7b2-32736df81394" />



---

## Dataset

**Source:** Call Center Operations Data  
**Size:** 1,000 call records across full year 2023  
**Fields:** Call Number, Customer ID, Duration, Representative (R01–R05), Date, Purchase Amount, Satisfaction Rating, Day of Week, Duration Bucket, City (Cincinnati / Cleveland / Columbus), Gender, Age

---

## Workbook Structure

| Sheet | Purpose |
|-------|---------|
| Data | Raw call records — 1,000 rows, cleaned and structured for analysis |
| Pivots | All aggregation logic powering the dashboard (KPIs, trends, rep stats, demographics) |
| Customer Center Report | The final interactive dashboard |
| Assets | Rep image references for the dynamic rep profile panel |

---

## Dashboard Components

**KPI Cards (top left)**
- Total Calls: 1,000 | Selected Rep Calls: 189
- Total Amount: $96,623 | Selected Rep Amount: $18,415
- Total Duration: 89,850 mins | Selected Rep Duration: 16,834 mins
- Average Rating: 3.9
- Happy Callers (5-star): 307

**Call Trend Chart** — monthly call volume across Jan–Dec 2023, showing seasonal peaks in March–April and September–October

**Calls by Day of Week** — horizontal bar chart identifying Saturday (40) and Sunday (36) as highest volume days

**Female vs Male Callers by City** — stacked bar showing gender breakdown across Cincinnati, Cleveland and Columbus (599 female, 401 male total)

**Rating Distribution** — bar chart of satisfaction scores from 1–5 stars

**Rep Performance Bars** — calls and revenue comparison across all 5 reps, dynamically highlighting the selected rep

**Rep Profile Panel** — dynamically updates to show selected rep's % of calls, call rank and amount rank

**Customer Revenue Table** — cross-tabulation of purchase amounts by customer and representative across all three cities

---

## Key Skills Demonstrated

- End-to-end dashboard design from raw data to executive reporting
- Pivot Tables and Pivot Charts as the data layer
- Dynamic KPI cards using pivot-linked formulas
- Slicer integration for interactive rep filtering
- Conditional formatting to highlight selected rep in comparison charts
- Multi-chart layout with consistent visual design
- Cross-tabulation of revenue by customer and representative
- Dynamic rep profile panel using XLOOKUP and RANK formulas

---

## Business Insights from the Data

- **R02 handled the most calls (218)** but **R03 generated the highest revenue ($20,872)**
- **Saturday and Sunday are peak call days**, suggesting weekend staffing should be reviewed
- **Cleveland has a significantly female-skewed caller base (326F vs 63M)** — worth noting for customer profiling
- **307 out of 1,000 callers (30.7%) gave a 5-star rating**, with an overall average of 3.9
- **R01 has the lowest call volume (189) and lowest revenue ($18,415)** — potential coaching opportunity
