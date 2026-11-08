# Uber Ride-Hailing Operations — Business Analysis Case Study

## Portfolio Project

**Type:** Self-initiated Business Analysis & Power BI portfolio project  
**Domain:** Ride-hailing / Mobility  
**Tools:** Power BI, DAX, Power Query, BPMN, User Stories, MoSCoW, Stakeholder Analysis

> **Important:** This is an independent portfolio case study based on a simulated ride-hailing business scenario. It is not work performed for or on behalf of Uber, and the dataset is synthetic.

## Business Problem

The case study examines how a ride-hailing operation can improve trip fulfilment and customer experience by monitoring demand, driver acceptance, cancellations, revenue and operational performance.

The analysis focuses on the journey from ride request through driver matching, acceptance, pickup, trip completion and cancellation.

## Business Analysis Approach

1. Define business problem, scope and success measures.
2. Identify stakeholders and their information needs.
3. Map the current-state (As-Is) process.
4. Identify bottlenecks and improvement opportunities.
5. Design a future-state (To-Be) process.
6. Translate requirements into user stories and acceptance criteria.
7. Prioritise requirements using MoSCoW.
8. Build KPI definitions and a Power BI prototype.
9. Provide data-driven recommendations.

## Key KPIs

| KPI | Definition |
|---|---|
| Completion Rate | Completed trips / total requested trips |
| Cancellation Rate | Cancelled trips / total requested trips |
| Driver Acceptance Rate | Accepted requests / total requests |
| Revenue | Fare revenue from completed trips |
| Average Trip Value | Revenue / completed trips |
| Trip Volume | Number of requested trips |
| Average Trip Duration | Average duration of completed trips |
| Average Distance | Average distance of completed trips |

## Key Recommendations

- Monitor cancellation hotspots by city, time period and demand conditions.
- Use demand and driver-acceptance indicators to support better driver allocation.
- Track completion and cancellation KPIs through a single operational dashboard.
- Investigate persistent low-acceptance or high-cancellation segments before they affect customer experience.
- Use trend-based KPI monitoring to support operational decisions rather than relying only on aggregate monthly results.

## Repository Structure

```text
README.md
Uber_BA_Case_Study.pdf
Uber_Synthetic_Trip_Data.csv
images/
  As-Is_BPMN.png
  To-Be_BPMN.png
  PowerBI_Dashboard_Overview.png
  PowerBI_Dashboard_KPI_Detail.png
Uber_Dashboard.pbix   # Add after building the report in Power BI Desktop
```

## Power BI

The included CSV is synthetic portfolio data. Import it into Power BI Desktop, create the model and measures, and reproduce the dashboard shown in the image previews.

Suggested report pages:

- Executive Overview
- Operational KPIs
- Cancellation Analysis
- City / Demand Analysis

## Interview Talking Points

Be prepared to explain:
- Why each stakeholder matters.
- How the As-Is process differs from the To-Be process.
- Why each KPI was selected.
- How MoSCoW was used to prioritise requirements.
- How Power BI supports the business decision rather than simply visualising data.
- What assumptions and limitations exist in the synthetic dataset.
