# OctoAcme Project Management Processes

## Overview
OctoAcme runs projects with an iterative, outcome-focused process that moves work from initiation through planning, execution, release, and continuous improvement. Projects begin with a lightweight Project One-pager to capture the problem, success metrics, stakeholders, and a high-level timeline; initiatives move into planning only after success criteria and stakeholder alignment are confirmed. Planning breaks approved initiatives into prioritized, estimable backlog items with clear acceptance criteria and a Definition of Done, and captures dependencies and risks in a lightweight Risk Register.

## Team rhythm & workflows
Day-to-day execution follows a visible project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a pull-request-oriented code process: keep PRs small when possible, include issue links and acceptance criteria, and run CI tests and security scans before requesting review. Team rhythm includes short daily standups for blockers, weekly delivery syncs to show progress and surface risks, PM+PdM alignment meetings, and demos at the end of sprints or milestones. Stakeholder communication is standardized with weekly status templates and defined escalation paths from team-level triage up to sponsor-level involvement for business-impacting issues.

## Quality & testing
Quality assurance is embedded across the lifecycle: unit and integration tests for new logic, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed to validate acceptance criteria. Pre-release requirements include passing CI and security checks, drafted release notes, a rollback/mitigation plan, and running smoke tests in staging prior to production. The Release & Deployment guide also includes an incident playbook to trigger response and post-incident learning.

## Continuous improvement
Continuous improvement is operationalized through structured retrospectives (timeboxed, focused on 2–3 action items) and by tracking action items back into the backlog. Project artifacts are versioned and stored in this repo's docs/ folder, and process updates can be proposed via the provided issue template in .github/ISSUE_TEMPLATE.

## Process documentation (links)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use these docs
- Start with the Project Management Overview to understand principles and lifecycle.
- Use the One-pager and initiation guide when evaluating new initiatives.
- Follow the Planning and Execution docs during delivery and add action items to the project board.
- Use the Release & Deployment checklist when preparing releases.
- Capture improvements in retrospectives and create issues to track follow-up work.
