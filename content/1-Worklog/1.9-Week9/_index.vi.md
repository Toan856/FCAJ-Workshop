---
title: "Worklog Tuần 9"
date: 2026-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Bắt đầu triển khai hạ tầng AWS phục vụ hệ thống ZeroBug Agent.
* Tìm hiểu và cấu hình các dịch vụ AWS Lambda, Amazon SQS và AWS Step Functions.
* Xây dựng quy trình xử lý Serverless theo kiến trúc đã thiết kế.
* Chuẩn bị môi trường phục vụ Workshop triển khai hệ thống.
* Kiểm tra khả năng kết nối giữa các dịch vụ AWS trước khi tích hợp vào dự án.

### Các công việc cần triển khai trong tuần này:

<table class="worklog-table">
<colgroup>
  <col class="col-day" style="width:5%">
  <col class="col-task" style="width:42%">
  <col class="col-start" style="width:13%">
  <col class="col-end" style="width:13%">
  <col class="col-ref" style="width:27%">
</colgroup>

<thead>
<tr>
<th>Ngày</th>
<th>Công việc</th>
<th>Ngày bắt đầu</th>
<th>Ngày hoàn thành</th>
<th>Nguồn tài liệu</th>
</tr>
</thead>

<tbody>

<tr>
<td class="col-day">1</td>
<td class="col-task">
- Rà soát lại kiến trúc Serverless đã thiết kế ở tuần trước.<br>
- Chuẩn bị tài khoản AWS và kiểm tra quyền truy cập AWS Lambda, Amazon SQS, AWS Step Functions và Amazon Bedrock.<br>
- Tạo IAM Role cho Lambda Execution và Step Functions Execution.<br>
- Cấu hình IAM Policy cho phép Lambda truy cập Amazon S3, Amazon RDS, Amazon CloudWatch và Amazon Bedrock.
</td>
<td class="col-date">15/06/2026</td>
<td class="col-date">15/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">2</td>
<td class="col-task">
- Nghiên cứu AWS Lambda và mô hình Function as a Service (FaaS).<br>
- Chuẩn bị môi trường phát triển bằng Visual Studio Code và AWS Toolkit.<br>
- Tạo Lambda Function đầu tiên phục vụ kiểm thử.<br>
- Triển khai và kiểm tra Lambda Function trên AWS Console, theo dõi kết quả bằng CloudWatch Logs.
</td>
<td class="col-date">16/06/2026</td>
<td class="col-date">16/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">3</td>
<td class="col-task">
- Nghiên cứu dịch vụ Amazon Simple Queue Service (Amazon SQS).<br>
- Tạo Standard Queue phục vụ tiếp nhận yêu cầu sinh Unit Test.<br>
- Thực hiện gửi và nhận Message để kiểm thử.<br>
- Tìm hiểu các thuộc tính như Visibility Timeout, Message Retention và Dead-Letter Queue.
</td>
<td class="col-date">17/06/2026</td>
<td class="col-date">17/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">4</td>
<td class="col-task">
- Nghiên cứu AWS Step Functions.<br>
- Thiết kế Workflow gồm các bước: tiếp nhận yêu cầu, Project Import, phân tích mã nguồn, gọi Amazon Bedrock, lưu kết quả và ghi lịch sử xử lý.<br>
- Tạo State Machine đầu tiên.<br>
- Kiểm thử Workflow với dữ liệu mẫu.
</td>
<td class="col-date">18/06/2026</td>
<td class="col-date">18/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">5</td>
<td class="col-task">
- Xây dựng các Lambda Function cho từng bước xử lý.<br>
- Khởi tạo các Function gồm Context Builder, Source File Service, AI Invoke Service, Result Service và History Service.<br>
- Cấu hình Runtime và Environment Variables.<br>
- Kiểm tra khả năng hoạt động độc lập của từng Lambda Function.
</td>
<td class="col-date">19/06/2026</td>
<td class="col-date">19/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">6</td>
<td class="col-task">
- Liên kết AWS Step Functions với các Lambda Function đã tạo.<br>
- Cấu hình Task State, Input và Output cho từng bước xử lý.<br>
- Thiết lập Retry và Catch để xử lý lỗi.<br>
- Theo dõi Execution History và đánh giá luồng hoạt động.
</td>
<td class="col-date">20/06/2026</td>
<td class="col-date">20/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">7</td>
<td class="col-task">
- Kiểm thử toàn bộ quy trình Serverless.<br>
- Gửi yêu cầu mẫu đến Amazon SQS.<br>
- Kiểm tra việc kích hoạt Lambda và AWS Step Functions.<br>
- Theo dõi CloudWatch Logs và tối ưu Workflow.<br>
- Cập nhật tài liệu Workshop.
</td>
<td class="col-date">21/06/2026</td>
<td class="col-date">21/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

</tbody>
</table>

### Kết quả đạt được tuần 9:

* Hoàn thành việc chuẩn bị môi trường AWS phục vụ triển khai hệ thống ZeroBug Agent.
* Cấu hình thành công IAM Role và IAM Policy cho AWS Lambda và AWS Step Functions.
* Triển khai thành công các Lambda Function phục vụ quy trình xử lý.
* Tạo và cấu hình Amazon SQS để xử lý các yêu cầu bất đồng bộ.
* Thiết kế và triển khai Workflow đầu tiên bằng AWS Step Functions theo kiến trúc Serverless.
* Hoàn thành việc tích hợp giữa Amazon SQS, AWS Lambda và AWS Step Functions.
* Kiểm thử thành công luồng xử lý cơ bản và theo dõi hoạt động thông qua Amazon CloudWatch Logs.
* Chuẩn bị đầy đủ môi trường và tài liệu để tích hợp Amazon Bedrock trong các giai đoạn tiếp theo.