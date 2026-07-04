---
title: "Worklog Tuần 10"
date: 2026-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Tiếp tục triển khai hệ thống ZeroBug Agent trên nền tảng AWS.
* Hoàn thiện các AWS Lambda Functions phục vụ quy trình sinh Unit Test.
* Tích hợp Amazon Bedrock Claude 3 Haiku vào hệ thống.
* Hoàn thiện AWS Step Functions Workflow và kết nối với Amazon SQS.
* Kiểm thử toàn bộ quy trình xử lý theo mô hình Serverless.

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
- Rà soát kiến trúc Serverless của hệ thống ZeroBug Agent.<br>
- Kiểm tra các Lambda Functions đã triển khai.<br>
- Chuẩn hóa cấu trúc mã nguồn và thư mục.<br>
- Cấu hình Environment Variables và kiểm tra IAM Roles, IAM Policies.<br>
- Chuẩn bị dữ liệu mẫu phục vụ kiểm thử Workflow.
</td>
<td class="col-date">22/06/2026</td>
<td class="col-date">22/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">2</td>
<td class="col-task">
- Hoàn thiện Lambda Project Import Service.<br>
- Tiếp nhận Repository Git hoặc tệp ZIP.<br>
- Clone Repository hoặc giải nén Project.<br>
- Upload mã nguồn lên Amazon S3.<br>
- Kiểm tra Metadata và xử lý dữ liệu không hợp lệ.
</td>
<td class="col-date">23/06/2026</td>
<td class="col-date">23/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">3</td>
<td class="col-task">
- Hoàn thiện Lambda Context Builder.<br>
- Phân tích cấu trúc Project.<br>
- Nhận diện ngôn ngữ lập trình (Java, Python, .NET).<br>
- Thu thập Metadata và chuẩn hóa dữ liệu đầu ra.<br>
- Kiểm thử với nhiều Project mẫu.
</td>
<td class="col-date">24/06/2026</td>
<td class="col-date">24/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">4</td>
<td class="col-task">
- Hoàn thiện Lambda Source File Service.<br>
- Đọc danh sách Source Files từ Amazon S3.<br>
- Lọc các thư mục và tệp không cần thiết.<br>
- Chuẩn hóa dữ liệu gửi đến Amazon Bedrock.<br>
- Đánh giá hiệu năng xử lý dữ liệu.
</td>
<td class="col-date">25/06/2026</td>
<td class="col-date">25/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">5</td>
<td class="col-task">
- Hoàn thiện Lambda AI Invoke Service.<br>
- Tích hợp Amazon Bedrock Runtime.<br>
- Cấu hình Claude 3 Haiku.<br>
- Xây dựng Prompt Template.<br>
- Kiểm thử kết quả sinh Unit Test và đánh giá chất lượng.
</td>
<td class="col-date">26/06/2026</td>
<td class="col-date">26/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">6</td>
<td class="col-task">
- Hoàn thiện Lambda Result Service.<br>
- Lưu kết quả lên Amazon S3.<br>
- Hoàn thiện Lambda History Service.<br>
- Lưu lịch sử xử lý vào Amazon RDS.<br>
- Theo dõi CloudWatch Logs và kiểm tra dữ liệu.
</td>
<td class="col-date">27/06/2026</td>
<td class="col-date">27/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">7</td>
<td class="col-task">
- Hoàn thiện AWS Step Functions Workflow.<br>
- Liên kết đầy đủ các Lambda Functions.<br>
- Cấu hình Retry, Catch và Timeout.<br>
- Kết nối Amazon SQS với Lambda Trigger.<br>
- Kiểm thử End-to-End và cập nhật tài liệu Workshop.
</td>
<td class="col-date">28/06/2026</td>
<td class="col-date">28/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

</tbody>
</table>

### Kết quả đạt được tuần 10:

* Hoàn thiện các AWS Lambda Functions phục vụ quy trình sinh Unit Test.
* Tích hợp thành công Amazon Bedrock Claude 3 Haiku.
* Xây dựng hoàn chỉnh Workflow bằng AWS Step Functions.
* Kết nối thành công Amazon SQS với AWS Lambda và AWS Step Functions.
* Lưu kết quả trên Amazon S3 và lịch sử xử lý trên Amazon RDS.
* Kiểm thử thành công quy trình End-to-End.
* Theo dõi hệ thống thông qua Amazon CloudWatch Logs và Execution History.
* Hoàn thiện phần lớn nội dung Workshop, tạo nền tảng cho giai đoạn tối ưu hóa hệ thống.