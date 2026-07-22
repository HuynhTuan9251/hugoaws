---
title: "Tự đánh giá (Self-evaluation)"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 6. </b> "
---

Trong suốt 15 tuần thực tập, tôi đã không ngừng nỗ lực để học hỏi kiến thức mới, hoàn thiện kỹ năng chuyên môn và đóng góp giá trị thực tế cho dự án. Dưới đây là báo cáo tự đánh giá chi tiết về quá trình thực tập của bản thân dựa trên các tiêu chuẩn đánh giá năng lực:

### Bảng tổng hợp tự đánh giá năng lực

| Tiêu chí đánh giá | Mức độ hoàn thành | Kết quả đạt được & Minh chứng cụ thể |
| :--- | :---: | :--- |
| **1. Kiến thức chuyên môn** | **Tốt** | Làm chủ và triển khai thực tế **9 dịch vụ AWS** cốt lõi; thiết kế thành công **Kiến trúc Lai (Hybrid)** kết hợp MERN Stack Web App và Serverless Data Pipeline để xây dựng hệ thống SOC Dashboard hoàn chỉnh. |
| **2. Khả năng tự học** | **Tốt** | Chủ động nghiên cứu tài liệu AWS, học cách tối ưu hóa truy vấn dữ liệu lớn bằng SQL trên **Amazon Athena**, viết mã Lambda xử lý log thời gian thực bằng Node.js. |
| **3. Tính chủ động** | **Tốt** | Tự thiết kế bài toán giám sát an ninh mạng thực tế, đề xuất giải pháp nhúng trực quan hóa dữ liệu thông qua **QuickSight Dashboard** và phát triển bản đồ tấn công trực quan trên Frontend. |
| **4. Kỷ luật & Trách nhiệm** | **Tốt** | Tuân thủ nghiêm túc kế hoạch của kỳ thực tập: viết đầy đủ **15 tuần Worklog**, hoàn thành **3 bài viết kỹ thuật chất lượng cao** đúng hạn. |
| **5. Giao tiếp & Làm việc nhóm**| **Khá** | Tích cực chia sẻ kiến thức, tài liệu học tập và viết blog chia sẻ cho cộng đồng **AWS Study Group**. |
| **6. Giải quyết vấn đề** | **Tốt** | Tối ưu hóa thành công chi phí lưu trữ và băng thông truyền tải bằng cách cấu hình bộ lọc Lambda và gom nhóm dữ liệu (Batching) thông qua **Kinesis Firehose** trước khi ghi vào S3. |
| **7. Đóng góp sản phẩm** | **Tốt** | Xây dựng thành công sản phẩm thực tế có đầy đủ giao diện, chức năng đăng nhập, phân quyền người dùng (RBAC 4 vai trò) tích hợp bảo mật (JWT, Bcrypt, IAM) và phân tích dữ liệu lớn. |

---

### Phân tích chi tiết các tiêu chí

#### 1. Kiến thức chuyên môn & Kỹ năng kỹ thuật (Technical Competency)
* **Kết quả:** Nắm vững lý thuyết nền tảng và vận dụng tốt các dịch vụ AWS: EC2, VPC, Flow Logs, S3, CloudTrail, Kinesis, Lambda, Athena, GuardDuty, QuickSight.
* **Minh chứng:** 
  - Đã tích hợp thành công dữ liệu phân tích từ Amazon Athena/QuickSight vào ứng dụng ReactJS.
  - Thiết lập luồng bảo mật nhiều lớp từ phân quyền AWS IAM đến mã hóa mật khẩu người dùng (Bcrypt) và xác thực người dùng (JWT) trong phần mềm.

#### 2. Khả năng tự học & Thích ứng (Learning & Adaptability)
* **Kết quả:** Thích nghi nhanh với công nghệ mới như Cloud Security và Big Data Processing.
* **Minh chứng:**
  - Tự học cách phân tích cấu trúc gói tin của VPC Flow Logs và cách viết mã xử lý, chuẩn hóa log trên AWS Lambda.
  - Chuyển đổi tư duy từ làm việc với các cơ sở dữ liệu quan hệ truyền thống sang truy vấn phi cấu trúc trên S3 Data Lake thông qua Athena.

#### 3. Tính chủ động & Đổi mới sáng tạo (Proactivity & Initiative)
* **Kết quả:** Không chỉ làm theo các bài Lab hướng dẫn có sẵn, tôi đã tự đề xuất và triển khai một giải pháp giám sát an ninh mạng tích hợp hoàn chỉnh.
* **Minh chứng:** Thiết lập tính năng **AI Anomaly Detection** (Phát hiện bất thường bằng trí tuệ nhân tạo) để so sánh dự báo lưu lượng mạng với dữ liệu thực tế, giúp đưa ra cảnh báo sớm cho SecOps.

#### 4. Kỷ luật làm việc & Tinh thần trách nhiệm (Discipline & Responsibility)
* **Kết quả:** Đảm bảo tính nhất quán, chuyên nghiệp và đúng hạn trong tất cả các báo cáo và sản phẩm bàn giao.
* **Minh chứng:** 
  - Ghi chép nhật ký công việc ([Worklog](file:///c:/Users/Admin/hugoaws/content/1-Worklog/)) liên tục suốt 15 tuần không ngắt quãng.
  - Hoàn thành đầy đủ 3 bài [Blogs](file:///c:/Users/Admin/hugoaws/content/3-BlogsPosted/) phân tích công nghệ chuyên sâu đúng kỳ hạn đề ra.

#### 5. Giao tiếp & Tương tác nhóm (Communication & Collaboration)
* **Kết quả:** Xây dựng mối quan hệ tốt đẹp với các thành viên và người hướng dẫn.
* **Minh chứng:** Tham gia trao đổi kỹ thuật tích cực trên các kênh Slack/Facebook Group của AWS Study Group, giúp tháo gỡ các vấn đề cấu hình AWS cho các thành viên khác.

#### 6. Giải quyết vấn đề & Tư duy phân tích (Problem-Solving & Analytical Thinking)
* **Kết quả:** Khả năng định vị lỗi, phân tích nguyên nhân gốc rễ và đề xuất giải pháp tối ưu.
* **Minh chứng:** Giải quyết triệt để bài toán chi phí lưu trữ S3 và thời gian truy vấn Athena bằng việc viết script Lambda để lọc bỏ các gói tin log không hợp lệ hoặc trùng lặp trước khi lưu trữ vào Data Lake.

#### 7. Giá trị đóng góp cho dự án (Contribution & Deliverables)
* **Kết quả:** Tạo ra sản phẩm có giá trị thực tế cao, phục vụ làm tài liệu tham khảo chất lượng cho các kỳ thực tập tiếp theo.
* **Minh chứng:** Hệ thống SOC Dashboard hoàn chỉnh có mã nguồn mở trên GitHub ([tubahung04/WebAws](https://github.com/tubahung04/WebAws)) và video demo chi tiết các chức năng vận hành ([Demo Video](https://drive.google.com/file/d/1TEdgbJpFZlVTRF4iUONUCP7IIBAWoMeB/view?usp=drive_link)).

---

### Định hướng phát triển trong tương lai
Trải nghiệm từ kỳ thực tập này giúp tôi khẳng định niềm đam mê đối với lĩnh vực **Cloud Engineering** và **DevSecOps**. Trong thời gian tới, tôi sẽ:
1. Tiếp tục nghiên cứu sâu hơn về **Infrastructure as Code (IaC)** như Terraform để tự động hóa việc triển khai kiến trúc đã xây dựng.
2. Học tập và thi các chứng chỉ chuyên nghiệp của AWS (như **AWS Certified Solutions Architect – Associate** hoặc **AWS Certified Security – Specialty**).
