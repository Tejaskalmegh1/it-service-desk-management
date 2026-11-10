# IT Helpdesk & Service Desk Ticket Management System

A practical, self-learning simulation of an L1 IT Service Desk. This portfolio project demonstrates how support teams receive, classify, prioritize, investigate, document, escalate, and close employee IT issues.

> **Project type:** Self-learning portfolio simulation  
> **Environment:** Fictional employees, tickets, assets, and training SLAs  
> **Tools:** Google Forms, Google Sheets, Google Docs, GitHub, Windows/macOS troubleshooting tools

## Project objectives

- Record incidents and service requests in a consistent ticket format.
- Categorize issues across hardware, software, networking, operating systems, peripherals, and account access.
- Prioritize work using impact and urgency.
- Track simulated response and resolution targets.
- Maintain a basic asset register and troubleshooting knowledge base.
- Document investigation steps, resolutions, and escalation decisions.

## Repository structure

```text
it-service-desk-management/
├── README.md
├── documentation/
│   ├── project-overview.md
│   ├── ticket-lifecycle.md
│   ├── incident-management.md
│   └── escalation-process.md
├── ticket-management/
│   └── sample-tickets.csv
├── sla-management/
│   └── sla-policy.md
├── asset-management/
│   └── asset-register.csv
├── knowledge-base/
│   ├── windows-troubleshooting.md
│   ├── networking-troubleshooting.md
│   ├── printer-troubleshooting.md
│   ├── software-troubleshooting.md
│   └── hardware-troubleshooting.md
└── screenshots/
    └── README.md
```

## How to use this project

1. Read the documents in `documentation/` to understand the workflow.
2. Import `ticket-management/sample-tickets.csv` into Google Sheets or Excel.
3. Import `asset-management/asset-register.csv` into a separate sheet.
4. Review `sla-management/sla-policy.md`. The targets are illustrative training values, not real contractual commitments.
5. Use the knowledge-base articles as checklists when practising in a safe test environment.
6. Replace or extend the fictional records with your own clearly labelled practice scenarios.
7. Capture genuine screenshots of your completed spreadsheet dashboard and forms in `screenshots/`.

## Suggested Google Sheets workbook

Create a workbook named `IT_Service_Desk_Management` with these tabs:

- **Dashboard:** ticket counts by status, priority, and category.
- **Tickets:** import `sample-tickets.csv`.
- **SLA Tracker:** calculate target due times and compare them with actual timestamps.
- **Asset Register:** import `asset-register.csv`.
- **Knowledge Base:** list article titles, categories, and article filenames.

Suggested ticket status values: `Open`, `In Progress`, `Pending`, `Resolved`, `Closed`, `Escalated`.

## Important project limitations

- This is a simulation, not a production ticketing platform.
- Google Forms/Sheets do not automatically provide enterprise-grade access control, audit trails, notifications, or SLA enforcement.
- All names, departments, devices, ticket records, and timestamps in the sample data are fictional.
- Do not use real employee information, passwords, serial numbers, or confidential company data.
- Perform troubleshooting only on devices and networks you own or are authorized to support.

## Skills demonstrated

IT service desk fundamentals, ticket documentation, incident categorization, priority assignment, basic SLA tracking, asset inventory, desktop troubleshooting, networking fundamentals, escalation, and technical communication.

## Suggested GitHub commits

```text
docs: add service desk project overview
docs: document ticket lifecycle and incident process
feat: add sample service desk ticket records
feat: add IT asset inventory sample
docs: add simulated SLA policy
docs: add troubleshooting knowledge base
docs: add project screenshots and final documentation
```

## Resume description

**IT Helpdesk & Service Desk Ticket Management System** — Self-learning project

Designed a simulated IT Service Desk workflow to document and track technical incidents and service requests. Created sample ticket and asset registers, defined training priority and SLA rules, documented escalation procedures, and developed troubleshooting guides for common desktop, hardware, software, printer, and network issues.

Only list features you have personally implemented, tested, and can explain in an interview.
