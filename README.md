# India Road Infrastructure — Capex Utilization & Execution Dashboard

An interactive Power BI dashboard analyzing 5+ years of India's national highway budget allocation, construction execution, toll revenue, and land acquisition cost trends across 28 states.

![Dashboard Preview](Mini_Dashboard.png)

## 📌 Overview

This project analyzes how efficiently India's road infrastructure funds are allocated, spent, and translated into constructed highway length across states — identifying execution gaps and cost escalation patterns similar to evidence-based infrastructure analysis used in advisory and consulting engagements.

**Key finding:** Land acquisition cost per hectare has risen ~4.9x since 2011-12, making it the primary driver of infrastructure cost escalation — more significant than construction cost inflation alone.

## 🔑 Highlights

- Analyzed 5+ years of national highway budget, execution, and toll revenue data across **28 states**
- Identified land acquisition cost escalation (**~4.9x since 2011-12**) as the primary infrastructure cost driver
- Built an interactive Power BI dashboard tracking state-wise construction completion (**46%–100%**) and toll revenue concentration
- Authored a 1-page insight brief with actionable recommendations

## 📊 Dashboard KPIs

| Metric | Value |
|---|---|
| NH Awarded | 26,425 km |
| NH Constructed | 20,769 km |
| National Completion % | 79% |
| Toll Revenue (2024-25) | ₹61,410 crore |
| Land Cost Rise (since 2011-12) | ~4.9x |

## 🖥️ Dashboard Pages / Visuals

- **State Execution Chart** — % of sanctioned NH length constructed, by state (Goa 100% → Kerala 71%)
- **Toll Revenue Chart** — State-wise toll/user fee collection for 2024-25 (top-grossing states)
- **Land Cost Chart** — Year-on-year NHAI land acquisition expenditure per hectare (2011-12 to 2022-23)
- **Road Safety Chart** — NH fatalities by state, 2019 vs 2023

## 🗂️ Repository Contents

| File | Description |
|---|---|
| `India_Infrastructure_Capex___Execution_Dashboard_.pbit` | Power BI template file — open in Power BI Desktop to explore the full interactive dashboard |
| `India_Road_Infrastructure_Data.xlsx` | Underlying dataset (6 sheets, see below) |
| `Mini_Dashboard.png` | Static preview/export of the dashboard |

## 📁 Dataset Structure

The workbook (`India_Road_Infrastructure_Data.xlsx`) contains 6 sheets:

1. **README** — dataset documentation and source notes
2. **Ministry Budget** — Year-wise Ministry of Road Transport & Highways allocation (Total, NHAI, Roads & Bridges, Road Safety) from 2024-25 (Actual) to 2026-27 (Budget Estimate)
3. **State Progress** — State-wise NH length: total sanctioned, awarded, and constructed (as of June 2025), with computed completion %
4. **Toll Collection** — State-wise NH toll/user fee collection, 2022-23 to 2024-25, with computed YoY growth %
5. **Land Acquisition Cost** — Year-wise NHAI land acquisition: hectares possessed, expenditure, and cost per hectare (2011-12 to 2022-23)
6. **Road Safety** — State-wise NH fatalities, 2019–2023 (top 10 states)

## 🔍 Data Source

**Primary source:** PRS Legislative Research — *"Demand for Grants 2026-27 Analysis: Road Transport and Highways,"* Feb 19, 2026. Compiled from Union Budget documents, NHAI reports, and Parliament Q&A records.
🔗 https://prsindia.org/budgets/parliament/demand-for-grants-2026-27-analysis-road-transport-and-highways

## 🛠️ Tools & Skills Used

- **Power BI** — data modeling, DAX measures, interactive dashboard design
- **Excel** — data cleaning, structuring, and derived-metric calculations (completion %, YoY growth, cost per hectare)
- **SQL** — data querying and transformation
- Government/public data sourcing and validation (PRS, NHAI)

## 🚀 How to Use

1. Clone or download this repository
2. Open `India_Infrastructure_Capex___Execution_Dashboard_.pbit` in **Power BI Desktop** (free download from Microsoft)
3. When prompted, point the data source to `India_Road_Infrastructure_Data.xlsx`
4. Explore the interactive filters: **State Execution**, **Toll Revenue**, **Land Cost Trend**, **Road Safety**

> To use this dataset in another BI tool (e.g., Tableau), import each Excel sheet as a separate table. Suggested pages: (1) National Overview — budget trend + KPI cards, (2) State Execution — map colored by completion %, (3) Toll Revenue trend, (4) Land Acquisition cost escalation over time, (5) Safety — fatalities vs NH share.

## 📄 License

Data sourced from public government records (PRS Legislative Research, NHAI, Union Budget documents) and used for educational/portfolio purposes.

