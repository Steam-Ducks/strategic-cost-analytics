# Sprint 3 Backlog

## Sprint
**Sprint 3**  
**Period:** 05/11/2026 to 05/31/2026

---

## Sprint Goal
Complete the SCAR solution with authentication, access control, export, traceability, audit features, CSV import improvements, and advanced analytical views for technical hours, material consumption, and financial monitoring.

---

## Sprint Objective
Deliver the final analytical and operational features of the SCAR platform, including secure authentication, role-based access control, export resources, audit and traceability capabilities, financial monitoring enhancements, and advanced analytical visualizations.

---

# Sprint User Stories

## US01 — Authenticate in the system

**User Story**  
As a user, I want to authenticate in the system so that I can access the analytical environment securely.

### Description
The system must allow authentication using username and password and grant access according to the authenticated user.

### Definition of Ready (DoR)
- Authentication rules are defined
- Login flow is mapped

### Definition of Done (DoD)
- Authentication is implemented
- Access works correctly
- Tests are approved

### Tasks
- Implement login endpoint
- Implement authentication validation rules
- Generate authentication token after valid login
- Protect private routes and endpoints
- Create login screen
- Implement login form validations
- Integrate login screen with authentication API
- Implement session persistence
- Implement front-end route protection
- Implement visual feedback for authentication errors

---

## US02 — Access functionalities according to user profile

**User Story**  
As an authenticated user, I want to access functionalities according to my user type so that I can use the application with the correct permission level.

### Description
The system must support role-based access control using predefined user profiles.

### Definition of Ready (DoR)
- User profiles are defined
- Access rules are defined

### Definition of Done (DoD)
- Access restrictions are implemented
- Permissions are validated
- Tests are approved

### Tasks
- Define user profiles in the system
- Implement authorization rules by profile
- Protect restricted endpoints
- Restrict access to sensitive information
- Validate unauthorized access attempts
- Implement profile validation in front-end navigation

---

## US20 — View material consumption over time

**User Story**  
As an analyst, I want to view material consumption over time so that I can identify increases, reductions, and seasonality in material usage.

### Description
The system must display the temporal evolution of material consumption and material costs by period.

### Definition of Ready (DoR)
- Temporal granularity is defined
- Material consumption rules are defined
- Historical data is available

### Definition of Done (DoD)
- Temporal visualization is implemented
- Aggregations are correct
- Tests are approved

### Tasks
- Create queries for material consumption evolution
- Create endpoint for material consumption evolution
- Implement filters for material temporal analysis
- Implement aggregation logic for temporal analysis
- Implement error handling for material consumption requests
- Create material consumption evolution section in materials dashboard
- Integrate temporal visualization with backend endpoint
- Create material consumption evolution chart component
- Integrate filters with temporal material analysis
- Implement loading, empty, and error states

---

## US24 — View hours by project

**User Story**  
As a manager, I want to view hours by project so that I can identify where the greatest technical effort is allocated.

### Description
The system must display a comparative visualization of total worked hours grouped by project.

### Definition of Ready (DoR)
- Aggregation by project is defined
- Hours data is available

### Definition of Done (DoD)
- Visualization is implemented
- Calculations are correct
- Tests are approved

### Tasks
- Create queries for technical hours by project
- Create endpoint for technical hours by project
- Implement filters for technical hours analysis
- Implement aggregation logic for project analysis
- Implement error handling for technical hours requests
- Create technical hours by project section in dashboard
- Integrate technical hours visualization with backend endpoint
- Create comparative technical hours chart by project
- Integrate filters in technical hours visualization
- Implement loading, empty, and error states

---

## US25 — View technical hours cost by collaborator

**User Story**  
As a manager, I want to view technical hours cost by collaborator so that I can analyze where labor cost is concentrated.

### Description
The system must display comparative visualization of accumulated technical hours cost grouped by collaborator.

### Definition of Ready (DoR)
- Aggregation rules are defined
- Collaborator data is available

### Definition of Done (DoD)
- Visualization is implemented
- Calculations are correct
- Tests are approved

### Tasks
- Create queries for technical hours cost by collaborator
- Create endpoint for technical hours cost by collaborator
- Implement filters in collaborator analysis endpoint
- Implement aggregation logic for collaborator analysis
- Implement error handling for collaborator requests
- Create collaborator cost section in technical hours dashboard
- Integrate collaborator visualization with backend endpoint
- Create collaborator cost chart component
- Integrate filters with collaborator visualization
- Implement loading, empty, and error states
- Implement sorting behavior for collaborator ranking

---

## US26 — View temporal evolution of technical hours

**User Story**  
As an analyst, I want to view the temporal evolution of technical hours so that I can analyze the execution pace over time.

### Description
The system must display the temporal evolution of technical hours and total hours cost by period.

### Definition of Ready (DoR)
- Temporal granularity is defined
- Historical technical hours data is available

### Definition of Done (DoD)
- Temporal visualization is implemented
- Aggregations are correct
- Tests are approved

### Tasks
- Create queries for technical hours temporal evolution
- Create endpoint for temporal evolution of technical hours
- Implement filters for temporal hours analysis
- Implement aggregation logic for temporal analysis
- Implement error handling for temporal analysis requests
- Create temporal evolution section in technical hours dashboard
- Integrate temporal visualization with backend endpoint
- Create technical hours temporal evolution chart component
- Integrate filters with temporal analysis visualization
- Implement loading, empty, and error states
- Implement chronological ordering behavior

---

## US28 — Export analytical data to CSV

**User Story**  
As a user, I want to export analytical data to CSV so that I can perform external analysis.

### Description
The system must allow exporting analytical data in CSV format while respecting applied filters.

### Definition of Ready (DoR)
- Export rules are defined
- Data source is available

### Definition of Done (DoD)
- CSV export is implemented
- Filters are preserved
- Tests are approved

### Tasks
- Create CSV export structure for analytical data
- Create endpoint for CSV export
- Implement filters integration in CSV export endpoint
- Implement analytical data selection for CSV export
- Implement standardized file naming
- Implement error handling for CSV export
- Create CSV export action in analytical screens
- Integrate export action with backend endpoint
- Implement loading and feedback states for export
- Implement export context validation

---

## US29 — Export analytical data to Excel

**User Story**  
As a user, I want to export analytical data to Excel so that I can share and manipulate analytical information.

### Description
The system must allow exporting analytical data in Excel format while respecting applied filters.

### Definition of Ready (DoR)
- Export rules are defined
- Data source is available

### Definition of Done (DoD)
- Excel export is implemented
- Filters are preserved
- Tests are approved

### Tasks
- Create Excel export structure for analytical data
- Create endpoint for Excel export
- Implement filters integration in Excel export endpoint
- Implement analytical data selection for Excel export
- Implement Excel formatting structure
- Implement standardized file naming
- Implement error handling for Excel export
- Create Excel export action in analytical screens
- Integrate export action with backend endpoint
- Implement loading and feedback states for export
- Implement export context validation

---

## US30 — View consolidated data traceability

**User Story**  
As an administrator, I want to trace consolidated analytical data so that I can audit the source system and original record.

### Description
The system must allow identification of the source system, original record identifier, and load timestamp of analytical data.

### Definition of Ready (DoR)
- Traceability metadata are defined
- Source identifiers are available

### Definition of Done (DoD)
- Traceability is implemented
- Consultation is available
- Tests are approved

### Tasks
- Create queries for traceability metadata
- Create endpoint for traceability data
- Apply analytical filters to traceability queries
- Implement error handling for traceability requests
- Create traceability table in audit screen
- Integrate traceability table with backend endpoint
- Implement filters integration for traceability visualization
- Implement loading, empty, and error states

---

## US31 — Identify integration and update failures

**User Story**  
As an administrator, I want to identify integration and update failures so that I can quickly react to analytical inconsistencies.

### Description
The system must display operational failures related to imports and data integrations.

### Definition of Ready (DoR)
- Failure events are defined
- Execution logs are available

### Definition of Done (DoD)
- Failure monitoring is implemented
- Failure details are available
- Tests are approved

### Tasks
- Create FATO_EXECUCAO_CARGA table structure
- Register execution logs during CSV imports
- Create queries for integration failure monitoring
- Create endpoint for integration failure monitoring
- Implement filters in integration monitoring endpoint
- Implement error handling for integration monitoring
- Create integration failure view in audit screen
- Integrate integration failure view with backend endpoint
- Create integration failure table component
- Integrate filters with failure monitoring
- Implement loading, empty, and error states
- Implement sorting behavior for execution records

---

## US33 — View data load history

**User Story**  
As an administrator, I want to view data load history so that I can monitor the freshness and reliability of the analytical environment.

### Description
The system must display historical execution records including status, timestamps, and processed volume.

### Definition of Ready (DoR)
- Execution logs are available
- Visualization structure is defined

### Definition of Done (DoD)
- History visualization is implemented
- Tests are approved

### Tasks
- Create queries for execution history monitoring
- Create endpoint for execution history monitoring
- Implement filters in execution history endpoint
- Implement error handling for execution history requests
- Create execution history view in audit screen
- Integrate execution history view with backend endpoint
- Create execution history table component
- Integrate filters with execution history visualization
- Implement loading, empty, and error states
- Implement sorting behavior for execution history

---

## US34 — View load failure details

**User Story**  
As an administrator, I want to view load failure details so that I can diagnose data import problems.

### Description
The system must allow detailed visualization of failed execution records.

### Definition of Ready (DoR)
- Failure logging is available

### Definition of Done (DoD)
- Detailed failure visualization is implemented
- Tests are approved

### Tasks
- Create queries for execution failure details
- Create endpoint for execution failure details
- Implement filters for execution failure details
- Implement error handling for failure detail requests
- Create execution failure details view in audit screen
- Integrate execution failure details view with backend endpoint
- Create execution failure details table component
- Integrate filters with failure details visualization
- Implement loading, empty, and error states
- Implement sorting behavior for failure details

---

## US35 — View access audit trail

**User Story**  
As an administrator, I want to view the access audit trail so that I can track authentication and access events.

### Description
The system must record and display authentication and access events.

### Definition of Ready (DoR)
- Audit events are defined
- Logging structure is available

### Definition of Done (DoD)
- Audit trail is implemented
- Consultation is available
- Tests are approved

### Tasks
- Create access log registration structure
- Register successful and failed authentication events
- Create endpoint for audit trail consultation
- Implement filters for audit trail consultation
- Create audit trail visualization in audit screen
- Integrate audit trail with backend endpoint
- Implement loading, empty, and error states
- Implement sorting behavior for access logs

---

## US39 — View projected budget overrun

**User Story**  
As a manager, I want to view projected budget overrun so that I can anticipate financial risks.

### Description
The system must calculate and display projected budget overrun based on the difference between actual cost and estimated budget.

### Definition of Ready (DoR)
- Projection rules are defined
- Budget and actual cost data are available

### Definition of Done (DoD)
- Projection calculation is implemented
- Visualization is implemented
- Tests are approved

### Tasks
- Create queries for budget overrun projection analysis
- Create endpoint for budget overrun projection analysis
- Implement filters in projection endpoint
- Implement projection aggregation logic
- Implement error handling for projection requests
- Create budget overrun projection section in financial screen
- Integrate projection visualization with backend endpoint
- Create budget overrun projection chart component
- Integrate filters with projection visualization
- Implement loading, empty, and error states
- Implement sorting behavior for projected overruns

---

## US40 — Import data through CSV files

**User Story**  
As an analytical system, I want to import data through CSV files so that analytical tables can be updated manually.

### Description
The system must allow manual CSV uploads for dimensions and fact tables through the audit screen.

### Definition of Ready (DoR)
- Analytical tables are defined
- CSV layout is defined
- Validation rules are defined

### Definition of Done (DoD)
- CSV upload is implemented
- Processing is functioning correctly
- Execution logging is implemented
- Tests are approved

### Tasks
- Create CSV import structure
- Implement CSV parsing and normalization
- Implement insertion into analytical tables
- Implement execution logging during imports
- Create endpoint for CSV imports
- Implement error handling for CSV imports
- Create CSV import view in audit screen
- Create CSV upload components
- Integrate import flow with backend endpoint
- Display import execution results
- Implement loading and error states
- Refresh execution history after imports

---

## US41 — View financial health indicators

**User Story**  
As a manager, I want to view financial health indicators so that I can quickly understand the financial situation of projects.

### Description
The system must display financial health indicators based on budget, actual cost, deviation percentage, and project classification.

### Definition of Ready (DoR)
- Financial indicators are defined
- Financial rules are defined
- Data sources are available

### Definition of Done (DoD)
- Financial indicators are implemented
- Calculations are validated
- Tests are approved

### Tasks
- Create queries for financial health indicators
- Create endpoint for financial health indicators
- Implement filters in financial health indicators endpoint
- Implement aggregation logic for financial indicators
- Implement error handling for financial indicator requests
- Create financial health indicators section
- Integrate financial indicators with backend endpoint
- Create financial indicator cards
- Integrate filters with financial indicators
- Implement loading, empty, and error states

---

## US42 — Filter budget and financial health analysis

**User Story**  
As an analyst, I want to filter budget and financial health analysis so that I can refine financial monitoring by analytical context.

### Description
The system must support filtering financial analysis by period, program, project, and financial health classification.

### Definition of Ready (DoR)
- Filter fields are defined
- Filter rules are defined
- Data sources are available

### Definition of Done (DoD)
- Financial filters are implemented
- Integration with analytical components is working
- Tests are approved

### Tasks
- Create queries for financial health filters
- Create endpoint for financial health filters
- Implement financial health filters logic
- Integrate filters with financial analysis endpoints
- Implement error handling for financial filters
- Create financial health filters section
- Create filter components for financial analysis
- Integrate financial filters with backend endpoint
- Integrate filters with analytical components
- Implement filters state management
- Implement loading, empty, and error states

---

## US43 — View financial summary table

**User Story**  
As a manager, I want to view a financial summary table so that I can compare budget, actual cost, financial health, and projected overrun.

### Description
The system must display a financial summary table with budget and financial health information grouped by program and project.

### Definition of Ready (DoR)
- Table columns are defined
- Financial rules are defined
- Data sources are available

### Definition of Done (DoD)
- Financial summary table is implemented
- Filters and sorting are working correctly
- Tests are approved

### Tasks
- Create queries for financial summary table
- Create endpoint for financial summary table
- Implement filters in financial summary table endpoint
- Implement aggregation logic for financial summary table
- Implement error handling for financial summary table requests
- Create financial summary table section
- Integrate financial summary table with backend endpoint
- Create financial summary table component
- Integrate filters with financial summary visualization
- Implement sorting behavior for financial summary table
- Implement loading, empty, and error states

---

# Sprint User Stories Summary

| ID | User Story | Priority | Points | Status |
|----|------------|----------|--------|--------|
| US01 | Authenticate in the system | Low | 2 | Planned |
| US02 | Access functionalities according to user profile | Low | 2 | Planned |
| US20 | View material consumption over time | Medium | 3 | Planned |
| US24 | View hours by project | Medium | 3 | Planned |
| US25 | View technical hours cost by collaborator | Low | 3 | Planned |
| US26 | View temporal evolution of technical hours | Low | 3 | Planned |
| US28 | Export analytical data to CSV | Low | 2 | Planned |
| US29 | Export analytical data to Excel | Low | 2 | Planned |
| US30 | View consolidated data traceability | Low | 3 | Planned |
| US31 | Identify integration and update failures | Low | 3 | Planned |
| US33 | View data load history | Low | 3 | Planned |
| US34 | View load failure details | Low | 3 | Planned |
| US35 | View access audit trail | Low | 3 | Planned |
| US39 | View projected budget overrun | Medium | 2 | Planned |
| US40 | Import data through CSV files | High | 1 | Planned |
| US41 | View financial health indicators | Medium | 2 | Planned |
| US42 | Filter budget and financial health analysis | Medium | 2 | Planned |
| US43 | View financial summary table | Medium | 2 | Planned |

**Total planned points:** 44

---

<!--

# Evidence

## Wireframes
- Dashboard Wireframe: https://www.figma.com/make/v1S1QcC1TETZXjW7fsROmZ/Minimalist-Dashboard?p=f&t=rTUNyg9AzobuhCrQ-0&fullscreen=1&preview-route=%2Fdashboard

## Quality and Monitoring
- Add burndown evidence in ../../assets/sprint-3/
- Add SonarQube evidence in ../../assets/sprint-3/

## Presentation
- Add Sprint 3 presentation link here

## Demo Video
- Add Sprint 3 demo video link here

---

-->

# Sprint Status

**In Progress**