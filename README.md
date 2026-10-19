# GitHub Pages Deployment using GitHub Actions

## Overview

This project demonstrates automated deployment of a static
website using GitHub Actions and GitHub Pages.

## Technology Stack

- Linux
- Git
- GitHub
- GitHub Actions
- YAML
- GitHub Pages

## CI/CD Workflow

1. Developer modifies index.html.
2. Developer pushes changes to the main branch.
3. GitHub Actions detects the change.
4. GitHub provisions an Ubuntu runner.
5. The workflow checks out the repository.
6. GitHub Actions uploads the website artifact.
7. GitHub Pages deploys the website.

## Trigger Conditions

Automatic deployment occurs only when index.html changes
on the main branch.

Manual deployment is available using workflow_dispatch.

## Learning Outcomes

- Git version control
- CI/CD workflow development
- GitHub Actions
- Static website deployment
- Deployment troubleshooting
