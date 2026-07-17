---
title: "Worklog Week 9"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Goals for week 9:

* Configure AWS Data Pipeline: VPC Flow Logs, CloudTrail, S3.
* Set up Amazon Kinesis Data Firehose and write AWS Lambda filter function.
* Enable Amazon GuardDuty.

### Tasks implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | - Enable VPC Flow Logs: Filter=All, Destination=S3, Interval=1 min | 15/06/2026 | 15/06/2026 | AWS VPC Docs |
| Tue | - Configure CloudTrail: Create Trail, push logs to S3 Bucket | 16/06/2026 | 16/06/2026 | AWS CloudTrail |
| Wed | - Create Kinesis Firehose stream, configure Source → Transform (Lambda) → S3 | 17/06/2026 | 17/06/2026 | AWS Kinesis Docs |
| Thu | - Write Lambda function `my-log-filter` (Node.js): Decode Base64, filter CONTROL_MESSAGE | 18/06/2026 | 18/06/2026 | AWS Lambda Docs |
| Fri | - Enable Amazon GuardDuty, review sample Findings | 19/06/2026 | 19/06/2026 | AWS GuardDuty |

### Results achieved:

* Data Pipeline operational: VPC Flow Logs → CloudWatch → Kinesis Firehose → Lambda → S3.
* Lambda my-log-filter processing successfully: Filters Control Messages, keeps Data Messages as JSON.
* GuardDuty detected alert when using Root credentials to call API (test successful).
