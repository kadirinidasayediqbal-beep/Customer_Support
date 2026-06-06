# Customer Support Helpdesk Dashboard — Power BI

A Power BI dashboard built to track and analyze customer support ticket data across agents, priorities, and resolution statuses.

---

## About the Project

I built this dashboard to practice data modeling in Power BI — specifically working with two related tables and writing DAX measures from scratch.

The dataset has 200 support tickets and 10 agents, linked through Agent_ID. From there I created visuals to answer basic operational questions: How many tickets are resolved? Which agents are handling the most load? Where are tickets piling up?

---

## Dataset

- 200 support tickets
- 10 agents
- Fields: Ticket ID, Agent ID, Priority, Status, Date
- Two-table model linked via Agent\_ID

---

## What I Built

| Visual | Purpose |
|---|---|
| KPI Card — Total Tickets | Shows overall volume (200) |
| KPI Card — Resolved Tickets | DAX measure using CALCULATE + COUNTROWS (105 resolved) |
| Bar Chart — Agent Performance | Tickets handled per agent |
| Donut Chart — Priority Split | Breakdown by High, Medium, Low priority |
| Status Slicer | Filter by Open, In Progress, Resolved, Escalated, Closed |

---

## Key Takeaway

52.5% of tickets are resolved. The agent performance chart makes it easy to spot uneven workload distribution — something a support manager would actually care about.

---

## Tools Used

- Power BI Desktop
- DAX (CALCULATE, COUNTROWS, SUM)
- Excel (dataset prep)

---

## Files

- `Customer_Support_Nida.pbix` — Power BI dashboard file
- `Customer_Support_Nida.xlsx` — Source dataset

---

*Part of my data analytics portfolio. More projects on my [GitHub profile](https://github.com/kadirinidasayediqbal-beep).*
