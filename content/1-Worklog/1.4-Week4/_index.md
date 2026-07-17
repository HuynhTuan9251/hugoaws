---
title: "Worklog Week 4"
date: 2024-01-01
weight: 31
chapter: false
pre: " <b> 1.4.4. </b> "
---

### Goals for week 4:

* Initialize Backend project: Node.js + Express + MongoDB.
* Design MongoDB Database Schema (User, Alert, TrafficLog).
* Build Authentication system (JWT) and Role-Based Access Control (RBAC).

### Tasks implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | - Initialize Node.js project, install Express, Mongoose, bcryptjs, jsonwebtoken | 11/05/2026 | 11/05/2026 | npm |
| Tue | - Design 3 MongoDB Schemas: User, Alert, TrafficLog | 12/05/2026 | 12/05/2026 | Mongoose Docs |
| Wed | - Code login API: POST /api/auth/login with JWT Token | 13/05/2026 | 13/05/2026 | JWT.io |
| Thu | - Build authorization middleware: verifyToken, checkRole | 14/05/2026 | 14/05/2026 | |
| Fri | - Design 4 roles (NetAdmin, SecOps, Manager, SystemAdmin) and test RBAC | 15/05/2026 | 15/05/2026 | |

### Results achieved:

* Backend server running at http://localhost:5000, connected to MongoDB (database: aws_monitor) successfully.
* Complete JWT Authentication system: Login → Receive Token → Send Token in Header for all APIs.
* RBAC working: Only SecOps and SystemAdmin can change security alert statuses.
