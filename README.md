# AGRIPM_MVP
Project management made simple for agriculture

# AgriPM

**Project management made simple for agriculture.**

AgriPM is a mobile-first platform that helps farmers plan, manage, and track agricultural projects from start to finish, without needing any formal project management training.

## The Problem

Most farmers know how to farm, but very few know how to *manage* a farm project. Without a system, they overspend, miss key activities, and often cannot tell whether a project is succeeding or failing. Tools like Trello and Asana were built for office teams, use unfamiliar language, and assume reliable internet access.

## Our Solution

AgriPM takes standard project management principles and wraps them in plain farming language that works on a basic smartphone and a slow connection.

**Core user journey:** Create → Plan → Execute → Monitor → Complete → Evaluate

## MVP Features

| Module | What it does |
|---|---|
| 1. Project Creation & Planning | Create a project with name, crop type, farm size, dates, budget, and objectives. Optionally start from a pre-built crop template (e.g. Maize, Cassava). |
| 2. Task & Schedule Management | Break a project into tasks, set deadlines, track status (To Do, In Progress, Completed), and see which tasks are delayed. |
| 3. Budget & Expense Tracking | Set a planned budget, record expenses, and see the remaining balance and whether the project is On Track or Over Budget. |
| 4. Risk Management Log | Log risks (such as pests or weather), rate their severity, and record how to address them. |
| 5. Project Control Dashboard | A single-screen view of progress, budget, and risks, with links to Tasks, Expenses, and Risks. |

A web-based **admin panel** (registered users and basic usage stats) shares the same backend and API as the mobile app, with access separated by role.

## Target Users

- Small and medium-scale farmers running or planning a farm project
- Farm managers overseeing day-to-day operations
- Young and emerging Farmer CEOs

## Out of Scope for the MVP

AI assistant, weather integration, market prices and supplier marketplace, farmer-to-farmer collaboration, lending and payment integration, advanced analytics, multi-user farm collaboration, and full offline mode. These are logged in the post-MVP backlog.

## Design Principles

- Mobile-first, lightweight, and usable on basic Android devices
- Works on slow 2G/3G connections (an internet connection is required in the MVP)
- Plain farming language, with no project management jargon
- Simple enough to use without training

## Project Workstreams

Work in this repository is tracked through GitHub Issues and organized with the following labels:

| Label | Focus |
|---|---|
| `team: research` | Farmer interviews, pilot recruitment, user feedback |
| `team: design` | Wireframes, UI/UX, crop templates |
| `team: development` | Backend, frontend, database, API |
| `team: qa` | Testing and bug fixes |
| `team: documentation` | Guides, charter, requirements |
| `team: project-management` | Scope, schedule, risks, change control |

Progress is managed on the project board with these stages: **Backlog, To Do, In Progress, Review, Done**.

## Delivery Plan

| Week | Focus |
|---|---|
| 1 | Discovery and design start: farmer interviews, workflow mapping, crop templates, wireframes |
| 2 | Design complete, database schema and API architecture finalized, development begins |
| 3 | Build part 1: authentication, project creation, tasks |
| 4 | Build part 2: budget, risks, dashboard, integration testing |
| 5 | Stabilization, farmer pilot (10 to 15 farmers), critical fixes, MVP launch |

## Success Measures

- 100 to 300 registered users within three months of launch
- At least 50 users managing a live project
- 10 to 15 farmers complete the pilot
- All five modules pass functional testing before launch
- Most pilot farmers report that the app makes project management easier

## Documentation

Project documents are stored in the [`docs/`](docs/) folder:

- Product Requirements Document (PRD)
- Project Charter

## Team (Group I)

| Name | Role |
|---|---|
| Kesiena Epia | Project Coordinator |
| Lilian Obijekwu | Risk & Quality Lead |
| Gold Offordile | Planning & Delivery Lead |
| Oyebanji Joseph Toluwanimi | Documentation & Research Lead |

