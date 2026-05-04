# Data-Analytics-Internship

Project Title / Headline

Data Analytics Job Simulation

A real-world data analytics simulation completed as part of the Deloitte Australia Data Analytics Job Simulation (via Forage, February 2026) — covering the full analytics pipeline from raw telemetry data cleaning and gender pay equality analysis in Excel, to building an interactive factory machine health dashboard in Tableau — analysing machine downtime across 4 global Daikibo factories and 9 device types.

📌 Short Description / Purpose
This project simulates the work of a Deloitte data analyst across two practical tasks. Task 1 involved using a provided data analysis framework to classify and interpret telemetry data from Daikibo Industrials' global factories. Task 2 involved working in Excel to analyse gender pay equality across job roles, and then building a Tableau dashboard to visualise machine health (unhealthy event counts) by factory location and device type.
The project is intended for aspiring data analysts looking to understand how real consulting firms approach forensic technology, operational data analysis, and executive-ready dashboard delivery.

🛠️ Tech Stack
----------------
| Tool                             |  Purpose                                                                          |
----------------------
| 📊 Microsoft Excel              | Data cleaning, equality scoring formula, classification logic for pay gap analysis  |
----------------------
|📈 Tableau Desktop               | Interactive two-sheet dashboard — machine unhealthy counts by Factory & Device Type   |
----------------------
| 📂 Daikibo Telemetry Data (.twb) | Source Tableau workbook with factory machine sensor data                             |
----------------------
| 🧠 Deloitte Analysis Framework   |Structured approach used in Task 1 to classify data findings                           |
-------------------

🗂️ Project Structure
Data Analytics Internship/
│
├── 📊 deloitte_second_task.xlsx       # Excel — gender pay equality analysis
├── 📈 daikibo-telemetry-data.twb      # Tableau workbook — machine health dashboard
├── 🖼️ dashboard_preview.png           # Dashboard screenshot
└── 📄 README.md                       # Project documentation

📂 Data Source
Task 1 — Telemetry Data: Daikibo Industrials machine sensor data across 4 factories:

daikibo-berlin
daikibo-factory-meiyo
daikibo-factory-seiko
daikibo-shenzhen

Tracking unhealthy events per device type including LaserWelder, LaserCutter, HeavyDutyDrill, Furnace, ConveyorBelt, CNC, and more.
Task 2 — Equality Data: Employee-level compensation dataset used to compute a fairness score and classify each job role as Fair / Unfair using Excel formulas.

📊 Stage 1 — Excel: Gender Pay Equality Analysis
Cleaned and structured the provided compensation dataset in Excel. Applied a calculated equality score column using conditional logic to classify each role:

Score = 0 → classified as "Fair"
Score ≠ 0 → classified as "Unfair"

This analysis identified which job roles within Daikibo had pay disparities between male and female employees.

📈 Stage 2 — Tableau: Machine Health Dashboard
Built a two-sheet interactive Tableau dashboard on the daikibo-telemetry-data source:
Sheet 1 — By Factory
FactoryUnhealthy Eventsdaikibo-factory-meiyo~480 (highest)daikibo-factory-seiko~420daikibo-factory-berlin~115daikibo-shenzhen~20 (lowest)
Sheet 2 — By Device Type
DeviceUnhealthy EventsLaserWelder~480 (most critical)LaserCutter~430HeavyDutyDrill~70Furnace~20CNC, ConveyorBelt, AirWrench, MetalPress, SpotWelder<10 each

💡 Business Impact & Insights

Factory Risk — daikibo-factory-meiyo records the highest unhealthy machine events, flagging it as the highest-risk location requiring immediate maintenance prioritisation.
Device Risk — LaserWelder and LaserCutter together account for the overwhelming majority of unhealthy events — strong candidates for predictive maintenance investment.
Pay Equality — Roles classified as "Unfair" in the Excel analysis provide HR leadership with a clear, data-backed list for compensation review and corrective action.
Operational Efficiency — Cross-referencing factory-level and device-level breakdown enables targeted, cost-effective maintenance scheduling rather than blanket servicing.
Simulation Credibility — Completed and certified under Deloitte's official job simulation programme via Forage — validated by Deloitte's Chief Human Resources Officer.

