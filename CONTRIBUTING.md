# Contributing to backstage-templates

Thank you for considering a contribution to backstage-templates! This guide outlines the process to help get your contribution accepted and merged smoothly.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [Where to Start?](#where-to-start)
- [Setting up Development Environment](#setting-up-development-environment)
- [Making Changes](#making-changes)
- [Coding Guidelines](#coding-guidelines)
- [Submitting a Pull Request](#submitting-a-pull-request)

## Code of Conduct
By participating in this project, you are expected to uphold our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Where to Start?

- **Bug Fixes**: If you've found a bug, first check if it has already been reported. If it hasn't, [open a new issue](https://github.com/your-username/backstage-templates/issues).
- **Features**: If there's a new feature that you want to add, [open a new issue](https://github.com/your-username/backstage-templates/issues) to discuss what you would like to achieve.

## Setting up Development Environment

1. Fork the repository.
2. Clone your fork:
   ```bash
   git clone https://github.com/your-username/backstage-templates.git
    ```
3. Add the main repository as an upstream remote:
    ```bash
    git remote add upstream https://github.com/original-owner/backstage-templates.git
    ```
## Making Changes

1. Create a new branch with a descriptive name:
    ```bash
    git checkout -b my-feature-or-bugfix
    ```
2. Make and commit your changes.
3. Before pushing, rebase your commits against the main branch:
    ```bash
    git fetch upstream
    git rebase upstream/main
    ```

## Coding Guidelines

- Write clean and readable code.
- Make sure to add comments to explain complex or nuanced sections.
- Follow the existing style of the codebase.

## Submitting a Pull Request

1. Push your changes to your fork:
    ```bash
    git push origin my-feature-or-bugfix
    ```
2. Open a pull request against the main branch.
3. In the pull request, describe the changes you've made, any challenges you faced, and any additional context.
4. Wait for a review. Address any comments or feedback provided.

Thank you for your contribution!