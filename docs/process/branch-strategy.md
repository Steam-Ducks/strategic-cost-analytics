# Version Control and Branching Strategy

## 1. Purpose

This document defines the version control and branching strategy adopted by the **SCARS** project team. Its purpose is to ensure repository organization, support parallel feature development, and increase safety during code integration.

## 2. Adopted Strategy

The team adopts the **GitHub Flow** branching strategy.

This strategy was selected because it is simple, practical, and appropriate for the academic context of the project. It allows team members to develop features in parallel without compromising the stability of the main branch.

According to the GitHub Flow approach, the `main` branch must always represent the stable version of the project, while each feature, fix, or documentation change is developed in a separate branch. At the end of development, a **pull request** must be opened for review and later merge into the main branch.

## 3. Rationale for the Choice

The adoption of **GitHub Flow** was based on the following factors:

- Simplicity and ease of understanding for the entire team
- Good fit for the project team size
- Support for parallel task execution
- Encouragement of code review through pull requests
- Reduced risk of direct conflicts in the main branch
- Alignment with the GitHub guidelines adopted in the course

## 4. Main Branch

The main branch of the project is:

```bash
main
```

The `main` branch must always contain the most stable and integrated version of the project.

No team member should develop directly on `main`.

## 5. Branch Naming Pattern

Each feature, bug fix, documentation change, or technical refactoring must be developed in a dedicated branch.

### 5.1 Feature Branches

```bash
feature/feature-name
```

Examples:

```bash
feature/main-dashboard
feature/period-filter
feature/material-analysis
```

### 5.2 Bug Fix Branches

```bash
bugfix/fix-name
```

Example:

```bash
bugfix/project-filter-fix
```

### 5.3 Documentation Branches

```bash
docs/document-name
```

Examples:

```bash
docs/main-readme
docs/product-backlog
```

### 5.4 Refactoring Branches

```bash
refactor/refactor-name
```

Example:

```bash
refactor/dashboard-component-structure
```

## 6. Team Workflow

The development workflow defined for the project is the following:

1. The team defines the user story and sprint tasks
2. The responsible team member creates a branch from `main`
3. Development is carried out in the created branch
4. Commits must follow the convention defined by the team
5. Once the work is completed, the team member opens a **pull request**
6. The pull request may be reviewed by another team member, when applicable
7. After validation, the branch is merged into `main`
8. After the merge, the branch may be removed

## 7. Usage Rules

To ensure consistency across the repository, the team adopts the following rules:

- Direct commits to `main` are not allowed
- Every delivery must be linked to a user story, task, or other identifiable demand
- Branch names must be clear and standardized
- A pull request must be opened before merging into `main`
- Branches should be kept up to date with `main` when necessary
- Branches with multiple unrelated objectives should be avoided
- Completed branches should be removed to keep the repository organized

## 8. Use of Pull Requests

The team uses **pull requests** as the official integration mechanism between branches.

Whenever possible, each pull request should contain:

- A clear and objective title
- A reference to the related user story or task
- A brief description of what was implemented
- Relevant review notes, when necessary

The use of pull requests contributes to:

- Delivery traceability
- Review of changes before integration
- Historical record of implementations
- Greater adherence to the course evaluation criteria

## 9. Practical Workflow Example

The following example illustrates the development of a period filter feature:

1. Create the branch:

```bash
feature/period-filter
```

2. Develop the feature and create commits following the defined convention

3. Open a pull request from `feature/period-filter` to `main`

4. After validation, merge the branch into `main`
