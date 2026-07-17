---
title: "Worklog Week 10"
date: 2024-01-01
weight: 91
chapter: false
pre: " <b> 1.10.10. </b> "
---

### Goals for week 10:

* Configure Amazon Athena: Create database, table to query VPC Flow Logs on S3.
* Configure Amazon QuickSight: Create data visualization Dashboard.
* Write Blog 3 about Amazon GuardDuty.

### Tasks implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | - Create Athena Database and Table pointing to S3 Data Lake | 22/06/2026 | 22/06/2026 | AWS Athena Docs |
| Tue | - Run test SQL query: SELECT srcAddr, COUNT(*) ... WHERE action='REJECT' | 23/06/2026 | 23/06/2026 | |
| Wed | - Register QuickSight, connect Data Source with Athena | 24/06/2026 | 24/06/2026 | AWS QuickSight |
| Thu | - Create QuickSight Dashboard: IP bar chart, Protocol pie chart | 25/06/2026 | 25/06/2026 | |
| Fri | - Write Blog 3: Automated Cloud Security Monitoring with Amazon GuardDuty | 26/06/2026 | 26/06/2026 | |

### Results achieved:

* Athena successfully queries VPC Flow Logs data from S3 at near-$0 cost.
* QuickSight Dashboard displays Count of Records by srcAddr, Protocol distribution charts.
* Completed Blog 3 about GuardDuty and posted to AWS Study Group.
