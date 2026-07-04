---
title: "Worklog Tuần 7"
date: 2026-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Tiếp tục nghiên cứu các dịch vụ AWS phục vụ dự án ZeroBug Agent.
* Phân tích yêu cầu chức năng và yêu cầu phi chức năng của hệ thống.
* Xây dựng phương án triển khai kiến trúc Serverless trên AWS.
* Xác định vai trò của từng dịch vụ AWS trong quá trình xử lý và sinh Unit Test tự động.
* Lập kế hoạch triển khai các module và phân chia nhiệm vụ trong nhóm.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|------|-----------|--------------|-----------------|----------------|
|01/06|Tổng hợp yêu cầu của dự án ZeroBug Agent từ tài liệu đặc tả và các buổi họp nhóm; phân tích mục tiêu của hệ thống; xác định luồng xử lý chính; rà soát các dịch vụ AWS đã nghiên cứu và tìm hiểu kiến trúc Serverless cùng các yêu cầu về hiệu năng, mở rộng và bảo mật.|01/06/2026|01/06/2026|Tài liệu dự án, AWS Documentation|
|02/06|Phân tích yêu cầu chức năng và phi chức năng của hệ thống; xác định các chức năng Upload Project, phân tích mã nguồn, sinh Unit Test bằng AI, lưu lịch sử và trả kết quả; thảo luận với nhóm để thống nhất phạm vi triển khai.|02/06/2026|02/06/2026|Tài liệu dự án|
|03/06|Nghiên cứu kiến trúc Serverless trên AWS; phân tích vai trò của Amazon SQS, AWS Lambda, AWS Step Functions, Amazon Bedrock, Amazon S3, Amazon RDS và Amazon CloudWatch; xây dựng sơ đồ luồng dữ liệu ban đầu của hệ thống.|03/06/2026|03/06/2026|AWS Documentation|
|04/06|Thiết kế sơ bộ kiến trúc ZeroBug Agent; xác định mối liên kết giữa Frontend, Backend và hạ tầng AWS; phân tích luồng xử lý từ khi người dùng tải Repository hoặc tệp ZIP đến khi nhận kết quả; đánh giá ưu điểm của kiến trúc Serverless.|04/06/2026|04/06/2026|AWS Architecture Center|
|05/06|Lập kế hoạch triển khai các module của hệ thống; xác định các giai đoạn phát triển gồm thiết kế kiến trúc, Backend API, Lambda Functions, Step Functions Workflow, tích hợp Amazon Bedrock, kiểm thử và tối ưu hệ thống; hoàn thiện tài liệu kế hoạch.|05/06/2026|05/06/2026|Tài liệu dự án|
|06/06|Họp nhóm phân chia nhiệm vụ; thống nhất phạm vi công việc của từng thành viên; nhận nhiệm vụ triển khai hạ tầng AWS; xây dựng kế hoạch Workshop về AWS Lambda, Step Functions và Amazon Bedrock; cập nhật tiến độ dự án.|06/06/2026|06/06/2026|Biên bản họp nhóm|
|07/06|Tổng hợp kết quả nghiên cứu trong tuần; hoàn thiện tài liệu phân tích yêu cầu và sơ đồ kiến trúc tổng quan; rà soát các dịch vụ AWS sẽ sử dụng; chuẩn bị tài liệu kỹ thuật cho giai đoạn thiết kế chi tiết và Workshop; lập danh sách các nội dung cần nghiên cứu bổ sung.|07/06/2026|07/06/2026|AWS Documentation|

### Kết quả đạt được tuần 7:

* Hoàn thành việc phân tích yêu cầu chức năng và phi chức năng của hệ thống ZeroBug Agent.
* Xây dựng được phương án kiến trúc Serverless phù hợp với mục tiêu của dự án.
* Xác định rõ vai trò của Amazon SQS, AWS Lambda, AWS Step Functions, Amazon Bedrock, Amazon S3, Amazon RDS và Amazon CloudWatch trong toàn bộ quy trình xử lý.
* Hoàn thiện sơ đồ luồng dữ liệu và kiến trúc tổng quan của hệ thống.
* Lập kế hoạch triển khai các module và phân chia nhiệm vụ giữa các thành viên.
* Chuẩn bị đầy đủ tài liệu và môi trường cho giai đoạn thiết kế chi tiết và triển khai Workshop.