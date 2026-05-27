# BIM Clash Detection Dashboard

> Interactive analytics dashboard for BIM coordination workflows, 
> tracking clash resolution, discipline interference, SLA performance,
> and backlog burn-down across AEC project phases.

🔗 **Live Demo:** https://karinacs2.github.io/bim-project-dashboard/

---

## Overview

Clash detection in BIM coordination generates large volumes of data that
typically remain locked in static Navisworks or Solibri reports or unstructured
spreadsheets, invisible to project managers and hard to act on.

This dashboard transforms clash report data into structured, interactive
visualizations, enabling coordination teams to monitor resolution
progress, identify bottlenecks by discipline, and track SLA compliance
in real time.

---

## Key Metrics Tracked

| KPI | Value (sample dataset) |
|---|---|
| Total Clashes Identified | 847 |
| Resolution Rate | 83.1% |
| Critical Open Clashes | 38 |
| Average Resolution Time | 11 days |
| SLA Compliance | 78% (target: 85%) |
| Rework Rate | 19% |
| Coordination Efficiency Score | 71% |

---

## Features

- **Monthly clash volume** — identified vs resolved vs active backlog
- **Discipline breakdown** — Hydraulics, Electrical, HVAC, Structure
- **Interference matrix** — clash volume between all discipline pairs
- **Resolution pipeline** — open → in analysis → in review → resolved → validated
- **Aging analysis** — clashes by days open, flagging SLA risk
- **Floor-level distribution** — concentration map by building level
- **Clash type classification** — Hard Clash / Soft Clash / Clearance / Workflow
- **Burn-down chart** — planned vs actual backlog reduction
- **Root cause Pareto** — top categories driving 68% of all clashes
- **Average resolution time by discipline** — vs 12-day target

---

## Technologies

| Layer | Stack |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic & Charts | JavaScript |
| Hosting | GitHub Pages |
| Domain | BIM Coordination / AEC Analytics |

---

## Project Context

This project was designed to bridge two areas:

**BIM Coordination** — clash management, discipline coordination,
ISO 19650-aligned workflows, CDE processes.

**Data Analytics** — KPI design, visual communication, dashboard
architecture, performance monitoring.

It reflects the kind of data layer that BIM coordinators work with
daily but rarely get to visualize in a structured, accessible way.

---

## Repository Structure

```text
bim-project-dashboard/
│
├── index.html          # Main dashboard layout
├── style.css           # Styling and responsive design
├── script.js           # Chart logic and interactivity
├── BIM Dashboard.png   # Dashboard preview image
└── README.md
```

---

## Dashboard Preview

![BIM Clash Detection Dashboard](https://github.com/karinacs2/bim-project-dashboard/blob/main/BIM%20Dashboard.png)

---
