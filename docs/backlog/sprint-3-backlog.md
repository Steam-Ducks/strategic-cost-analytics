# Sprint 3

## Sprint

**Sprint 3**  
**Period:** 05/11/2026 to 05/31/2026

---

## Sprint Goal

Complete the solution with authentication, access control, export, traceability, and audit features, while expanding the analytical views for technical hours, material consumption over time, and projected budget overrun.

---

## Sprint Objective

Deliver the final version of the solution with user authentication and administration mechanisms, data export resources, traceability and audit features, and additional analytical views for technical hours, material consumption over time, and projected budget overrun.

---

## Demonstration Video

- Add Sprint 3 demo video link here

---

## User Stories

### US01 — As a user, I want to authenticate in the system, so that I can access the analytical environment securely.

#### Description
The system must allow user authentication through login and password, granting access according to the application rules.

#### Acceptance Criteria
- Display the login screen
- Validate username and password
- Allow access when credentials are valid
- Display an appropriate error message when authentication fails

#### Definition of Ready
- authentication rules are defined
- login flow is mapped

#### Definition of Done
- authentication is implemented
- access works correctly
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US02 — As an authenticated user, I want to access features according to my user type, so that I can use the application with the appropriate level of access.

#### Description
The system must support different user types and apply the corresponding access restrictions to the available features.

#### Acceptance Criteria
- Identify the user type during authentication
- Allow normal access according to user type
- Restrict exclusive features when applicable
- Prevent unauthorized direct access
- Display consistent behavior for unauthorized attempts

#### Definition of Ready
- user types are defined
- access rules are defined

#### Definition of Done
- access restrictions are implemented
- behavior is validated
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US03 — As an administrator, I want to manage system users, so that I can keep application access updated and centrally controlled.

#### Description
The system must provide an administrative screen to list, create, edit, and delete users, accessible only to administrators.

#### Acceptance Criteria
- Display access to user management only for administrators
- Prevent access by unauthorized users
- Display user listing
- Allow creating a new user
- Allow editing an existing user
- Allow deleting an existing user
- Prevent duplicate login creation
- Display success and validation messages appropriately

#### Definition of Ready
- required user fields are defined
- administrator-only rule is defined
- uniqueness rule is defined

#### Definition of Done
- user management is implemented
- access restriction is implemented
- listing is updated after operations
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US20 — As an analyst, I want to view material consumption over time, so that I can identify increases, reductions, and seasonality in material usage.

#### Description
The system must display the temporal evolution of material consumption and/or material cost by period.

#### Acceptance Criteria
- Display time series for material consumption or cost
- Allow analysis by period
- Respect applied filters
- Display periods in correct order
- Update the visualization according to the selected context

#### Definition of Ready
- temporal granularity is defined
- material cost/consumption rule is defined
- historical data is available

#### Definition of Done
- temporal visualization is implemented
- aggregations are correct
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US24 — As a manager, I want to view hours by project, so that I can identify where the greatest technical effort is allocated.

#### Description
The system must display a comparative visualization of the total worked hours by project.

#### Acceptance Criteria
- Display hours by project
- Respect applied filters
- Allow visual comparison between projects
- Display total hours correctly

#### Definition of Ready
- aggregation by project is defined
- hours data by project is available

#### Definition of Done
- visualization is implemented
- calculations are correct
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US25 — As a manager, I want to view hourly cost by employee or role, so that I can analyze where labor cost is concentrated.

#### Description
The system must display a comparative visualization of accumulated labor cost by employee or role.

#### Acceptance Criteria
- Display cost by employee or role
- Allow switching between employee and role when applicable
- Respect applied filters
- Display total values correctly

#### Definition of Ready
- aggregation rule is defined
- employee and role data are available

#### Definition of Done
- visualization is implemented
- calculations are correct
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US26 — As an analyst, I want to view the time evolution of hours, so that I can analyze the pace of execution over time.

#### Description
The system must display a time series with the sum of worked hours by period.

#### Acceptance Criteria
- Display hours evolution over time
- Respect applied filters
- Display periods in the correct order
- Display aggregated values correctly

#### Definition of Ready
- temporal granularity is defined
- historical hours data is available

#### Definition of Done
- temporal visualization is implemented
- aggregations are correct
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US28 — As a user, I want to export analytical data to CSV, so that I can perform complementary analysis outside the system.

#### Description
The system must allow export of visible analytical data to CSV, respecting active filters and selected columns when applicable.

#### Acceptance Criteria
- Allow CSV export
- Respect applied filters
- Respect selected columns when applicable
- Generate a standardized file name

#### Definition of Ready
- export rules are defined
- data source is available

#### Definition of Done
- CSV export is implemented
- filters are preserved
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US29 — As a user, I want to export analytical data to Excel, so that I can share and manipulate results in a corporate format.

#### Description
The system must allow export of analytical data to Excel, respecting active filters and selected columns when applicable.

#### Acceptance Criteria
- Allow Excel export
- Respect applied filters
- Respect selected columns when applicable
- Generate a standardized file name

#### Definition of Ready
- export rules are defined
- data source is available

#### Definition of Done
- Excel export is implemented
- filters are preserved
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US30 — As an administrator, I want to view the source of consolidated data, so that I can audit which source system and record originated the analytical values.

#### Description
The system must allow identification of the source of consolidated data, including source system, original identifier, and load timestamp.

#### Acceptance Criteria
- Display source system
- Display original source record identifier when applicable
- Display load date and time
- Make traceability available for audit consultation

#### Definition of Ready
- traceability metadata are defined
- source identifiers are known

#### Definition of Done
- traceability is implemented
- consultation is available
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US31 — As an administrator, I want to identify data update or integration failures, so that I can act quickly when analytical data becomes inconsistent.

#### Description
The system must signal relevant failures in data update or integration processes and allow their identification in the operational context.

#### Acceptance Criteria
- Display registered update or integration failures
- Allow identification of the related execution status
- Allow viewing minimum failure details
- Preserve failure history

#### Definition of Ready
- failure events are defined
- execution logs are available

#### Definition of Done
- failures are available for consultation
- details are implemented
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US33 — As an administrator, I want to view data load history, so that I can monitor the reliability and freshness of the analytical environment.

#### Description
The system must present data load executions with period, status, and processed volume.

#### Acceptance Criteria
- Display execution history
- Display execution status
- Display processed volume
- Allow filtering by period and status

#### Definition of Ready
- load logs are available
- visualization structure is defined

#### Definition of Done
- history view is implemented
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US34 — As an administrator, I want to view details of load failures, so that I can diagnose update and import problems.

#### Description
The system must allow opening failed load executions and displaying useful information for diagnosis.

#### Acceptance Criteria
- Display failed executions
- Allow opening execution details
- Display error message or failure reason when available
- Preserve execution history

#### Definition of Ready
- failure logging is available

#### Definition of Done
- detailed failure view is implemented
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US35 — As an administrator, I want to view the access audit trail, so that I can track who used the application and when.

#### Description
The system must record and display relevant authentication and access events.

#### Acceptance Criteria
- Register relevant access events
- Display the user associated with the event
- Display event date and time
- Allow consultation of the records

#### Definition of Ready
- audit events are defined
- log structure is available

#### Definition of Done
- auditing is implemented
- consultation is available
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

### US39 — As a manager, I want to view projected budget overrun, so that I can anticipate financial risks and prioritize corrective actions.

#### Description
The system must calculate and display projected budget overrun for projects when applicable, based on the difference between actual consolidated cost and estimated budget.

#### Acceptance Criteria
- Display projected overrun by project when applicable
- Respect applied filters
- Display values correctly formatted
- Allow analytical and/or tabular consultation

#### Definition of Ready
- overrun projection rule is defined
- actual cost and budget data are available

#### Definition of Done
- calculation is implemented
- visualization is implemented
- tests are approved

#### Tasks
| Task | Owner | Status |
|---|---|---|
| Add tasks here |  | To Do |

---

## Sprint User Stories Summary

| ID | Priority | Points | Status |
|----|----------|--------|--------|
| US01 | Low | 2 | Planned |
| US02 | Low | 2 | Planned |
| US03 | Low | 3 | Planned |
| US20 | Medium | 3 | Planned |
| US24 | Medium | 3 | Planned |
| US25 | Low | 3 | Planned |
| US26 | Low | 3 | Planned |
| US28 | Low | 2 | Planned |
| US29 | Low | 2 | Planned |
| US30 | Low | 3 | Planned |
| US31 | Low | 3 | Planned |
| US33 | Low | 3 | Planned |
| US34 | Low | 3 | Planned |
| US35 | Low | 3 | Planned |
| US39 | Medium | 2 | Planned |

**Total planned points:** 40

---

## Evidence

### Wireframes
- [Dashboard Wireframe](https://www.figma.com/make/v1S1QcC1TETZXjW7fsROmZ/Minimalist-Dashboard?p=f&t=rTUNyg9AzobuhCrQ-0&fullscreen=1&preview-route=%2Fdashboard)

### Screenshots
- Add screenshots from `../../assets/sprint-3/`

### Quality and Monitoring
- Add burndown from `../../assets/sprint-3/`
- Add SonarQube evidence from `../../assets/sprint-3/`

### Presentation
- Add Sprint 3 presentation link here

### Demo Video
- Add Sprint 3 demo video link here

---

## Sprint Status

**In planning**