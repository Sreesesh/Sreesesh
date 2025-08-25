<!-- PROFILE README — Finance | Excel/VBA | Power Query | Power BI -->

<h1 align="center">Hi there 👋, I'm Sreesesh</h1>
<p align="center">
Finance & Analytics | AR • AP • GL | Consolidated Revenue Reporting | Abu Dhabi, UAE
</p>

<p align="center">
  <a href=https://www.linkedin.com/in/sreesesh-kakkarayil-5b98891aa">LinkedIn</a> •
  <a href=sree7823@yahoo.com">Email</a> •
  <a href="https://drive.google.com/file/d/1K3F9xQEqJVoeNP9zzhXLSE6aUy8LDzYJ/view?usp=drivesdk">Resume</a>
</p>

---

## 🔎 What I Do
- Build **automation** with **Excel + VBA** to reduce manual work and errors  
- Transform raw data using **Power Query** and model with **DAX**  
- Design **Power BI** dashboards for **revenue, AR/AP, and doctor KPIs**  
- Own month-end routines: **reconciliations, YTD variance, consolidated revenue**

## 🛠 Tech & Tools
- **Excel** (VLOOKUP, XLOOKUP, Pivot, Power Query, VBA)
- **Power BI** (Data Modeling, DAX, Bookmarks, Drillthrough)
- **SQL basics** for joins & aggregations
- Version control with **Git & GitHub**

## 🧭 Current Role
**NMC Healthcare LTD, Abu Dhabi** — AR/AP/GL, consolidated revenue finalization, reporting automation.

## 📈 Highlighted Work (pin these repos!)
- **Power BI — Healthcare Revenue Dashboard**  
  KPI pages for **OP/IP**, **doctor performance**, **YTD vs LY**, slicer-driven views.  
  _Tech_: Power Query, DAX (YTD, PY, dynamic titles), bookmarks.

- **Excel/VBA — Daily PPT Email Automation**  
  Generates **speedometer/cylinder charts** per recipient, emails securely, deletes temp files.  
  _Tech_: VBA (Outlook automation), chart templates, parameterized filters.

- **Power Query — AR Aging Automation**  
  Cleans & classifies invoices into dynamic aging buckets with scheduled refresh.  
  _Tech_: M language, incremental refresh patterns.

> Tip: Create these repos with concise READMEs (problem → solution → screenshots → tech stack).

## 🧮 Handy DAX/Power Query Snippets
```DAX
-- YTD Revenue
YTD Revenue =
TOTALYTD(
    SUM('DRR Revenue'[Net Amount]),
    'Calendar'[Date]
)

-- Previous Year YTD
PYTD Revenue =
CALCULATE(
    [YTD Revenue],
    SAMEPERIODLASTYEAR('Calendar'[Date])
)
