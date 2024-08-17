# 📊 Scrum Master's Excel Dashboard

## Overview

As a Scrum Master, I developed this dashboard to monitor and manage the performance of the development team. I have continuously adapted and added new features and visualizations as needed. Currently, I update the dashboard whenever I require new insights or need to analyze data for forecasting.

This Excel workbook offers a comprehensive overview of a Scrum team's performance, organized into three worksheets:

- Data Table
- Pivot Tables
- Dashboard

## Worksheet explanation

### Data Table

Contains raw data from Scrum sprints, including team availability (hours), story points or issues planned and completed, bugs resolved, and other calculations that provide insights into sprint performance and forecasting.

![SM Excel Dashboard - Data table](https://github.com/user-attachments/assets/34ca1242-7aad-4d40-8564-9bbbcb7548fa)

| Column name | Column description |
|---|---|
| Sprint | Sprint Number | 
| Hours | Hours that the team is available to develop in this sprint |
| Planned Issues| Number of Issues or tasks that the team has planned to do in this sprint |
| Planned SP | Total of the Story Points the team has commited to do in this sprint |
| Planned Issues Done | Number of issues done that were planned |
| Unplanned Issues Done |	Number of issues done that were NOT planned |
| Bugs |Total Amount of bug issues done during this sprint (planned or unplanned) |
| Total Issues Done | Total amount of issues done during this sprint |
| Planned Issues NOT Done	| Total amount of issues planned that were NOT done |
| % Planned Issues | % of planned issues done in this sprint |
| % Unplanned Issues | % of unplanned issues done in this sprint |
| Planned SP Done	| Number of Story Points Done that were planned |
| Unplanned SP Done |	Number of Story Points Done that were NOT planned |
| Bugs (SP)	| SP of bugs done during this sprint (planned or unplanned) |
| Total SP Done	| Total amount of Story Points done during this sprint |
| Planned SP NOT Done	| Total amount of Story Points planned that were NOT done |
| % Planned SP	| % of planned story points done in this sprint |
| % Unplanned SP	| % of unplanned story points done in this sprint |
| % Compliance	| % compliance with what was planned: SP Done / Sp Planned |
| Ratio SP / issue	| Story Points per issue ratio |
| SP / Hours	| Team effectiveness in terms of value delivery per hour worked |
| Hours Next Sprint	| Estimation of team avaliability hours for next sprint |
| Estimated Total SP | Used to plan next sprint. SP that should be for next sprint regarding average delivery of the previous 5 sprints and team capacity |
| Estimated SP Planned	| Used to plan next sprint. SP that should be planned for next sprint regarding estimated total SP minus possible unplanned work |
| Estimated SP Unplanned	| Used to plan next sprint. Unplanned SP that the team would have next sprint regarding average of unplanned SP for the previous 5 sprints |
| Estimated % Compliance	| % of estimated team compliance taking in account the average of the previous 5 sprints |
| Compliance final % var	| % of compliance final variation on what was predicted and what finally was |

### Pivot Tables

- Pivot Tables: Dynamically generated pivot tables that enable flexible data exploration and analysis across various dimensions. These tables are also used to create the dashboard.

### Dashboard

- Dashboard: A visual representation of key performance indicators (KPIs) tailored for the Scrum Master. The dashboard highlights team velocity, defect trends, and other critical metrics, as well as next sprint forecasting.


<kbd>![assets/img/Excel - Scrum Master Dashboard.png](https://github.com/XaviVelasco/Scrum-Master-Excel-Dashboard/blob/main/assets/img/Excel%20-%20Scrum%20Master%20Dashboard.png)
