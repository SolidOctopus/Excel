# Data Science Salary Dashboard (Excel)

Interactive Excel dashboard that helps users explore **data-related job salaries and postings** by selecting:
- **Job title**
- **Country**
- **Job type** (e.g., full-time, part-time, contract)

Based on the selected filters, the dashboard surfaces:
- **Median salary** (based on available salary entries)
- **Top hiring platform/source** and **number of postings**
- Visuals such as **job title vs. expected salary**, **posting distribution by location**, and **pay comparisons by job type**

---

## File
- `Data Salary Dashboard.xlsx`

## How to use
1. Open the workbook in **Excel (Microsoft 365 / Excel 2021+ recommended)**.
2. Go to the **Salary_Dashboard** sheet.
3. Use the dropdowns for **Job Title**, **Country**, and **Type**.
4. Review the updated metrics and charts.
5. If anything doesn’t update: **Data → Refresh All** (or refresh the sheet/pivots if prompted).

---

## What’s inside
- **Data**: raw job-posting dataset (salary + job metadata)
- **Salary_Dashboard**: interactive dashboard + visualizations
- **Jobs / Country / Type / Platform**: dropdown lists used for filtering and validation

---

## Metrics & notes
- Salary metrics are calculated from postings where salary values are present.
- “Platform” refers to the job source (e.g., “via Indeed”, “via LinkedIn”, etc.).
- Results reflect the underlying dataset timeframe and coverage (not live market data).

---

## Screenshots
![Salary Dashboard 1.png]
