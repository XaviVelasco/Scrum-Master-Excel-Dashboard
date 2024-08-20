# 📊 Scrum Master's Excel Dashboard

## :eye: Overview

As a Scrum Master, I developed this dashboard to monitor and manage the performance of the development team. I have continuously adapted and added new features and visualizations as needed. Currently, I update the dashboard whenever I require new insights or need to analyze data for forecasting.

This Excel workbook offers a comprehensive overview of a Scrum team's performance, organized into three worksheets:

- Sprint_details
- Data 
- Pivot Tables
- Dashboard

You can check the Excel file [here](https://github.com/XaviVelasco/Scrum-Master-Excel-Dashboard/blob/f4214c17ebf1bf0544235bd73b1e5fb15f800fd4/Excel%20-%20Scrum%20Master%20Dashboard.xlsx).

***

## :abacus: Skills and formulas used

This project demonstrates a range of data analysis skills that are crucial for understanding the performance of a Scrum team, including data cleaning, aggregation, and visualization, as well as the application of various Excel formulas and tools. Below is a detailed breakdown of the skills and specific Excel functions utilized:

- **Data Management**:
     - Data Backup and Handling: Ensuring data integrity by maintaining backup sheets.
     - Manual Data Entry and Validation: Ensuring that all sprint data is accurately entered and validated, eliminating errors that could affect calculations and visualizations.
     - Data Cleaning: Preparing the raw data for analysis, removing inconsistencies and ensuring accuracy.
     - Data Structuring: Organizing data in a table format with clear headers and consistent data types, making it easier to analyze and create pivot tables. Cross-sheet references to ensure that the data is always consistent.
     - Conditional Formatting: To highlight key performance indicators (KPIs) and other important data points visually.


- **Analytical Skills**:
     - PivotTables: Used to dynamically summarize data, allowing for quick analysis of key metrics across different sprints.
     - Filtering and Slicing: Pivot tables enable quick filtering of data by sprint, issue type, or any other relevant category, which helps in identifying trends and making data-driven decisions.

- **Visualization Skills**:

     - Dashboard Creation: Crafting a dashboard that visualizes key metrics and trends, making complex data easily understandable.
     - Conditional Formatting: Used to highlight important data points, such as compliance rates and sprint performance, providing quick visual cues.

### Formulas and Functions

This Excel contains advanced use of Excel functions such as VLOOKUP, SUM, AVERAGE, ROUNDUP, and arithmetic operations to process and analyze the data.

***

## :spiral_notepad: Worksheet explanation

### Sprint_details

This Excel sheet is used to manually enter new data observed in the sprints, which will then be used for the rest of the tables and the creation of the team's control dashboard.

<kbd>![SM Excel Dashboard - Sprint_details](https://github.com/XaviVelasco/Scrum-Master-Excel-Dashboard/blob/7b672422b64f23ce5f58c4dfe3f2107d1c6df52a/assets/img/SM%20Excel%20Dashboard%20-%20Data%20table.png)

Below you can find the description of the data (columns) used in this sheet:

| Column name | Column description |
|---|---|
| Sprint | Sprint Number | 
| Hours |Hours that the team is available to develop in this sprint |
| Planned Issues | Number of Issues or tasks that the team has planned to do in this sprint |
| Planned SP | Total of the Story Points the team has commited to do in this sprint |
| Planned Issues Done | Number of issues done that were planned |
| Unplanned Issues Done | Number of issues done that were NOT planned |
| Bugs (Issues) | Total Amount of bug issues done during this sprint (planned or unplanned) |
| Planned SP Done	| Number of Story Points Done that were planned |
| Unplanned SP Done | Number of Story Points Done that were NOT planned |
| Bugs (SP)	| SP of bugs done during this sprint (planned or unplanned) |

> [!IMPORTANT]
> This data used is based on real scrum teams but has been deliberately modified.

***

### Data Table

Contains raw data from Scrum sprints, including team availability (hours), story points or issues planned and completed, bugs resolved, and other calculations that provide insights into sprint performance and forecasting.

<kbd>![SM Excel Dashboard - Data table](https://github.com/XaviVelasco/Scrum-Master-Excel-Dashboard/blob/99be9d13d2fbf015a3704becb5b1a724e37a73ba/assets/img/SM%20Excel%20Dashboard%20-%20Data.png)

Below you can find the description of the data (columns) used in this sheet:

| Column name | Type of data | Column description |
|---|:---:|---|
| Sprint | Referenced | Sprint Number | 
| Hours | Referenced | Hours that the team is available to develop in this sprint |
| Planned Issues | Referenced |  Number of Issues or tasks that the team has planned to do in this sprint |
| Planned SP | Referenced | Total of the Story Points the team has commited to do in this sprint |
| Planned Issues Done | Referenced | Number of issues done that were planned |
| Unplanned Issues Done | Referenced |	Number of issues done that were NOT planned |
| Bugs (Issues) | Referenced | Total Amount of bug issues done during this sprint (planned or unplanned) |
| Total Issues Done | Calculated | Total amount of issues done during this sprint |
| Planned Issues NOT Done	| Calculated | Total amount of issues planned that were NOT done |
| % Planned Issues | Calculated | % of planned issues done in this sprint |
| % Unplanned Issues | Calculated | % of unplanned issues done in this sprint |
| Planned SP Done	| Referenced | Number of Story Points Done that were planned |
| Unplanned SP Done | Referenced | Number of Story Points Done that were NOT planned |
| Bugs (SP)	| Referenced | SP of bugs done during this sprint (planned or unplanned) |
| Total SP Done	| Calculated | Total amount of Story Points done during this sprint |
| Planned SP NOT Done	| Calculated | Total amount of Story Points planned that were NOT done |
| % Planned SP	| Calculated | % of planned story points done in this sprint |
| % Unplanned SP | Calculated | % of unplanned story points done in this sprint |
| % Compliance	| Calculated | % compliance with what was planned: SP Done / Sp Planned |
| Ratio SP / issue	| Calculated | Story Points per issue ratio |
| SP / Hours	| Calculated | Team effectiveness in terms of value delivery per hour worked |
| Hours Next Sprint	| Referenced | Estimation of team avaliability hours for next sprint |
| Estimated Total SP | Calculated | Used to plan next sprint. SP that should be for next sprint regarding average delivery of the previous 5 sprints and team capacity |
| Estimated SP Planned	| Calculated | Used to plan next sprint. SP that should be planned for next sprint regarding estimated total SP minus possible unplanned work |
| Estimated SP Unplanned	| Calculated | Used to plan next sprint. Unplanned SP that the team would have next sprint regarding average of unplanned SP for the previous 5 sprints |
| Estimated % Compliance	| Calculated | % of estimated team compliance taking in account the average of the previous 5 sprints |
| Compliance final % var	| Calculated | % of compliance final variation on what was predicted and what finally was |

> [!NOTE]
> The *referenced* data is obtained from the *Sprint_details* sheet.

***

### Pivot Tables

This worksheet cointains dynamically generated pivot tables that have been created to populate the dashboard.

<kbd>![SM Excel Dashboard - pivot table](https://github.com/XaviVelasco/Scrum-Master-Excel-Dashboard/blob/6b7871554fa1efa71de40b518bda2416cc1067c8/assets/img/SM%20Excel%20Dashboard%20-%20pivot%20table.png)

***

### Dashboard

The dashboard created in this Excel file is a powerful tool for Scrum Masters and Product Owners, providing several key insights. It is a visual representation of key performance indicators (KPIs) tailored for the Scrum Master. The dashboard highlights team velocity, defect trends, and other critical metrics, as well as next sprint forecasting.

- **Sprint Performance Tracking**: By comparing planned versus completed tasks, the dashboard allows Scrum Masters to assess the team's ability to meet sprint goals. This is crucial for maintaining team productivity and identifying any obstacles early on.
- **Unplanned Work Monitoring**: The dashboard tracks the occurrence of unplanned tasks and their impact on the sprint. This helps in understanding scope creep and its effect on the team's ability to deliver on their commitments.
- **Bug Tracking**: By including bug fixes in the analysis, the dashboard helps in assessing the quality of the work delivered and the effectiveness of the team in addressing issues as they arise.
- **Compliance Rates**: The dashboard tracks compliance with sprint goals, providing a clear picture of the team's reliability and consistency over time. This metric is particularly useful for long-term planning and resource allocation.
- **Resource Utilization**: By analyzing the hours worked and story points delivered, the dashboard provides insights into how effectively the team's resources are being utilized. This can inform decisions about team capacity and workload management.


<kbd>![SM Excel Dashboard - Dashboard](https://github.com/XaviVelasco/Scrum-Master-Excel-Dashboard/blob/0d3387deb4ab816f0b4cb41eb08c7c2d9fa0441a/assets/img/SM%20Excel%20Dashboard%20-%20Dashboard.png)
