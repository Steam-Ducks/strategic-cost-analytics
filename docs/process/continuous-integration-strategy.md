# Continuous Integration and Release Documentation

## 1. Purpose

The purpose of this Continuous Integration (CI) strategy is to maintain long-term code quality, ensure system stability, and automate the delivery process across both the back-end and front-end modules. The CI pipelines are designed to validate every change before it is merged, enforce coding standards, execute automated tests, and ensure that only stable code reaches the main branches.

## 2. CI Architecture Overview

The project uses a structured CI architecture composed of multiple workflows designed to cover the full software lifecycle. This includes pull request validation, automatic merges, scheduled sprint releases, code quality analysis, and submodule synchronization between repositories. Each workflow has a specific responsibility and contributes to consistency, reliability, and automation.

## 3. Pull Request Validation – Back-End

Every pull request targeting the `develop` branch automatically triggers the back-end CI workflow. This workflow ensures that the Python code follows the project's coding standards and that all automated tests pass before the code is merged.

### Back-End CI Steps

The back-end CI workflow includes the following steps:

- Code linting using Ruff
- Code formatting validation using Black
- Python 3.12 environment setup
- Installation of dependencies using `pip`
- Database initialization using PostgreSQL
- Execution of migrations
- Execution of automated tests using `pytest`
- Code coverage generation
- Coverage artifact upload

## 4. Pull Request Validation – Front-End

Every pull request targeting the `develop` branch also triggers the front-end CI workflow. This workflow ensures code quality, type safety, and application stability before the code is merged.

### Front-End CI Steps

The front-end CI workflow includes:

- Node.js 20 environment setup
- Dependency installation using `npm ci`
- Lint validation using ESLint
- TypeScript type checking
- Unit tests with coverage
- End-to-end tests using Playwright
- Full application build validation
- Upload of test and Playwright reports

## 5. Automatic Merge Process

If all CI validations succeed, the pull request is automatically merged into the `develop` branch. This ensures that only validated and stable code becomes part of the main development branch. The merge method used is **squash merge**, which keeps the repository history clean and easier to maintain.

## 6. Scheduled Release Process – Front-End

The project uses scheduled releases aligned with sprint deliveries for the front-end application. Instead of manually merging code into production, the workflow automatically validates the code and merges `develop` into `main` on predefined dates.

### Front-End Release Validation

Before the merge occurs, the workflow executes:

- Lint validation
- Type checking
- Unit tests with coverage
- End-to-end tests using Playwright
- Application build validation
- SonarCloud code quality analysis

## 7. Scheduled Release Process – Back-End

The back-end also has a scheduled release workflow. This workflow ensures that the Python application is fully validated before it reaches the production branch.

### Back-End Release Validation

The workflow validates:

- Code linting using Ruff
- Formatting validation using Black
- Automated tests using `pytest`
- PostgreSQL database execution
- Coverage report generation
- SonarCloud analysis

## 8. SonarCloud Integration

SonarCloud is used as part of the release pipeline to ensure long-term code quality. The analysis includes code smell detection, duplication validation, test coverage evaluation, security vulnerability detection, and maintainability analysis.

## 9. Submodule Synchronization

The project uses independent repositories for the front-end and back-end. These repositories are integrated into a main repository using Git submodules. When a release is completed, the child repositories automatically notify the main repository, which updates the corresponding submodules.

## 10. Automated Notification Process

Whenever the `main` branch of the front-end or back-end repository is updated, a workflow sends an automatic notification to the parent repository. The parent repository receives this notification, updates the submodule, commits the change, and pushes the update automatically.

## 11. Benefits of This CI Strategy

This CI architecture provides several important benefits:

- High code quality
- Automated validation of every change
- Stable releases
- Predictable sprint deliveries
- Reduced manual work
- Faster development cycle
- Long-term maintainability

## 12. Development Workflow Summary

The development workflow follows these steps:

1. A developer creates a feature branch.
2. A pull request is opened targeting `develop`.
3. CI pipelines are automatically executed.
4. If all validations succeed, the pull request is automatically merged.
5. At the end of the sprint, scheduled release workflows merge `develop` into `main`.
6. The main repository updates its submodules automatically.
