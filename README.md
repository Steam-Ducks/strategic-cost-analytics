<div align="center">
<img src="assets/header.png" alt="SCARS project header" width="100%" />
</div>

<span id="about"></span>

## 📍 Introduction

This project was developed by **STEAM DUCKS**, a team of students from the 5th semester of the **Database program at FATEC São José dos Campos**.

The proposal is to build **SCARS**, an analytical solution for consolidating and visualizing strategic project costs, developed in partnership with **SIATT**.

The acronym **SCARS** comes from the original Portuguese project name, **Sistema de Controle e Acompanhamento de Recursos Soberanos**.

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

<span id="team"></span>

## Contributors

Name | Role | Networking | Profile
--- | --- | --- | ---
Alexander Silva | Dev Team | <a href="https://github.com/alexttz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/alexander-silva-lima-96a0432a6"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/alexttz.png" width="60"> |
Carlos Daniel | Scrum Master | <a href="https://github.com/darloscaniel"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/carlos-daniel-9516952b4"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/darloscaniel.png" width="60"> |
Felipe Reis | Dev Team | <a href="https://github.com/felpzreiz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/felipe-reiss/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/felpzreiz.png" width="60"> |
Isabelly Sousa | Dev Team | <a href="https://github.com/61isabelly"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/isabelly-sousa"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/61isabelly.png" width="60"> |
Luiz Henrique | Product Owner | <a href="https://github.com/LuizHRFerreira"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/luiz-henrique-rabello-ferreira-3600752ba"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/LuizHRFerreira.png" width="60"> |
Mariana Oliveira | Dev Team | <a href="https://github.com/mariinetic"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/oliveirasmari/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/mariinetic.png" width="60"> |
Rafaella Cruz | Dev Team | <a href="https://github.com/arafaellacruz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/rafaella-cruz"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/arafaellacruz.png" width="60"> |
Samuel Prado | Dev Team | <a href="https://github.com/Samuelprado99"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/samuel-prado-9142381b6"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <img src="https://github.com/Samuelprado99.png" width="60"> |

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

<span id="backlog"></span>

## Product Backlog 🔍

| Rank | Priority | User Story | Story Points | Sprint |
|---|---|---|---:|---:|
| 1 | Highest | US04 — View the main dashboard base structure | 2 | 1 |
| 2 | Highest | US05 — View the main dashboard indicators | 3 | 1 |
| 3 | Highest | US06 — Filter dashboard by period | 2 | 1 |
| 4 | Highest | US07 — Filter dashboard by program and project | 3 | 1 |
| 5 | Highest | US08 — View consolidated total cost | 2 | 1 |
| 6 | High | US09 — View total cost by program | 2 | 1 |
| 7 | High | US10 — View total cost by project | 2 | 1 |
| 8 | High | US11 — View cost evolution over time | 3 | 1 |
| 9 | High | US16 — View the base structure of the materials analysis screen | 2 | 1 |
| 10 | High | US17 — View indicators and table for materials analysis | 3 | 1 |
| 11 | Medium | US12 — View cost composition between materials and labor hours | 2 | 2 |
| 12 | Medium | US13 — View materials with highest financial impact | 2 | 2 |
| 13 | Medium | US14 — View projects with highest cost | 2 | 2 |
| 14 | Medium | US15 — View dashboard summary table | 3 | 2 |
| 15 | Medium | US27 — View consolidated cost screen | 5 | 2 |
| 16 | Medium | US18 — Filter materials analysis by item, supplier, and category | 2 | 2 |
| 17 | Medium | US19 — View material cost by project | 3 | 2 |
| 18 | Medium | US21 — View the base structure of the technical labor screen | 2 | 2 |
| 19 | Medium | US22 — View indicators and table for technical labor analysis | 3 | 2 |
| 20 | Medium | US23 — Filter labor analysis by employee, role, and task | 2 | 2 |
| 21 | Medium | US32 — View the last data refresh timestamp | 1 | 2 |
| 22 | High | US36 — View budget by program and project | 3 | 2 |
| 23 | High | US37 — View percentage deviation by project | 3 | 2 |
| 24 | High | US38 — View project financial health | 3 | 2 |
| 25 | High | US40 — Import data through CSV files | 1 | 2 |
| 26 | Low | US01 — Authenticate into the system | 2 | 3 |
| 27 | Low | US02 — Access features according to user profile | 2 | 3 |
| 28 | Low | US03 — Manage system users | 3 | 3 |
| 29 | Low | US25 — View labor cost by employee or role | 3 | 3 |
| 30 | Low | US26 — View labor evolution over time | 3 | 3 |
| 31 | Low | US28 — Export analytical data to CSV | 2 | 3 |
| 32 | Low | US29 — Export analytical data to Excel | 2 | 3 |
| 33 | Low | US30 — View the origin of consolidated data | 3 | 3 |
| 34 | Low | US31 — Identify data update or integration failures | 3 | 3 |
| 35 | Low | US33 — View data load history | 3 | 3 |
| 36 | Low | US34 — View detailed load failures | 3 | 3 |
| 37 | Low | US35 — View access audit trail | 3 | 3 |
| 38 | Medium | US20 — View material consumption over time | 3 | 3 |
| 39 | Medium | US24 — View labor hours by project | 3 | 3 |
| 40 | Medium | US39 — View projected budget overrun | 2 | 3 |

<span id="schedule"></span>

## Delivery Schedule 🗓️

Phase | Start | Delivery
--- | --- | ---
General kick-off | 2026-03-02 | 2026-03-06
Planning and initial backlog | 2026-03-09 | 2026-03-13
Sprint 1 | 2026-03-16 | 2026-04-05
Sprint Review / Planning | 2026-04-06 | 2026-04-10
Sprint 2 | 2026-04-13 | 2026-05-03
Sprint Review / Planning | 2026-05-04 | 2026-05-08
Sprint 3 | 2026-05-11 | 2026-05-31
Sprint Review / Planning | 2026-06-01 | 2026-06-05
Solutions Fair | 2026-06-11 | 2026-06-11

## Sprint Summary 📋

<details>
<summary>Kick-off</summary>

**Project:** SCARS — Sovereign Resource Control and Autonomy System.

**Partner:** SIATT.

**Challenge**

Data related to materials, purchasing, inventory, project activities, and technical labor are currently fragmented across different sources, which makes consolidated historical analysis difficult.

The absence of a structured analytical environment reduces visibility into the real cost of strategic projects and programs, increases manual effort, and raises the risk of inconsistencies.

**Project Goal**

Design and implement a Data Warehouse capable of consolidating strategic cost data and supporting analytical exploration by time, program, project, material, employee, and financial indicators.

**Initial Engineering Standards and Technologies**

- PostgreSQL as the main database;
- Star and snowflake dimensional modeling;
- Python and Django for backend services and data processing;
- Vue.js with TypeScript for frontend development;
- ETL/ELT strategy with staging area;
- Automated testing, GitHub Actions CI, and static code analysis.

</details>

<details>
<summary>Sprint 1</summary>

**Period:** 2026-03-16 to 2026-04-05.

**Sprint Goal:** Deliver the solution foundation and the first version of the analytical dashboard for stakeholder validation.

**Planned User Stories**
- US04 — View the main dashboard base structure
- US05 — View the main dashboard indicators
- US06 — Filter dashboard by period
- US07 — Filter dashboard by program and project
- US08 — View consolidated total cost
- US09 — View total cost by program
- US10 — View total cost by project
- US11 — View cost evolution over time
- US16 — View the base structure of the materials analysis screen
- US17 — View indicators and table for materials analysis

**Completed Deliveries**
- _To be filled at the end of the sprint._

**Challenges and Obstacles**
- _To be filled at the end of the sprint._

**Lessons Learned**
- _To be filled at the end of the sprint._

**Evidence**
- _Add screenshots, links, or images at the end of the sprint._

![Sprint 1 Evidence](docs/evidence/sprint-1/screenshot-1.png)

</details>

<details>
<summary>Sprint 2</summary>

**Period:** 2026-04-13 to 2026-05-03.

**Sprint Goal:** Expand the analytical environment with specialized views, financial monitoring, and CSV-based ingestion.

**Planned User Stories**
- US12 — View cost composition between materials and labor hours
- US13 — View materials with highest financial impact
- US14 — View projects with highest cost
- US15 — View dashboard summary table
- US27 — View consolidated cost screen
- US18 — Filter materials analysis by item, supplier, and category
- US19 — View material cost by project
- US21 — View the base structure of the technical labor screen
- US22 — View indicators and table for technical labor analysis
- US23 — Filter labor analysis by employee, role, and task
- US32 — View the last data refresh timestamp
- US36 — View budget by program and project
- US37 — View percentage deviation by project
- US38 — View project financial health
- US40 — Import data through CSV files

**Completed Deliveries**
- _To be filled at the end of the sprint._

**Challenges and Obstacles**
- _To be filled at the end of the sprint._

**Lessons Learned**
- _To be filled at the end of the sprint._

**Evidence**
- _Add screenshots, links, or images at the end of the sprint._

![Sprint 2 Evidence](docs/evidence/sprint-2/screenshot-1.png)

</details>

<details>
<summary>Sprint 3</summary>

**Period:** 2026-05-11 to 2026-05-31.

**Sprint Goal:** Complete governance, export, traceability, and remaining analytical features.

**Planned User Stories**
- US01 — Authenticate into the system
- US02 — Access features according to user profile
- US03 — Manage system users
- US25 — View labor cost by employee or role
- US26 — View labor evolution over time
- US28 — Export analytical data to CSV
- US29 — Export analytical data to Excel
- US30 — View the origin of consolidated data
- US31 — Identify data update or integration failures
- US33 — View data load history
- US34 — View detailed load failures
- US35 — View access audit trail
- US20 — View material consumption over time
- US24 — View labor hours by project
- US39 — View projected budget overrun

**Completed Deliveries**
- _To be filled at the end of the sprint._

**Challenges and Obstacles**
- _To be filled at the end of the sprint._

**Lessons Learned**
- _To be filled at the end of the sprint._

**Evidence**
- _Add screenshots, links, or images at the end of the sprint._

![Sprint 3 Evidence](docs/evidence/sprint-3/screenshot-1.png)

</details>

## Burndown 🔥

![Sprint 1 Burndown](docs/burndown/sprint-1.png)
![Sprint 2 Burndown](docs/burndown/sprint-2.png)
![Sprint 3 Burndown](docs/burndown/sprint-3.png)

## SonarCloud / Quality Reports 📑

![Sprint 1 SonarCloud](docs/tests/sonarcloud/sprint-1.png)
![Sprint 2 SonarCloud](docs/tests/sonarcloud/sprint-2.png)
![Sprint 3 SonarCloud](docs/tests/sonarcloud/sprint-3.png)

## Documentation 📁

- [Product Backlog](docs/backlog/product-backlog.md)
- [Sprint 1 Backlog](docs/backlog/sprint-1-backlog.md)
- [Sprint 2 Backlog](docs/backlog/sprint-2-backlog.md)
- [Sprint 3 Backlog](docs/backlog/sprint-3-backlog.md)
- [Installation Guide](docs/manuals/installation-guide.md)
- [User Guide](docs/manuals/user-guide.md)
- [Version Control and Branching Strategy](docs/process/branch-strategy.md)
- [Continuous Integration Strategy](docs/process/continuous-integration-strategy.md)
- [Commit Standard](docs/process/commit-standard.md)

## 💻 Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,django,postgres,vue,ts,docker,git,github,githubactions,figma,vscode&theme=light" />
  </a>
</p>

<div align="center">
<img src="assets/footer.png" alt="footer" width="100%" />
</div>
