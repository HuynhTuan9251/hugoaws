---
title: "Worklog Week 11"
date: 2024-01-01
weight: 101
chapter: false
pre: " <b> 1.11.11. </b> "
---

### Goals for week 11:

* Integrate AWS SDK into Backend Node.js to call Athena.
* Capture screenshots of entire AWS process on Console.
* Start writing Workshop report on Hugo template.

### Tasks implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | - Install @aws-sdk/client-athena into Backend Node.js | 29/06/2026 | 29/06/2026 | AWS SDK v3 |
| Tue | - Code queryAthena() function to get Top REJECTED IPs from Backend | 30/06/2026 | 30/06/2026 | |
| Wed | - Capture screenshots: EC2, VPC, S3, Lambda, Firehose, Athena, QuickSight, GuardDuty | 01/07/2026 | 01/07/2026 | AWS Console |
| Thu | - Clone Hugo template (fcj-workshop-template), start writing Workshop | 02/07/2026 | 02/07/2026 | Hugo Docs |
| Fri | - Write sections 5.1 (Overview) and 5.2 (Prerequisites) for Workshop | 03/07/2026 | 03/07/2026 | |

### Results achieved:

* Backend Node.js can call Athena Query directly via AWS SDK, returning results to React Dashboard.
* Collected real screenshots for all 9 AWS services from Console.
* Workshop website running successfully on http://localhost:1313 with Hugo.
