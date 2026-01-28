# 📊 Operational Performance & MI Reporting (Power BI)

## Project overview
This project focuses on analysing day-to-day operational service data to support regular performance monitoring and management decision-making. It replicates a typical UK MI / reporting scenario, where managers require clear visibility of workload, backlog and SLA performance rather than complex analytical models.

The project prioritises clarity, usability and non-technical communication, reflecting how operational reporting is used in real business environments.

---

## Business context
Operational teams rely on consistent reporting to understand whether service performance is stable, where operational risks are emerging, and which areas require intervention.  
This project analyses ticket-based service data across teams and regions to support workload balancing, SLA monitoring and resource planning decisions.

---

## Data source
The dataset used in this project represents **simulated operational service data** provided as CSV files for analytical and portfolio purposes.

- The data structure reflects common ticket-based operational systems used in customer service and operations teams.
- All data has been anonymised and does not represent any real organisation or individuals.
- The dataset was used solely for learning, analysis and portfolio demonstration.

---

## Tools & techniques
- **SQL** – basic querying and aggregation
- **Power BI** – data modelling, visualisation and dashboard design
- **CSV files** – source data format

Scope of analysis included:
- Ticket volume
- Backlog levels
- SLA compliance
- Resolution time
- Team and regional performance
- Day-of-week demand patterns

---

## Dashboards
The Power BI report consists of two dashboards:

### 1. Executive Summary
A high-level view of overall operational performance, including ticket volume trends, backlog levels, SLA compliance and key performance indicators, designed for quick management review.

### 2. Operational Detail
A detailed breakdown by team, region and day of week, supporting identification of bottlenecks, workload imbalances and potential SLA risk areas.

---

### Screenshots

**Executive Summary**
![Executive Summary](screenshots/executive_summary.png)

**Operational Detail**
![Operational Detail](screenshots/operational_detail.png)


---

## Key insights
- Overall ticket volume remains relatively stable, while backlog levels vary significantly across teams, indicating uneven workload distribution.
- Technical Support consistently carries higher backlog levels, suggesting structural capacity or complexity constraints.
- Teams with higher backlog levels tend to show lower SLA compliance, highlighting workload pressure as a key performance driver.
- Resolution times differ by region, with some regions consistently taking longer to close tickets.
- Ticket demand is concentrated on weekdays, with a predictable reduction at weekends.

---

## Recommendations
- Review workload allocation and staffing capacity within Technical Support to address persistent backlog pressure.
- Prioritise backlog reduction in underperforming teams before increasing intake or expanding service capacity.
- Investigate regional process or escalation differences contributing to longer resolution times.
- Align resource planning more closely with weekday demand patterns to prevent backlog accumulation.

---

## Notes
This project focuses on practical, operational reporting rather than advanced analytics, reflecting common requirements for MI, Reporting and Junior Data Analyst roles in the UK.
