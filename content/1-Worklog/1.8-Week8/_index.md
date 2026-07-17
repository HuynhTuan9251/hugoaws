---
title: "Worklog Week 8"
date: 2024-01-01
weight: 71
chapter: false
pre: " <b> 1.8.8. </b> "
---

### Goals for week 8:

* Code components: AttackMap (global attack map) and TopIPConsole.
* Complete 3-tab interface (Dashboard, Security, Traffic) in App.jsx.
* Optimize UI/UX: micro-animations, responsive layout.

### Tasks implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | - Code AttackMap.jsx (map showing attack IP locations by geo_location) | 08/06/2026 | 08/06/2026 | |
| Tue | - Code TopIPConsole.jsx (Top 10 IPs, filter by protocol, terminal effect) | 09/06/2026 | 09/06/2026 | |
| Wed | - Build App.jsx: Router, 3 tabs, ProtectedRoute component | 10/06/2026 | 10/06/2026 | React Router |
| Thu | - Add micro-animations (fade-in, slide-in), blur gradient background effects | 11/06/2026 | 11/06/2026 | TailwindCSS |
| Fri | - E2E test entire Web App: Login → Dashboard → Security → Traffic | 12/06/2026 | 12/06/2026 | |

### Results achieved:

* Completed all 9 React Components for SOC Dashboard.
* AttackMap displays attack locations from 6 countries (China, UK, Russia, USA, Brazil, Australia).
* TopIPConsole supports protocol filtering (ALL, TCP, HTTP, UDP, ICMP) with terminal-style UI.
* Web App fully functional End-to-End.
