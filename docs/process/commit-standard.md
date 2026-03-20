# Commit Standard

## 1. Purpose

This document defines the commit message standard adopted by the **SCARS** project team.

The goal of this standard is to keep the repository history clear, consistent, and easy to trace across feature development and DevOps-related changes.

## 2. Commit Message Format

All commit messages must follow this structure:

```text
feat(<scope>): <short description>
```

## 3. Accepted Scopes

The project adopts two main commit scopes.

### 3.1 Feature Development

For commits related to backlog items, user stories, and feature implementation, the team must use the corresponding project identifier in the following format:

```text
feat(sca-**): <short description>
```

Example:

```text
feat(sca-12): add main dashboard filters
```

### 3.2 DevOps and Infrastructure

For commits related to DevOps, infrastructure, CI/CD, workflows, automation, or repository configuration, the team must use the following format:

```text
feat(devops): <short description>
```

Example:

```text
feat(devops): add continuous integration workflow
```

## 4. Writing Guidelines

To keep commit messages consistent, the team should follow these rules:

- Use clear and objective descriptions
- Write the description in English
- Keep the message short and directly related to the implemented change
- Use `sca-**` only for commits related to backlog items or project features
- Use `devops` only for commits related to automation, infrastructure, pipelines, or repository configuration

## 5. Examples

### Feature Commits

```text
feat(sca-04): add main dashboard base structure
feat(sca-06): implement dashboard period filter
feat(sca-16): create materials analysis screen
feat(sca-40): add csv import validation
```

### DevOps Commits

```text
feat(devops): add continuous integration workflow
feat(devops): configure backend test pipeline
feat(devops): update deployment automation
feat(devops): add repository hook validation
```

## 6. Notes

For consistency across the repository, all contributors must follow the examples and scope rules described in this document.