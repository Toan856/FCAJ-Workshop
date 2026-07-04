---
title: "Worklog Tuần 8"
date: 2026-01-01
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Hoàn thiện thiết kế tổng thể của hệ thống ZeroBug Agent.
* Thiết kế kiến trúc triển khai trên nền tảng AWS theo mô hình Serverless.
* Xây dựng sơ đồ luồng xử lý và luồng dữ liệu của hệ thống.
* Thiết kế cơ sở dữ liệu phục vụ lưu trữ lịch sử sinh Unit Test.
* Chuẩn bị đầy đủ tài liệu kỹ thuật phục vụ giai đoạn triển khai Workshop.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|------|-----------|--------------|-----------------|----------------|
|08/06|Phân tích lại toàn bộ yêu cầu của hệ thống ZeroBug Agent; xác định các thành phần Frontend, Backend API, AWS Serverless Services, Database và AI Service; phân tích luồng xử lý và hoàn thiện tài liệu mô tả chức năng của từng thành phần.|08/06/2026|08/06/2026|Tài liệu dự án, AWS Documentation|
|09/06|Thiết kế sơ đồ kiến trúc triển khai trên AWS; xác định vai trò của Amazon EC2, Amazon SQS, AWS Step Functions, AWS Lambda, Amazon Bedrock, Amazon S3, Amazon RDS và Amazon CloudWatch; đánh giá khả năng mở rộng của hệ thống.|09/06/2026|09/06/2026|AWS Architecture Center|
|10/06|Thiết kế Workflow xử lý của hệ thống từ khi người dùng gửi yêu cầu đến khi nhận Unit Test; xây dựng luồng xử lý qua Amazon SQS, AWS Lambda, AWS Step Functions, Amazon Bedrock, Amazon S3 và Amazon RDS; đề xuất cơ chế Retry bằng AWS Step Functions.|10/06/2026|10/06/2026|AWS Documentation|
|11/06|Thiết kế cơ sở dữ liệu; xây dựng mô hình ERD; xác định các bảng Users, Projects, TestHistory, GeneratedTests và Logs; thiết kế khóa chính, khóa ngoại và đánh giá khả năng mở rộng của cơ sở dữ liệu.|11/06/2026|11/06/2026|Tài liệu thiết kế hệ thống|
|12/06|Thiết kế giao diện người dùng (UI/UX); xây dựng Wireframe cho các màn hình Đăng nhập, Dashboard, Upload Project, Lịch sử và Kết quả Unit Test; tối ưu trải nghiệm người dùng và rà soát tính thống nhất của giao diện.|12/06/2026|12/06/2026|Figma, Tài liệu dự án|
|13/06|Hoàn thiện Prototype giao diện; kiểm tra luồng chuyển giữa các màn hình; cập nhật góp ý từ các thành viên; điều chỉnh bố cục và chuẩn bị giao diện cho giai đoạn tích hợp Backend.|13/06/2026|13/06/2026|Figma|
|14/06|Tổng hợp tài liệu thiết kế; rà soát kiến trúc AWS, Workflow và cơ sở dữ liệu; chuẩn bị môi trường AWS phục vụ Workshop về Lambda, Step Functions và Amazon Bedrock; xây dựng danh sách tài nguyên AWS cần triển khai.|14/06/2026|14/06/2026|AWS Documentation|

### Kết quả đạt được tuần 8:

* Hoàn thiện thiết kế tổng thể của hệ thống ZeroBug Agent theo mô hình Serverless trên AWS.
* Xây dựng sơ đồ kiến trúc thể hiện mối liên kết giữa Amazon EC2, Amazon SQS, AWS Step Functions, AWS Lambda, Amazon Bedrock, Amazon S3, Amazon RDS và Amazon CloudWatch.
* Thiết kế hoàn chỉnh Workflow xử lý yêu cầu sinh Unit Test từ khi người dùng tải dự án đến khi nhận kết quả.
* Hoàn thiện mô hình cơ sở dữ liệu và xác định các bảng lưu trữ thông tin người dùng, dự án và lịch sử sinh Unit Test.
* Xây dựng Wireframe và Prototype giao diện đáp ứng các chức năng chính của hệ thống.
* Chuẩn bị đầy đủ tài liệu thiết kế và môi trường AWS cho giai đoạn triển khai Workshop và phát triển hệ thống.