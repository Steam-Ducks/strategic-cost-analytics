# Sprint 1 Backlog

## Sprint
**Sprint 1**  
**Period:** 03/16/2026 to 04/05/2026

---

## Sprint Goal
Deliver the initial structure of the analytical solution, including the first functional version of the main dashboard and the materials analytics screen, allowing stakeholders to view strategic indicators, apply global filters, and validate the first consolidated data with the client.

---

## Sprint Objective
Provide a first navigable version of the main dashboard with key indicators, charts, and basic filters, along with the initial structure of the materials analytics screen, enabling functional and visual validation of the solution.

---

## Sprint User Stories

| ID | User Story | Priority | Points | Status |
|----|------------|----------|--------|--------|
| US04 | View the base structure of the main dashboard | Highest | 2 | Planned |
| US05 | View the main dashboard indicators | Highest | 3 | Planned |
| US06 | Filter the dashboard by period | Highest | 2 | Planned |
| US07 | Filter the dashboard by program and project | Highest | 3 | Planned |
| US08 | View the consolidated total cost | Highest | 2 | Planned |
| US09 | View the total cost by program | High | 2 | Planned |
| US10 | View the total cost by project | High | 2 | Planned |
| US11 | View the cost trend over time | High | 3 | Planned |
| US16 | View the base structure of the materials analytics screen | High | 2 | Planned |
| US17 | View indicators and table in the materials analysis screen | High | 3 | Planned |

**Total planned points:** 24

---

## Sprint Tasks

### US04 — View the base structure of the main dashboard
| Task | Owner | Status |
|------|-------|--------|
| Create PostgreSQL staging tables for dashboard data |  | To Do |
| Implement initial CSV data ingestion into the staging layer |  | To Do |
| Implement data transformation from staging to the dimensional model |  | To Do |
| Create the main dashboard base query |  | To Do |
| Create the main dashboard backend endpoint |  | To Do |
| Create the last data update backend endpoint |  | To Do |
| Implement success, error, and no-data handling in the backend |  | To Do |
| Create the base dashboard page in the frontend |  | To Do |
| Implement the indicators section in the dashboard |  | To Do |
| Implement the charts section in the dashboard |  | To Do |
| Implement the global filters section in the dashboard |  | To Do |
| Implement the summary table section in the dashboard |  | To Do |
| Implement the last update display in the frontend |  | To Do |
| Implement the dashboard loading state |  | To Do |
| Implement the dashboard error state |  | To Do |
| Implement the dashboard no-data state |  | To Do |
| Integrate the frontend with the dashboard endpoints |  | To Do |
| Create backend tests for the main dashboard |  | To Do |
| Create frontend tests for the main dashboard |  | To Do |

### US05 — View the main dashboard indicators
| Task | Owner | Status |
|------|-------|--------|
| Implement loading of analytical materials data into the Data Warehouse |  | To Do |
| Implement loading of analytical labor-hours data into the Data Warehouse |  | To Do |
| Create backend tests for the main indicators |  | To Do |
| Create frontend tests for the main indicators |  | To Do |
| Implement the SQL query for the main dashboard indicators |  | To Do |
| Implement the consolidated total cost calculation |  | To Do |
| Implement the total materials cost calculation |  | To Do |
| Implement the total labor-hours cost calculation |  | To Do |
| Implement the project count calculation |  | To Do |
| Implement the program count calculation |  | To Do |
| Create the backend endpoint for the main indicators |  | To Do |
| Implement standardized indicator responses in the backend |  | To Do |
| Create the visual component for indicator cards in the frontend |  | To Do |
| Display the consolidated total cost indicator in the frontend |  | To Do |
| Display the total materials cost indicator in the frontend |  | To Do |
| Display the total labor-hours cost indicator in the frontend |  | To Do |
| Display the project count indicator in the frontend |  | To Do |
| Display the program count indicator in the frontend |  | To Do |
| Implement value formatting for the indicators |  | To Do |
| Integrate the main indicators into the frontend |  | To Do |

### US06 — Filter the dashboard by period
| Task | Owner | Status |
|------|-------|--------|
| Implement loading of the time dimension into the Data Warehouse |  | To Do |
| Ensure period relationships with the dashboard analytical facts |  | To Do |
| Create backend tests for the period filter |  | To Do |
| Create frontend tests for the period filter |  | To Do |
| Implement period filtering in the main indicators SQL query |  | To Do |
| Implement period filtering in the dashboard charts SQL query |  | To Do |
| Implement period filtering in the summary table SQL query |  | To Do |
| Create backend support for the period parameter |  | To Do |
| Apply the period filter to the dashboard endpoints |  | To Do |
| Standardize the API response with applied filter information |  | To Do |
| Create the period filter component in the frontend |  | To Do |
| Integrate the period filter with the dashboard endpoints |  | To Do |
| Update dashboard indicators when the period filter is applied |  | To Do |
| Update charts when the period filter is applied |  | To Do |
| Update the summary table when the period filter is applied |  | To Do |
| Implement clearing of the period filter |  | To Do |
| Display the active period filter in the dashboard |  | To Do |

### US07 — Filter the dashboard by program and project
| Task | Owner | Status |
|------|-------|--------|
| Implement loading of the program dimension into the Data Warehouse |  | To Do |
| Implement loading of the project dimension into the Data Warehouse |  | To Do |
| Ensure the relationship between program and project in the dimensional model |  | To Do |
| Ensure the relationship of program and project with the dashboard analytical facts |  | To Do |
| Create backend tests for the program and project filters |  | To Do |
| Create frontend tests for the program and project filters |  | To Do |
| Implement program filtering in the main indicators SQL query |  | To Do |
| Implement project filtering in the main indicators SQL query |  | To Do |
| Implement program filtering in the dashboard charts SQL query |  | To Do |
| Implement project filtering in the dashboard charts SQL query |  | To Do |
| Implement program and project filtering in the summary table SQL query |  | To Do |
| Create backend support for the program and project parameters |  | To Do |
| Apply the program and project filters to the dashboard endpoints |  | To Do |
| Implement a standardized API response with active filter information |  | To Do |
| Create the program filter component in the frontend |  | To Do |
| Create the project filter component in the frontend |  | To Do |
| Implement chained behavior between program and project in the frontend |  | To Do |
| Integrate the program and project filters with the dashboard endpoints |  | To Do |
| Update dashboard indicators when the program and project filters are applied |  | To Do |
| Update charts when the program and project filters are applied |  | To Do |
| Update the summary table when the program and project filters are applied |  | To Do |
| Implement clearing of the program and project filters |  | To Do |
| Display active filters in the dashboard |  | To Do |

### US08 — View the consolidated total cost
| Task | Owner | Status |
|------|-------|--------|
| Implement loading of analytical materials data into the Data Warehouse |  | To Do |
| Implement loading of analytical labor-hours data into the Data Warehouse |  | To Do |
| Ensure relationships between analytical facts and dashboard dimensions |  | To Do |
| Create backend tests for the consolidated total cost |  | To Do |
| Create frontend tests for the consolidated total cost indicator |  | To Do |
| Implement the SQL query for the consolidated total cost |  | To Do |
| Implement the consolidated total cost calculation in the backend |  | To Do |
| Apply filters to the consolidated total cost calculation |  | To Do |
| Create the backend endpoint for the consolidated total cost |  | To Do |
| Implement a standardized indicator response in the backend |  | To Do |
| Create the visual component for the consolidated total cost indicator in the frontend |  | To Do |
| Display the consolidated total cost value in the frontend |  | To Do |
| Implement currency formatting for the indicator in the frontend |  | To Do |
| Integrate the consolidated total cost indicator into the frontend |  | To Do |
| Update the indicator according to the applied filters |  | To Do |

### US09 — View the total cost by program
| Task | Owner | Status |
|------|-------|--------|
| Implement loading of analytical materials data by program into the Data Warehouse |  | To Do |
| Implement loading of analytical labor-hours data by program into the Data Warehouse |  | To Do |
| Ensure relationships between analytical facts, program, and time |  | To Do |
| Create backend tests for total cost by program |  | To Do |
| Create frontend tests for the total cost by program visualization |  | To Do |
| Implement the SQL query for total cost by program |  | To Do |
| Implement the consolidated cost calculation by program in the backend |  | To Do |
| Apply filters to the total cost by program calculation |  | To Do |
| Create the backend endpoint for the cost-by-program chart |  | To Do |
| Implement a standardized chart response in the backend |  | To Do |
| Create the visual component for the cost-by-program chart in the frontend |  | To Do |
| Display consolidated cost by program in the frontend |  | To Do |
| Implement visual formatting for chart values |  | To Do |
| Integrate the cost-by-program chart into the frontend |  | To Do |
| Update the chart according to the applied filters |  | To Do |
| Implement click interaction in the chart, if applicable |  | To Do |

### US10 — View the total cost by project
| Task | Owner | Status |
|------|-------|--------|
| Implement loading of analytical materials data by project into the Data Warehouse |  | To Do |
| Implement loading of analytical labor-hours data by project into the Data Warehouse |  | To Do |
| Ensure relationships between analytical facts, project, and time |  | To Do |
| Create backend tests for total cost by project |  | To Do |
| Create frontend tests for the total cost by project visualization |  | To Do |
| Implement the SQL query for total cost by project |  | To Do |
| Implement the consolidated cost calculation by project in the backend |  | To Do |
| Apply filters to the total cost by project calculation |  | To Do |
| Create the backend endpoint for the total cost by project visualization |  | To Do |
| Implement a standardized response for the visualization in the backend |  | To Do |
| Create the visual component for the cost-by-project chart and/or table in the frontend |  | To Do |
| Display consolidated cost by project in the frontend |  | To Do |
| Implement visual formatting for the values in the visualization |  | To Do |
| Implement sorting of the visualization by project |  | To Do |
| Integrate the cost-by-project visualization into the frontend |  | To Do |
| Update the visualization according to the applied filters |  | To Do |
| Implement navigation to details, if applicable |  | To Do |

### US11 — View the cost trend over time
| Task | Owner | Status |
|------|-------|--------|
| Implement loading of the time dimension into the Data Warehouse for time-based analysis |  | To Do |
| Implement loading of analytical materials data for time-based analysis |  | To Do |
| Implement loading of analytical labor-hours data for time-based analysis |  | To Do |
| Ensure relationships between analytical facts, time, project, and program |  | To Do |
| Create backend tests for the cost trend over time |  | To Do |
| Create frontend tests for the time-based cost visualization |  | To Do |
| Implement the SQL query for the cost trend over time |  | To Do |
| Implement temporal cost aggregation in the backend |  | To Do |
| Apply filters to the cost trend calculation |  | To Do |
| Handle periods with no data in the time-based query |  | To Do |
| Create the backend endpoint for the cost trend over time |  | To Do |
| Implement a standardized response for the time-based visualization in the backend |  | To Do |
| Create the visual component for the time-based chart in the frontend |  | To Do |
| Display the cost trend over time in the frontend |  | To Do |
| Implement chronological ordering in the time-based visualization |  | To Do |
| Implement visual formatting for values and periods in the chart |  | To Do |
| Integrate the time-based chart into the frontend |  | To Do |
| Update the time-based visualization according to the applied filters |  | To Do |

### US16 — View the base structure of the materials analytics screen
| Task | Owner | Status |
|------|-------|--------|
| Implement loading of analytical materials data into the Data Warehouse |  | To Do |
| Implement loading of dimensions used in the materials screen |  | To Do |
| Ensure relationships between facts and dimensions in the materials analysis |  | To Do |
| Create backend tests for the base structure of the materials screen |  | To Do |
| Create frontend tests for the base structure of the materials screen |  | To Do |
| Implement the SQL query for the base structure of the materials screen |  | To Do |
| Create the backend endpoint for the materials analytics screen |  | To Do |
| Implement a standardized response for the materials screen in the backend |  | To Do |
| Create the base page for the materials analytics screen in the frontend |  | To Do |
| Implement the filter area of the materials screen |  | To Do |
| Implement the analytics visualization area of the materials screen |  | To Do |
| Implement the tabular area of the materials screen |  | To Do |
| Implement the materials screen loading state |  | To Do |
| Implement the materials screen error state |  | To Do |
| Implement the materials screen no-data state |  | To Do |
| Integrate frontend and backend for the materials analytics screen |  | To Do |

### US17 — View indicators and table in the materials analysis screen
| Task | Owner | Status |
|------|-------|--------|
| Implement loading of analytical materials data for indicators and table |  | To Do |
| Ensure relationships between materials data and analytical dimensions |  | To Do |
| Create backend tests for indicators and table in the materials analysis screen |  | To Do |
| Create frontend tests for indicators and table in the materials analysis screen |  | To Do |
| Implement the SQL query for the materials analysis indicators |  | To Do |
| Implement the SQL query for the materials analysis table |  | To Do |
| Implement the materials analysis indicator calculations in the backend |  | To Do |
| Apply filters to the indicators and the materials analysis table |  | To Do |
| Create the backend endpoint for the materials analysis indicators |  | To Do |
| Create the backend endpoint for the materials analysis table |  | To Do |
| Implement a standardized response for the indicators and table in the backend |  | To Do |
| Create visual components for the materials analysis indicators in the frontend |  | To Do |
| Create the visual component for the materials analysis table in the frontend |  | To Do |
| Display the materials analysis indicators in the frontend |  | To Do |
| Display the materials analysis table data in the frontend |  | To Do |
| Implement visual formatting for indicator and table values |  | To Do |
| Integrate the materials analysis indicators and table into the frontend |  | To Do |
| Update the indicators and table according to the applied filters |  | To Do |

---

## Sprint Evidence
- Wireframes: https://www.figma.com/make/v1S1QcC1TETZXjW7fsROmZ/Minimalist-Dashboard?p=f&t=rTUNyg9AzobuhCrQ-0&fullscreen=1&preview-route=%2Fdashboard
- Dashboard screenshots:
- Materials screen screenshots:
- Test evidence:
- SonarQube evidence:
- Burndown chart:
- Sprint presentation link:

---

## Sprint Status
**In progress**
