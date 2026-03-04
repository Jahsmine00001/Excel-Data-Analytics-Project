# Essential Excel Functions & Formulas

## Overview

This workbook uses a real HR employee dataset (266 employees across 13 departments) to answer 10 progressive business questions using Excel's most powerful functions. Each question is answered in its own dedicated sheet, building from foundational aggregations to complex multi-function formulas.

---

## Dataset

**Source:** HR Employee Records  
**Size:** 266 employee records  
**Fields:** Employee ID, First Name, Last Name, Gender, Department, Salary, Salary Bucket, Start Date, FTE, Employee Type, Work Location, Tenure, Work Type

---

## Business Questions Answered

| # | Business Question | Functions Used |
|---|-------------------|----------------|
| Q1 | Total salary and headcount by department | SUMIFS, COUNTIFS |
| Q2 | All employees earning more than $100k | FILTER |
| Q3 | Female employees earning over $100k who joined in 2020 or after | FILTER, wildcards |
| Q4 | Lowest, highest and top 5 salary values overall, by male and female | MIN, MAX, LARGE, SORT, TAKE |
| Q5 | Full list of all departments and total count | UNIQUE, COUNTA |
| Q6 | Employee details lookup by ID | VLOOKUP, INDEX+MATCH |
| Q7 | Employee details lookup with error handling, find all employees at $120k | XLOOKUP, IFERROR |
| Q8 | Name of the highest salary earner using a single complex formula | XLOOKUP + MAX |
| Q9 | All employees who joined in March; female employees who started on a Monday | FILTER + MONTH |
| Q10 | Full department report: headcount, average salary, % deviation from overall average, median salary, female ratio | UNIQUE, SUMIFS, COUNTIFS, Conditional Formatting |

---

## Key Highlights

- **Q10** is the most complex sheet — it builds a full department summary report from scratch using dynamic array functions, calculating each department's performance against the company-wide average salary of **$73,881**
- **XLOOKUP** is used with nested functions to handle multi-result lookups and combine results into a single comma-separated cell
- **Conditional Formatting** applied in Q10 to visually flag departments performing above and below the overall salary average
- Dataset includes edge cases like employees with "Need to check" gender entries, duplicate names, and part-time FTE values — all handled cleanly in the formulas

---

## Skills Demonstrated

- Advanced lookup functions: XLOOKUP, VLOOKUP, INDEX+MATCH
- Dynamic array functions: FILTER, UNIQUE, SORT, TAKE
- Aggregation functions: SUMIFS, COUNTIFS, LARGE, MIN, MAX, MEDIAN
- Nested and combined formulas for complex business logic
- Conditional formatting for data-driven visual reporting
- Handling errors and edge cases with IFERROR
