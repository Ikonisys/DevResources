
# Dev Resources

## Welcome to Our Development Hub

This repository is your go-to source for all development-related guidelines and best practices. Designed to support our team in maintaining high-quality code and efficient collaboration, here you'll find everything from code review templates to commit and branching strategies.

## Table of Contents

- [Introduction](#introduction)
  - [Purpose](#purpose)
  - [Scope](#scope)
- [Commit Style Guide](#commit-style-guide)
  - [Commit Message Structure](#commit-message-structure)
  - [Examples](#examples)
- [Branch Naming Conventions](#branch-naming-conventions)
  - [Branch Types](#branch-types)
  - [Naming Structure](#naming-structure)
- [Development Practices](#development-practices)
- [Contributing](#contributing)
- [Resources](#resources)

## Introduction

### Purpose

The purpose of the Dev Resources repository is to centralize and standardize the development practices, guidelines, and resources for our project. This repository serves as a foundation for maintaining code quality, enhancing collaboration, and ensuring consistency across the development lifecycle.

### Scope

The scope of the Dev Resources repository encompasses:

-   **Commit Style Guide**: Conventions for writing clear and informative commit messages that facilitate understanding and tracking of project history.
-   **Branch Naming Conventions**: Strategies for naming branches in a way that reflects their purpose and facilitates organization within the repository.
-   **Development Practices**: Best practices for development workflows, including coding standards, testing guidelines, and workflow strategies.
-   **Contributing Guidelines**: Instructions for team members on how to contribute to the repository, propose changes, and submit resources.
-   **Additional Resources**: A curated list of external guides, tools, and recommended resources that support development practices and project goals.

## Commit Style Guide

### Commit message structure

A well-structured commit message consists of three distinct parts separated by a blank line: the title, an optional body, and an optional footer. The layout looks like this:

**type(scope): subject**
**body**
**footer**

Type: Specifies the type of change being made. Common types include feat (new feature), fix (bug fix), docs (documentation changes), style (formatting, missing semi colons, etc.), refactor (code change that neither fixes a bug nor adds a feature), test (adding missing tests), and chore (maintenance tasks).
Scope: An optional element that specifies the context of the commit. It could be the module or component affected by the changes.
Subject: A concise description of the changes. Use imperative, present tense: "change" not "changed" nor "changes".
Body: A detailed description of the changes being made. Include the motivation for the change and contrast this with previous behavior.
Footer: Optional. Used to reference issue tracker IDs or any notable changes in behavior or backward-incompatible changes.

### Examples

feat(authentication): implement JWT authentication
fix(server): resolve memory leak in image processing
docs(readme): update installation instructions

**Commit Message Guidelines**

Keep the subject line under 50 characters if possible.
Do not end the subject line with a period.
By adhering to these guidelines, we ensure our project's commit history is readable and informative, facilitating effective team collaboration and project management.

## Branch Naming Conventions

Branch naming conventions are crucial for maintaining an organized and efficient workflow in a collaborative development environment. They help in categorizing branches by purpose, making them easily identifiable, and facilitating automated processes like continuous integration. Below are the guidelines for naming branches within our project:

#### branch types:

1.  **Feature Branches (`feature/`)**: For new features or enhancements. Prefix with `feature/` followed by a brief descriptor of the feature. Example: `feature/add-login`.
    
2.  **Bugfix Branches (`bugfix/`)**: For fixing bugs. Start with `bugfix/`, then a concise description of the fix. Example: `bugfix/login-error`.
    
3.  **Hotfix Branches (`hotfix/`)**: For critical fixes that need immediate deployment. Use `hotfix/` followed by the issue it addresses. Example: `hotfix/urgent-login-fix`.
    
4.  **Release Branches (`release/`)**: For preparing releases. Prefix with `release/` and the version number. Example: `release/1.0.0`.
    
5.  **Development Branches (`dev/`)**: For ongoing development work, experiments, or large refactoring's not yet ready for production. Start with `dev/`, followed by a descriptive name. Example: `dev/refactor-authentication`.
    

#### Naming Structure:

-   **Use Lowercase**: Always use lowercase to avoid confusion with case-sensitive systems.
-   **Use Slashes for Categories**: Use slashes to separate categories (e.g., `feature/`, `bugfix/`) from the descriptor.
-   **Be Concise and Descriptive**: Keep names short but descriptive enough to convey the branch's purpose at a glance.
-   **Use Dashes to Separate Words**: Use dashes instead of underscores or spaces for readability. Example: `feature/add-user-profile`.
-   **Include Issue Numbers**: When applicable, include the issue or ticket number at the end. Example: `feature/add-login-#123`.

## Development Practices

Share best practices for development workflows, including any project-specific conventions or strategies for maintaining code quality will be added **here**.

## Contributing

Guidelines for team members on how to contribute to the Dev Resources repository, including how to propose changes or add new resources. add them **here**.

## Resources

A curated list of external guides, tools, and resources that support our development practices and enhance our workflows. add them **here**.

---
