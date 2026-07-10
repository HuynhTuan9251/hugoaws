---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 21
chapter: false
pre: " <b> 1.3.3. </b> "
---

### Mục tiêu tuần 3:

* Viết Proposal (Bản đề xuất) dự án cá nhân.
* Thiết kế sơ đồ kiến trúc hệ thống (Architecture Diagram).
* Nghiên cứu IAM: Users, Groups, Roles, Policies và nguyên tắc Least Privilege.

### Các công việc đã triển khai trong tuần:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Viết Proposal: Tóm tắt điều hành, Tuyên bố vấn đề | 05/05/2026 | 05/05/2026 | |
| 3 | - Viết Proposal: Giải pháp kỹ thuật, Kiến trúc Hybrid | 06/05/2026 | 06/05/2026 | |
| 4 | - Thiết kế Architecture Diagram trên draw.io (9 dịch vụ AWS) | 07/05/2026 | 07/05/2026 | draw.io |
| 5 | - Nghiên cứu IAM: Tạo IAM User, gán Policy, tạo Role cho Lambda | 08/05/2026 | 08/05/2026 | AWS IAM Docs |
| 6 | - Hoàn thiện Proposal và nộp cho Mentor review | 09/05/2026 | 09/05/2026 | |

### Kết quả đạt được:

* Hoàn thành Proposal với đầy đủ: Executive Summary, Problem Statement, Technical Solution, Architecture Diagram.
* Vẽ xong sơ đồ kiến trúc thể hiện luồng dữ liệu từ EC2 → VPC Flow Logs → Kinesis → Lambda → S3 → Athena → QuickSight.
* Tạo IAM User riêng (huynhtuan1) thay vì dùng Root, áp dụng Principle of Least Privilege.
