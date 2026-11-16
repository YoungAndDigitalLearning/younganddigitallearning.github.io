<p align="center">
  <img src="https://raw.githubusercontent.com/YoungAndDigitalLearning/.github/refs/heads/main/images/branding/ydl-logo.svg" alt="Young & Digital Learning logo" width="260">
</p>
<h1 align="center">Young & Digital Learning — Interactive Demo</h1>

<p align="center">
  <!-- Workflow GitHub Actions - Deployment -->
  <a href="https://github.com/YoungAndDigitalLearning/younganddigitallearning.github.io/actions/workflows/deploy.yml">
    <img
      src="https://img.shields.io/github/actions/workflow/status/YoungAndDigitalLearning/younganddigitallearning.github.io/deploy.yml?branch=main&style=for-the-badge&logo=githubactions&label=Deployment"
      alt="GitHub Pages deployment workflow status"
    >
  </a>
  <!-- Workflow GitHub Actions - Deployment status -->
  <a href="https://github.com/YoungAndDigitalLearning/younganddigitallearning.github.io/deployments">
  <img
    src="https://img.shields.io/github/deployments/YoungAndDigitalLearning/younganddigitallearning.github.io/github-pages?style=for-the-badge&logo=githubpages&label=GitHub%20Pages"
    alt="GitHub Pages deployment status"
  >
  </a>
  </br>
  <!-- Website Online/Offline -->
  <a href="https://younganddigitallearning.github.io/">
    <img
      src="https://img.shields.io/website?url=https%3A%2F%2Fyounganddigitallearning.github.io%2F&style=for-the-badge&logo=githubpages&label=Website&up_message=online&down_message=offline&up_color=brightgreen&down_color=red"
      alt="Young and Digital Learning website availability"
    >
  </a>
  <!-- Website Uptime 7 days -->
  <a target="_blank" href="https://stats.uptimerobot.com/VNKWLhxGJn">
    <img alt="Uptime Robot ratio (7 days)" src="https://img.shields.io/uptimerobot/ratio/7/m784129797-7749dd35a60d2d59a8715daa.svg?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI1MTIiIGhlaWdodD0iNTEyIiB2aWV3Qm94PSIwIDAgNTEyIDUxMiI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxjaXJjbGUgY3g9IjI1NiIgY3k9IjI1NiIgcj0iMjU2IiBmaWxsPSIjMkE4QzAwIi8+CiAgICA8Y2lyY2xlIGN4PSIyNTYuNSIgY3k9IjI1Ni41IiByPSIxNDEuNSIgZmlsbD0iIzIwMjAxRiIgc3Ryb2tlPSIjRkZGRkZGIiBzdHJva2Utd2lkdGg9IjIwIi8+CiAgPC9nPgo8L3N2Zz4K">
  </a>
  </br>
  <a href="https://github.com/YoungAndDigitalLearning/younganddigitallearning.github.io/commits/main/">
    <img
      src="https://img.shields.io/github/last-commit/YoungAndDigitalLearning/younganddigitallearning.github.io?style=for-the-badge&logo=github&label=Last%20Commit"
      alt="Last commit to the GitHub Pages repository"
    >
  </a>
  </br>
  <!-- Vue.js -->
  <a href="https://github.com/YoungAndDigitalLearning/ydl-front">
    <img
      src="https://img.shields.io/badge/Vue.js-2.x-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white"
      alt="Vue.js 2 frontend"
    >
  </a>
  </br>
  <!-- GitHub License -->
  <a target="_blank" href="https://github.com/YoungAndDigitalLearning/ydl/blob/master/LICENSE">
    <img alt="GitHub License" src="https://img.shields.io/github/license/YoungAndDigitalLearning/ydl?style=for-the-badge">
  </a>
</p>

<p align="center">
  <a target="_blank" href="https://younganddigitallearning.github.io/">
    <strong>Launch Interactive Demo</strong>
  </a>
</p>

This repository hosts the public, interactive demonstration of **Young & Digital Learning**, an academic full-stack web application originally developed at **Technische Universität Berlin (TU Berlin)** in collaboration with the **Sprach- und Kulturbörse (SKB)**.

## About the Demo

The demo is based on the original **Vue 2 frontend**, restored and adapted for static hosting on GitHub Pages.

It allows visitors to explore the application from both student and teacher perspectives, including:

- Course discovery, enrollment, and management
- Course discussions and forum threads
- Interactive quizzes with immediate feedback
- Course calendars and learning resources
- Teacher interfaces for creating and editing course content

The demo runs entirely in the browser using **fictional sample data and a mock API**. No Django backend, database, or real user credentials are required.

Changes are stored locally in the browser and can be reverted using **Reset Demo**.

## Project Repositories

| Repository                                                         | Description                                                      |
| ------------------------------------------------------------------ | ---------------------------------------------------------------- |
| [ydl](https://github.com/YoungAndDigitalLearning/ydl)              | Main full-stack project, Docker setup, and screenshot automation |
| [ydl-front](https://github.com/YoungAndDigitalLearning/ydl-front)  | Original Vue.js frontend and static demo implementation          |
| [ydl-api](https://github.com/YoungAndDigitalLearning/ydl-api)      | Django REST Framework backend                                    |
| [Organization Profile](https://github.com/YoungAndDigitalLearning) | Project overview, architecture, and screenshots                  |

## Deployment

This repository contains the **generated static build** of the Vue application, published using GitHub Pages and GitHub Actions.

The frontend source code is maintained in [`ydl-front`](https://github.com/YoungAndDigitalLearning/ydl-front). The deployed files are build artifacts rather than a separate source-code fork.

---

_Young & Digital Learning is presented as an academic software engineering project and technical portfolio reference. All data in the public demo is fictional._
