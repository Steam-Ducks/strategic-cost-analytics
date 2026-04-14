# Sprint 2 Backlog

## Sprint
**Sprint 2**  
**Period:** 04/13/2026 to 05/03/2026

---

## Sprint Goal
Expand the analytical capabilities of the solution by enhancing the main dashboard with new strategic visualizations, evolving the materials analysis, introducing the technical hours analysis screen, enabling budget and financial health visibility, and supporting CSV-based data import.

---

## Sprint Objective
Deliver a second functional version of the solution with richer dashboard analysis, an initial consolidated analytical view, more advanced materials filters, the base structure of the technical hours screen, financial monitoring indicators, and CSV import support in the current project scope.

---

## Sprint User Stories

### US12 — Cost Composition Between Materials and Technical Hours

**User Story**  
As a manager, I want to view the cost composition between materials and technical hours so that I can understand the weight of each component in the total cost.

**Description**  
The system must display a comparative visualization showing the composition of the consolidated cost, separating materials and technical hours.

**Definition of Ready (DoR)**
- Cost categories are defined  
- Consolidated data is available  

**Definition of Done (DoD)**
- Visualization is implemented  
- Percentage calculations are correct  
- Tests are approved  

**Tasks**
- Create a chart comparing materials versus technical hours on the main dashboard  
- Feed the graph of materials vs. technical hours with data  

---

### US13 — Materials with the Highest Financial Impact

**User Story**  
As a manager, I want to view the materials with the highest financial impact so that I can identify critical cost items.

**Description**  
The system must display a ranking of the materials with the highest total cost in the selected period.

**Definition of Ready (DoR)**
- Aggregation by material is defined  
- Material data is available  

**Definition of Done (DoD)**
- Ranking is implemented  
- Ordering is correct  
- Tests are approved  

**Tasks**
- Create a ranking of materials with the greatest financial impact  
- Feed the table of materials with the greatest financial impact  

---

### US14 — Projects with the Highest Cost

**User Story**  
As a manager, I want to view the projects with the highest cost so that I can prioritize managerial attention on the most relevant projects.

**Description**  
The system must display a ranking of projects with the highest consolidated cost in the selected period.

**Definition of Ready (DoR)**
- Aggregation by project is defined  
- Consolidated project data is available  

**Definition of Done (DoD)**
- Ranking is implemented  
- Calculation is correct  
- Tests are approved  

**Tasks**
- Create a ranking of highest costs by project  
- Feed the ranking table of highest costs per project  

---

### US15 — Summary Table in the Dashboard

**User Story**  
As an analyst, I want to view a summary table in the dashboard so that I can validate and compare the values shown in the charts.

**Description**  
The dashboard must display a summary table with the main aggregates of the selected context.

**Definition of Ready (DoR)**
- Table columns are defined  
- Consolidated data is available  

**Definition of Done (DoD)**
- Table is implemented  
- Integration with data is working  
- Tests are approved  

**Tasks**
- Create a summary table in the main dashboard  
- Feed summary table of the main dashboard  

---

### US18 — Filter Material Analysis by Item, Supplier, and Category

**User Story**  
As an analyst, I want to filter material analysis by item, supplier, and category so that I can refine the investigation of cost and consumption from different perspectives.

**Description**  
The materials analysis screen must allow filters by period, program, project, material, supplier, and supplier category.

**Definition of Ready (DoR)**
- Filter fields are defined  
- Filter application rules are defined  

**Definition of Done (DoD)**
- Filters are implemented  
- Screen updates correctly  
- Tests are approved  

**Tasks**
- Create a visualization of material filters in the materials dashboard  
- Create endpoints for material dashboard filters  

---

### US19 — Material Cost by Project

**User Story**  
As a manager, I want to view material cost by project so that I can understand the financial impact of materials in each project.

**Description**  
The system must display a comparative visualization of total material cost by project.

**Definition of Ready (DoR)**
- Aggregation by project is defined  
- Material data by project is available  

**Definition of Done (DoD)**
- Visualization is implemented  
- Calculations are correct  
- Tests are approved  

**Tasks**
- Create a ranking of material costs by project  
- Feed ranking of material costs by project  

---

### US21 — Base Structure of the Technical Hours Screen

**User Story**  
As an analyst, I want to view the base structure of the technical hours screen so that I can access an organized view of effort and labor cost by project.

**Description**  
The technical hours screen must present its main structure, including filters, analytical visualizations, and tabular area, with consistent loading, error, and no-data states.

**Definition of Ready (DoR)**
- Screen structure is defined  
- Wireframe is approved  
- Main components are defined  

**Definition of Done (DoD)**
- Structure is implemented  
- Visual states are implemented  
- Tests are approved  

**Tasks**
- Create the front end for the technical hours screen  
- Create a technical hours dashboard  

---

### US22 — Indicators and Table in the Technical Hours Analysis Screen

**User Story**  
As an analyst, I want to view indicators and a table in the technical hours analysis screen so that I can monitor cost and effort by project.

**Description**  
The technical hours screen must display analytical indicators and a table with the main hours and labor cost data, respecting the applied filters.

**Definition of Ready (DoR)**
- Indicators are defined  
- Table columns are defined  
- Data sources are available  

**Definition of Done (DoD)**
- Indicators are implemented  
- Table is implemented  
- Integration with data is working  
- Tests are approved  

**Tasks**
- Create indicators on the technical hours dashboard  
- Create endpoints for indicators in the technical hours dashboard  

---

### US23 — Filter Technical Hours Analysis by Employee, Role, and Task

**User Story**  
As an analyst, I want to filter technical hours analysis by employee, role, and task so that I can refine the investigation of technical effort from different perspectives.

**Description**  
The technical hours screen must allow filters by period, program, project, employee, role, and task.

**Definition of Ready (DoR)**
- Filter fields are defined  
- Filter rules are defined  

**Definition of Done (DoD)**
- Filters are implemented  
- Screen updates correctly  
- Tests are approved  

**Tasks**
- Create filters for technical hours dashboard  
- Create endpoints for the filters in the technical hours dashboard  

---

### US27 — Consolidated Cost Screen

**User Story**  
As a manager, I want to view a consolidated cost screen so that I can compare materials and technical hours in a single view by project and program.

**Description**  
The system must display a consolidated cost view including global filters, comparative charts, and a consolidated table.

**Definition of Ready (DoR)**
- Consolidation rules are defined  
- Consolidated data is available  

**Definition of Done (DoD)**
- Screen is implemented  
- Integration is completed  
- Tests are approved  

**Tasks**
- Create a cost consolidation screen  

---

### US32 — Latest Data Update

**User Story**  
As a user, I want to view the date of the latest data update so that I know whether the information shown is up to date.

**Description**  
The system must display the latest update date and time in the relevant analytical contexts.

**Definition of Ready (DoR)**
- Latest update source is defined  

**Definition of Done (DoD)**
- Information is implemented  
- Tests are approved  

**Tasks**
- View the date of the last data import on the cost consolidation screen  

---

### US36 — Budget by Program and Project

**User Story**  
As a manager, I want to view budget by program and project so that I can compare planned values with actual costs.

**Description**  
The system must allow visualization of budget by program and estimated budget by project, according to the defined distribution rule.

**Definition of Ready (DoR)**
- Budget rule by program is defined  
- Project budget distribution rule is defined  
- Budget source is available  

**Definition of Done (DoD)**
- Visualization is implemented  
- Calculations are validated  
- Integration with data is working  
- Tests are approved  

**Tasks**
- Create budget and financial health screen  
- Create a real cost chart per project on the budget and financial health screen  
- Create a backend for a real cost graph per project on the budget and financial health screen  

---

### US37 — Percentage Deviation of Projects

**User Story**  
As a manager, I want to view the percentage deviation of projects so that I can understand budget consumption relative to the estimated budget.

**Description**  
The system must calculate and display the percentage deviation of each project based on the relationship between consolidated actual cost and estimated project budget.

**Definition of Ready (DoR)**
- Deviation calculation rule is defined  
- Actual cost and budget sources are available  

**Definition of Done (DoD)**
- Calculation is implemented  
- Visualization is implemented  
- Tests are approved  

**Tasks**
- Create a percentage deviation chart by project  
- Create a backend for a standard deviation chart by project on the budget screen  

---

### US38 — Financial Health Status of Projects

**User Story**  
As a manager, I want to view the financial health status of projects so that I can identify which projects are healthy, under attention, or critical.

**Description**  
The system must classify projects according to the defined financial health rule, using the deviation percentage between consolidated actual cost and estimated budget.

**Definition of Ready (DoR)**
- Financial health rule is defined  
- Deviation rule is defined  
- Actual cost and budget data are available  

**Definition of Done (DoD)**
- Classification is implemented  
- Visualization is implemented  
- Tests are approved  

**Tasks**
- Create financial health cards for the projects  
- Create a backend to feed financial health cards for projects  

---

### US40 — CSV Data Import

**User Story**  
As an analytical system, I want to receive data through CSV files provided by the client so that the initial load and data preparation can be performed without depending on API integration.

**Description**  
The system must support ingestion of the CSV files provided by the client as the official source of data in the current scope. The import must include minimum structural validation, staging load, and availability for analytical transformation.

**Definition of Ready (DoR)**
- List of CSV files is defined  
- Expected minimum structure of each file is known  
- Structural validation rules are defined  
- Staging load strategy is defined  

**Definition of Done (DoD)**
- CSV import process is implemented  
- Structural validations are implemented  
- Staging load is working correctly  
- Imported data is available for transformation  
- Tests are approved  

**Tasks**
- Define CSV input data flow provided by the client  

---

## Sprint User Stories Summary

| ID | User Story | Points | Status |
|----|------------|--------|--------|
| US12 | Cost composition between materials and technical hours | 6 | To Do |
| US13 | Materials with the highest financial impact | 6 | To Do |
| US14 | Projects with the highest cost | 6 | To Do |
| US15 | Summary table in the dashboard | 8 | To Do |
| US18 | Filter material analysis by item, supplier, and category | 9 | To Do |
| US19 | Material cost by project | 6 | To Do |
| US21 | Base structure of the technical hours screen | 3 | To Do |
| US22 | Indicators and table in the technical hours analysis screen | 4 | To Do |
| US23 | Filter technical hours analysis by employee, role, and task | 9 | To Do |
| US27 | Consolidated cost screen | 3 | To Do |
| US32 | Latest data update | 1 | To Do |
| US36 | Budget by program and project | 6 | To Do |
| US37 | Percentage deviation of projects | 6 | To Do |
| US38 | Financial health status of projects | 7 | To Do |
| US40 | CSV data import | 0 | To Do |

**Total planned points:** 80

---

## Evidence

### Wireframes
- [Dashboard Wireframe](https://www.figma.com/make/v1S1QcC1TETZXjW7fsROmZ/Minimalist-Dashboard?p=f&t=rTUNyg9AzobuhCrQ-0&fullscreen=1&preview-route=%2Fdashboard)

### Screenshots
- Add screenshots from `../../assets/sprint-2/`

### Quality and Monitoring
- Add burndown from `../../assets/sprint-2/`
- Add SonarQube evidence from `../../assets/sprint-2/`

### Presentation
- 

### Demo Video
- 

---

## Sprint Summary

- Planned User Stories: 15  
- Planned Story Points: 80  
- Sprint source aligned with Jira tasks exported for Sprint 2  

---

## Sprint Status
**In Progress**
