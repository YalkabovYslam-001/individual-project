---
title: "Continuous Integration and Continuous Deployment (CI/CD)"

summary: "Using GitHub Actions for automatic building and deployment of a personal website."

date: 2026-08-23

authors:

  - me

tags:

  - CI/CD
  - GitHub Actions
  - GitHub Pages
  - Hugo
  - Git

---

# Continuous Integration and Continuous Deployment

## What is CI/CD

CI/CD is an approach to automating software development.

CI stands for Continuous Integration.

CD stands for Continuous Delivery or Continuous Deployment.

Using CI/CD makes it possible to automatically validate, build, and deploy a project after changes are made.

## GitHub Actions

GitHub Actions is used for automation in the individual project.

After changes are pushed to the GitHub repository, a workflow is triggered.

The workflow performs several operations:

1. gets the project's source code;
2. installs Hugo;
3. installs Node.js and dependencies;
4. builds the website;
5. creates the final website files;
6. uploads the build result;
7. deploys the website through GitHub Pages.

## Workflow

The website deployment process works as follows:

```text
Visual Studio Code

        ↓

      Git

        ↓

    GitHub

        ↓

GitHub Actions

        ↓

      Hugo

        ↓

     Build

        ↓

  GitHub Pages

        ↓

 Personal Website