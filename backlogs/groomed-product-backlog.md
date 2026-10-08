---
layout: default
title: Product Backlog
permalink: /backlogs/product-backlog/
---

# 📋 Product Backlog – *Insurance Risk Calculator*

| **ID** | **User Story / Task** | **Priority (1-10)** | **Estimate (SP)** | **Spike (Y/N)** | **Status** | **Assigned** |
|--------|------------------------|--------------|--------------|------------|--------------|--------------|
| RC-001 | As a Scrum Team, we want to identify our Sprint 4 Scrum Master and Product Owner and review Agile 101 from Agile Alliance so that we have clearly defined responsibilities and a shared understanding of Scrum for the sprint. | 10 | 1 | Y | Ready | -- |
| RC-002 | As a Product Owner, I want to groom and prioritize the Product Backlog around the Minimum Viable Product (MVP) so that the team delivers the most valuable stories by the end of the sprint. | 9 | 2 | Y | -- | -- |
| RC-003 | As a Scrum Master, I want to facilitate Sprint Planning and the team's story commitment so that the team works with focus and alignment during the sprint. | 9 | 2 | Y | -- | -- |
| RC-005 | As a developer, I want shared GitHub client and server repositories, with all team members as collaborators, connected to an Azure Static Web App and an Azure Node.js server so that I can deploy and test code collaboratively in the cloud. | 9 | 5 | Y | -- | -- |
| RC-011 | As a developer, I want a Node.js `risk-category` API that takes age, BMI category, blood pressure category, and family diseases and returns the total points and risk category (low ≤ 20, moderate ≤ 50, high ≤ 75, uninsurable > 75) so that the risk calculation is done only on the server. | 9 | 5 | Y | -- | -- |
| RC-012b | As a developer, I want a Node.js `bp-category` API that takes systolic and diastolic values and returns the category (normal, elevated, stage 1, stage 2, or crisis) so that blood pressure is categorized consistently on the server. | 9 | 3 | Y | -- | -- |
| RC-012c | As a developer, I want a Node.js `bmi` API that takes height (feet and inches) and weight (lbs) and returns the BMI and its category (normal, overweight, or obese) so that BMI is calculated consistently on the server. | 9 | 3 | Y | -- | -- |
| RC-007 | As a user, I want to enter my age, height (feet and inches), and weight (lbs), and select my systolic and diastolic blood pressure from drop-down lists so that I can enter my health information quickly and easily. | 9 | 5 | N | -- | -- |
| RC-022 | As a user, I want to see the inputs used in the calculation and my resulting risk category after I submit so that I understand my risk assessment. | 9 | 3 | N | -- | -- |
| RC-006 | As a user, I want a clean and welcoming home screen with clear, non-technical instructions so that I can use the application without any additional training. | 8 | 3 | N | -- | -- |
| RC-008 | As a user, I want my inputs validated by the server API (and by the client before sending), including height ≥ 2 feet, age > 0, and weight > 0 lbs, with a clear error message for each invalid field so that I can correct mistakes and receive accurate results. | 8 | 3 | N | -- | -- |
| RC-014 | As a Product Owner, I want to verify through code review that the client performs no calculations and only calls the server APIs so that calculation logic stays centralized and consistent. | 8 | 1 | Y | -- | -- |
| RC-015 | As a developer, I want to deploy the client as an Azure Static Web App so that I can provide users with a fast and accessible frontend. | 8 | 3 | Y | -- | -- |
| RC-017 | As a user, I want to check whether I have a family history of diabetes, cancer, or Alzheimer's so that my family history is included in my risk assessment. | 8 | 2 | N | -- | -- |
| RC-024 | As a developer, I want to verify that every team member can clone, pull, add, commit, and push to both shared repositories and that each push triggers the Azure CI/CD pipeline so that the whole team can deliver changes. | 8 | 2 | Y | -- | -- |
| RC-012a | As a developer, I want a Node.js `ping` API that returns a short "awake" response so that the client can wake the Azure server before the user submits. | 7 | 1 | Y | -- | -- |
| RC-010 | As a user, I want the client to call the `ping` API when the page loads so that the server is awake and my results return without a cold-start delay. | 7 | 1 | N | -- | -- |
| RC-013 | As a developer, I want local `.env` or config files so that I can run and test the client and server on my own machine without environment conflicts. | 7 | 2 | Y | -- | -- |
| RC-021 | As a developer, I want meaningful console log messages each time the client calls an API or receives an API response so that I can trace and debug client-server communication. | 7 | 1 | Y | -- | -- |
| RC-020 | As a user, I want to see the blood pressure category chart next to the blood pressure drop-downs so that I understand what my numbers mean. | 6 | 2 | N | -- | -- |
| RC-023 | As a user, I want to clear the form and evaluate another customer without reloading the page so that I can assess multiple customers until I am done. | 6 | 2 | N | -- | -- |
| RC-009 | As a user, I want to see a summary of my inputs before submitting so that I can confirm the information I entered is correct. | 5 | 3 | N | -- | -- |
| RC-016 | As a user, I want a modern, consistently styled interface so that the application is pleasant and easy to use. (Acceptance: styled with Tailwind CSS) | 4 | 5 | N | -- | -- |
| RC-018 | As a developer, I want to remove all unnecessary code from the Node.js servers so that I can improve maintainability and performance. | 3 | 3 | Y | -- | -- |
| RC-004 | As a developer, I want to create a GitHub organization to hold the client and server repos so that team repositories are managed in one place. (Not required for MVP; the team collaborates through shared repos.) | 2 | 2 | Y | -- | -- |
