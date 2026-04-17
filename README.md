<div align="center">
<img src="assets/header.png" alt="SCAR project header" width="100%" />
</div>

## Introduction

This project was developed by **STEAM DUCKS**, a team of students from the 5th semester of the **Database program at FATEC São José dos Campos**.

The proposal is to build **SCAR**, an analytical solution for consolidating and visualizing strategic project costs, developed in partnership with **SIATT**.

The acronym **SCAR** comes from the original Portuguese project name, **Sistema de Controle e Acompanhamento de Recursos**.

The project aims to design and implement a **Data Warehouse** capable of consolidating data related to **materials**, **technical labor hours**, **projects**, **programs**, and **budget indicators**, enabling structured and historical analysis to support decision-making.

The platform is intended to provide multidimensional analysis from different perspectives such as **time**, **program**, **project**, **material**, **employee**, and **financial status**, increasing visibility, traceability, and predictability across strategic initiatives.

### SIATT: Industry Partner

**SIATT (Sistemas Integrados de Alto Teor Tecnológico)** is a Brazilian defense company specialized in critical embedded systems, high-technology integration for military applications, and intelligent missile systems.

One of its most relevant initiatives is **MANSUP (National Surface Anti-Ship Missile)**, a strategic Brazilian Navy project focused on reducing dependence on foreign suppliers in naval defense systems.

<br>

> Data Warehouse development;  
> Cost analytics and decision support;  
> Historical and multidimensional analysis;  
> Budget and financial health monitoring.


## Business Questions

The solution is expected to answer questions such as:

- How much did each project spend on materials?
- What is the total technical labor cost per project?
- What is the consolidated real cost per project or program?
- How do costs evolve over time?
- What is the estimated budget of each project?
- What is the percentage deviation of each project?
- What is the financial health classification of each project?
- Which projects are at risk of budget overrun?

## Functional Requirements

| ID | Functional Requirement | Related User Stories |
|---|---|---|
| FR01 | Display the main dashboard base structure. | US04 |
| FR02 | Display main dashboard KPIs and consolidated cost indicators. | US05, US08, US09, US10 |
| FR03 | Filter analytical views by period, program, and project. | US06, US07 |
| FR04 | Display historical cost evolution. | US11 |
| FR05 | Display the materials analysis screen structure and its main indicators. | US16, US17 |
| FR06 | Filter material analysis by item, supplier, and category. | US18 |
| FR07 | Display material cost analysis by project and over time. | US19, US20 |
| FR08 | Display cost composition between materials and labor hours. | US12 |
| FR09 | Display rankings of materials and projects with highest financial impact. | US13, US14 |
| FR10 | Display summary tables in the dashboard and in consolidated analytical views. | US15, US27 |
| FR11 | Display the technical labor analysis screen structure and its indicators. | US21, US22 |
| FR12 | Filter labor analysis by employee, role, and task. | US23 |
| FR13 | Display labor costs by project, employee, role, and over time. | US24, US25, US26 |
| FR14 | Display the last data refresh timestamp. | US32 |
| FR15 | Display budget by program and project. | US36 |
| FR16 | Display percentage deviation between planned budget and actual cost. | US37 |
| FR17 | Display project financial health classification. | US38 |
| FR18 | Display projected budget overrun risk. | US39 |
| FR19 | Import source data through CSV files. | US40 |
| FR20 | Export analytical data to CSV and Excel. | US28, US29 |
| FR21 | Display data lineage and source traceability for consolidated metrics. | US30 |
| FR22 | Display integration/update failures and detailed load history. | US31, US33, US34 |
| FR23 | Display audit trail related to system access and data operations. | US35 |

## Non-Functional Requirements

| ID | Item |
|---|---|
| NFR01 | Star and/or snowflake dimensional modeling. |
| NFR02 | Technical documentation for the repository and the solution architecture. |
| NFR03 | Installation guide. |
| NFR04 | User guide. |
| NFR05 | PostgreSQL as the main persistence layer. |
| NFR06 | Backend developed in Python with Django. |
| NFR07 | Frontend developed in Vue.js with TypeScript. |
| NFR08 | Continuous Integration pipeline with GitHub Actions. |
| NFR09 | Unit and integration tests. |
| NFR10 | Static analysis and code quality checks. |
| NFR11 | Data traceability, auditability, and analytical reliability. |
| NFR12 | Export operations must preserve active filters and analytical context. |

## Product Backlog

| ID | Epic | User Story | Priority | Points | Sprint |
|----|------|------------|----------|--------|--------|
| US01 | Access and Control | As a user, I want to authenticate in the system, so that I can access the analytical environment securely. | Low | 2 | 3 |
| US02 | Access and Control | As an authenticated user, I want to access features according to my user type, so that I can use the application with the appropriate level of access. | Low | 2 | 3 |
| US03 | Access and Control | As an administrator, I want to manage system users, so that I can keep application access updated and centrally controlled. | Low | 3 | 3 |
| US04 | Main Dashboard | As a manager, I want to view the base structure of the main dashboard, so that I can access the executive analytical view of the solution. | Highest | 2 | 1 |
| US05 | Main Dashboard | As a manager, I want to view the main dashboard indicators, so that I can quickly understand the main consolidated metrics. | Highest | 3 | 1 |
| US06 | Main Dashboard | As an analyst, I want to filter the dashboard by period, so that I can analyze cost evolution within specific time ranges. | Highest | 2 | 1 |
| US07 | Main Dashboard | As an analyst, I want to filter the dashboard by program and project, so that I can analyze specific organizational contexts. | Highest | 3 | 1 |
| US08 | Main Dashboard | As a manager, I want to view the consolidated total cost, so that I can quickly understand the total value associated with the analyzed projects. | Highest | 2 | 1 |
| US09 | Main Dashboard | As a manager, I want to view the total cost by program, so that I can compare programs from a consolidated cost perspective. | High | 2 | 1 |
| US10 | Main Dashboard | As a manager, I want to view the total cost by project, so that I can identify the projects with the greatest financial impact. | High | 2 | 1 |
| US11 | Main Dashboard | As a manager, I want to view cost evolution over time, so that I can identify trends, variations, and historical behavior. | High | 3 | 1 |
| US12 | Main Dashboard | As a manager, I want to view the cost composition between materials and technical hours, so that I can understand the weight of each component in the total cost. | Medium | 2 | 2 |
| US13 | Main Dashboard | As a manager, I want to view the materials with the highest financial impact, so that I can identify critical cost items. | Medium | 2 | 2 |
| US14 | Main Dashboard | As a manager, I want to view the projects with the highest cost, so that I can prioritize managerial attention on the most relevant projects. | Medium | 2 | 2 |
| US15 | Main Dashboard | As an analyst, I want to view a summary table in the dashboard, so that I can validate and compare the values shown in the charts. | Medium | 3 | 2 |
| US16 | Materials | As an analyst, I want to view the base structure of the materials analytics screen, so that I can access an organized view of material cost and consumption. | High | 2 | 1 |
| US17 | Materials | As an analyst, I want to view material indicators and the analytical table, so that I can monitor material cost and consumption by project. | High | 3 | 1 |
| US18 | Materials | As an analyst, I want to filter material analysis by item, supplier, and category, so that I can refine the investigation of cost and consumption from different perspectives. | Medium | 2 | 2 |
| US19 | Materials | As a manager, I want to view material cost by project, so that I can understand the financial impact of materials in each project. | Medium | 3 | 2 |
| US20 | Materials | As an analyst, I want to view material consumption over time, so that I can identify increases, reductions, and seasonality in material usage. | Medium | 3 | 3 |
| US21 | Technical Hours | As an analyst, I want to view the base structure of the technical hours screen, so that I can access an organized view of effort and labor cost by project. | Medium | 2 | 2 |
| US22 | Technical Hours | As an analyst, I want to view indicators and a table in the technical hours analysis screen, so that I can monitor cost and effort by project. | Medium | 3 | 2 |
| US23 | Technical Hours | As an analyst, I want to filter technical hours analysis by employee, role, and task, so that I can refine the investigation of technical effort from different perspectives. | Medium | 2 | 2 |
| US24 | Technical Hours | As a manager, I want to view hours by project, so that I can identify where the greatest technical effort is allocated. | Medium | 3 | 3 |
| US25 | Technical Hours | As a manager, I want to view hourly cost by employee or role, so that I can analyze where labor cost is concentrated. | Low | 3 | 3 |
| US26 | Technical Hours | As an analyst, I want to view the time evolution of hours, so that I can analyze the pace of execution over time. | Low | 3 | 3 |
| US27 | Consolidated View | As a manager, I want to view a consolidated cost screen, so that I can compare materials and technical hours in a single view by project and program. | Medium | 5 | 2 |
| US28 | Export | As a user, I want to export analytical data to CSV, so that I can perform complementary analysis outside the system. | Low | 2 | 3 |
| US29 | Export | As a user, I want to export analytical data to Excel, so that I can share and manipulate results in a corporate format. | Low | 2 | 3 |
| US30 | Data Traceability | As an administrator, I want to view the source of consolidated data, so that I can audit which source system and record originated the analytical values. | Low | 3 | 3 |
| US31 | Data Traceability | As an administrator, I want to identify data update or integration failures, so that I can act quickly when analytical data becomes inconsistent. | Low | 3 | 3 |
| US32 | Data Traceability | As a user, I want to view the date of the latest data update, so that I know whether the information shown is up to date. | Medium | 1 | 2 |
| US33 | Audit / Loads | As an administrator, I want to view data load history, so that I can monitor the reliability and freshness of the analytical environment. | Low | 3 | 3 |
| US34 | Audit / Loads | As an administrator, I want to view details of load failures, so that I can diagnose update and import problems. | Low | 3 | 3 |
| US35 | Audit / Loads | As an administrator, I want to view the access audit trail, so that I can track who used the application and when. | Low | 3 | 3 |
| US36 | Budget and Financial Health | As a manager, I want to view budget by program and project, so that I can compare planned values with actual costs. | High | 3 | 2 |
| US37 | Budget and Financial Health | As a manager, I want to view the percentage deviation of projects, so that I can understand budget consumption relative to the estimated budget. | High | 3 | 2 |
| US38 | Budget and Financial Health | As a manager, I want to view the financial health status of projects, so that I can identify which projects are healthy, under attention, or critical. | High | 3 | 2 |
| US39 | Budget and Financial Health | As a manager, I want to view projected budget overrun, so that I can anticipate financial risks and prioritize corrective actions. | Medium | 2 | 3 |
| US40 | Data Import | As an analytical system, I want to receive data through CSV files provided by the client, so that the initial load and data preparation can be performed without depending on API integration. | High | 1 | 2 |

## Delivery Schedule

| Phase | Start | Delivery | Documentation |
|---|---|---|---|
| General kick-off | 2026-03-02 | 2026-03-06 | - |
| Planning and initial backlog | 2026-03-09 | 2026-03-13 | - |
| Sprint 1 | 2026-03-16 | 2026-04-05 | [Sprint 1](docs/sprints/sprint-1.md) |
| Sprint Review / Planning | 2026-04-06 | 2026-04-10 | - |
| Sprint 2 | 2026-04-13 | 2026-05-03 | [Sprint 2](docs/sprints/sprint-2.md) |
| Sprint Review / Planning | 2026-05-04 | 2026-05-08 | - |
| Sprint 3 | 2026-05-11 | 2026-05-31 | -
| Sprint Review / Planning | 2026-06-01 | 2026-06-05 | - |
| Solutions Fair | 2026-06-11 | 2026-06-11 | - |

## Documentation

### Database
- [Database Model](docs/database/README.md)

### Sprints
- [Sprint 1](docs/sprints/sprint-1.md)
- [Sprint 2](docs/sprints/sprint-2.md)
<!--- [Sprint 3](docs/sprints/sprint-3.md)-->

### Technical and Process
<!--- [Installation Guide](docs/manuals/installation-guide.md)
- [User Guide](docs/manuals/user-guide.md)-->
- [Version Control and Branching Strategy](docs/process/branch-strategy.md)
- [Continuous Integration Strategy](docs/process/continuous-integration-strategy.md)
- [Commit Standard](docs/process/commit-standard.md)

## Definition of Ready (DoR) and Definition of Done (DoD)

In order to standardize the team's workflow, general criteria were established to define when a task is ready to enter the backlog, ready for development, and considered completed.

These are the **broad project-level criteria**.  
Specific user-story-level DoR and DoD should be documented in each sprint file.

### Definition of Ready (Backlog)
A task is considered ready to enter the backlog when:

- it has a clear description, prepared by the Product Owner, with well-defined acceptance criteria;
- it is properly prioritized and has an estimated level of complexity;
- its objective, business value, and impact are clearly defined and aligned with the stakeholder(s).

### Definition of Ready (Development)
A task is considered ready to begin development when:

- it has a design (wireframe or visual reference) reviewed and approved by the team;
- it has documented, clear, and accessible business rules;
- it has no dependencies or blockers preventing the start of implementation.

### Definition of Done
A task is considered done when:

- all acceptance criteria have been met;
- unit tests and integration tests have been implemented and are passing;
- the code has gone through code review, when applicable;
- the merge has been completed and the feature has been tested in the testing/homologation branch;
- there are no critical errors, known failures, or inconsistent behaviors.

## Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,django,postgres,vue,ts,docker,git,github,githubactions,figma,vscode&theme=light" />
  </a>
</p>

## Contributors

Name | Role | Networking | Profile
--- | --- | --- | ---
Alexander Silva | Dev Team | <a href="https://github.com/ahlesk"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/alexander-silva-lima-96a0432a6"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/ahlesk.png" width="60"> |
Carlos Daniel | Scrum Master | <a href="https://github.com/darloscaniel"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/carlos-daniel-9516952b4"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/darloscaniel.png" width="60"> |
Felipe Reis | Dev Team | <a href="https://github.com/felpzreiz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/felipe-reiss/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/felpzreiz.png" width="60"> |
Isabelly Sousa | Dev Team | <a href="https://github.com/61isabelly"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/isabelly-sousa"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/61isabelly.png" width="60"> |
Luiz Henrique | Product Owner | <a href="https://github.com/LuizHRFerreira"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/luiz-henrique-rabello-ferreira-3600752ba"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/LuizHRFerreira.png" width="60"> |
Mariana Oliveira | Dev Team | <a href="https://github.com/mariinetic"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/oliveirasmari/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/mariinetic.png" width="60"> |
Rafaella Cruz | Dev Team | <a href="https://github.com/arafaellacruz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/rafaella-cruz"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/arafaellacruz.png" width="60"> |
Samuel Prado | Dev Team | <a href="https://github.com/Samuelprado99"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/samuel-prado-9142381b6"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/Samuelprado99.png" width="60"> |

<div align="center">
<img src="assets/footer.png" alt="footer" width="100%" />
</div>