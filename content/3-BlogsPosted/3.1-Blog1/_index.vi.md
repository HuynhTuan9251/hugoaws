---
title: "Blog 1: Tối ưu chi phí lưu trữ Big Data Log bằng S3 và Kinesis Firehose"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

### Giới thiệu
Khi xây dựng hệ thống **AWS Observability & Security Dashboard**, một trong những thách thức lớn nhất là xử lý lượng lớn dữ liệu (Big Data) từ VPC Flow Logs và CloudTrail mà không làm "cháy túi" ngân sách. Thay vì sử dụng cơ sở dữ liệu truyền thống, tôi đã thiết kế một đường ống dữ liệu (Data Pipeline) hoàn toàn Serverless.

### Giải pháp kiến trúc
Tôi đã sử dụng kết hợp **Amazon Kinesis Data Firehose** và **Amazon S3**:
1. **Thu thập và Gom nhóm (Batching)**: Kinesis Firehose không ghi từng dòng log ngay lập tức vào S3. Thay vào đó, nó gom các luồng mạng lại thành từng batch lớn (ví dụ: mỗi phút một lần). Việc này giúp giảm số lượng yêu cầu (PUT requests) lên S3 đi hàng nghìn lần, tiết kiệm chi phí cực kỳ lớn.
2. **Làm sạch bằng Lambda**: Trước khi ghi vào S3, Firehose tự động gọi hàm Lambda my-log-filter để định dạng lại log thành chuẩn JSON.
3. **Lưu trữ lạnh trên S3**: Dữ liệu sau khi làm sạch được đẩy vào bucket my-aws-bucket-nhom-2026. S3 là kho lưu trữ Object Storage rẻ nhất và bền bỉ nhất trên AWS.

### Kết quả
Nhờ áp dụng mô hình này, hệ thống Backend (MERN Stack) của tôi không phải gánh vác việc xử lý dữ liệu nặng nề. Mọi luồng xử lý Big Data đều được AWS giải quyết ngầm với chi phí chỉ vài cent mỗi tháng (Pay-as-you-go). Đây là một kiến trúc chuẩn mực để xử lý dữ liệu Cloud!
