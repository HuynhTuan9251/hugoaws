---
title: "Worklog Week 5"
date: 2024-01-01
weight: 41
chapter: false
pre: " <b> 1.5.5. </b> "
---

### Goals for week 5:

* Build API Endpoints for Dashboard: overview, traffic, alerts, protocols, health, anomaly.
* Create automatic Seed Data when server starts.
* Write Blog 1 about cost optimization with S3 and Kinesis Firehose.

### Tasks implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | - Code API: GET /api/dashboard/overview (KPI overview) | 19/05/2026 | 19/05/2026 | |
| Tue | - Code API: GET /api/security/alerts, GET /api/dashboard/map | 20/05/2026 | 20/05/2026 | |
| Wed | - Code API: GET /api/dashboard/protocols, /infrastructure/health | 21/05/2026 | 21/05/2026 | |
| Thu | - Build seedDatabase() function to auto-generate 6 Alerts + 200 TrafficLogs | 22/05/2026 | 22/05/2026 | |
| Fri | - Write Blog 1: Cost Optimization for Big Data Logs with S3 and Kinesis Firehose | 23/05/2026 | 23/05/2026 | |

### Results achieved:

* Completed 10 API Endpoints serving the entire Dashboard.
* System auto-seeds 4 Users, 6 Alerts (with geo_location), 200 TrafficLogs on startup.
* Completed Blog 1 and posted to AWS Study Group.
