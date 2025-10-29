---
title: "Project Standard Operating Procedure (SOP)"
date: 2025-10-29
draft: false
---

## Introduction

This document outlines the Standard Operating Procedures (SOP) for software development in this project. Adhering to these procedures ensures consistency, quality, and efficiency in our development process.

## Version Control

*   **Repository:** All code is managed in a Git repository hosted on [Platform (e.g., GitHub, GitLab)].
*   **Commits:**
    *   Commit messages should be clear and concise, following the [Conventional Commits](https://www.conventionalcommits.org/) specification.
    *   Each commit should represent a single logical change.
    *   Atomic commits are preferred.

## Branching Strategy

We follow the [GitHub Flow](https://guides.github.com/introduction/flow/) branching model.

*   `main` branch is always deployable.
*   New work is done in feature branches, created from `main`.
*   Feature branches should have descriptive names (e.g., `feat/add-user-authentication`, `fix/resolve-login-bug`).
*   Pull requests are used to merge feature branches into `main`.

## Code Style and Linting

*   We use [Linter Name (e.g., ESLint, Ruff)] to enforce a consistent code style.
*   Code should be formatted according to the rules defined in the project's configuration file (e.g., `.eslintrc.js`, `pyproject.toml`).
*   Run the linter before committing your changes.

## Testing

*   Write unit tests for all new features and bug fixes.
*   Tests should be located in the `tests` directory.
*   Run all tests before submitting a pull request.

## Code Reviews

*   All code must be reviewed by at least one other team member before being merged into `main`.
*   The author of a pull request is responsible for addressing all comments and feedback from the reviewer.
*   Reviewers should provide constructive feedback.

## Issue Tracking

*   We use [Issue Tracker (e.g., GitHub Issues, Jira)] to track bugs, feature requests, and other tasks.
*   Each issue should have a clear title and a detailed description.
*   Assign issues to the appropriate team member.

## Deployment

*   The `main` branch is automatically deployed to the [Staging Environment] environment.
*   Production deployments are done manually after successful testing in the staging environment.
