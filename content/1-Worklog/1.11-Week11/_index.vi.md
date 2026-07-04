---
title: "Week 11 Worklog"
date: 2026-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu

* Tích hợp toàn bộ các thành phần của hệ thống ZeroBug Agent.
* Kiểm thử quy trình sinh Unit Test trên môi trường AWS.
* Hoàn thiện kết nối giữa Backend và các dịch vụ Serverless.
* Theo dõi, xử lý lỗi và tối ưu hiệu năng của hệ thống.
* Chuẩn bị tài liệu và kết quả phục vụ báo cáo Workshop.

### Nội dung thực hiện

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
<th>Tài liệu tham khảo</th>
</tr>
</thead>

<tbody>

<tr>
<td class="col-day">1</td>
<td class="col-task">
- Rà soát kiến trúc ZeroBug Agent sau khi hoàn thành Lambda và Step Functions.<br>
- Kiểm tra kết nối Backend API với Amazon SQS.<br>
- Kiểm tra luồng gửi yêu cầu từ giao diện người dùng đến Backend.<br>
- Đối chiếu dữ liệu đầu vào và JSON Payload.<br>
- Hoàn thiện tài liệu mô tả luồng xử lý của hệ thống.
</td>
<td class="col-date">29/06/2026</td>
<td class="col-date">29/06/2026</td>
<td class="col-ref">AWS Documentation, Workshop Materials</td>
</tr>

<tr>
<td class="col-day">2</td>
<td class="col-task">
- Tích hợp Backend với Amazon SQS.<br>
- Kiểm tra gửi yêu cầu sinh Unit Test từ giao diện Web.<br>
- Theo dõi Message trong Amazon SQS.<br>
- Kiểm tra Lambda Trigger.<br>
- Kiểm tra Step Functions khởi động sau khi nhận yêu cầu.
</td>
<td class="col-date">30/06/2026</td>
<td class="col-date">30/06/2026</td>
<td class="col-ref">AWS Documentation, Workshop Materials</td>
</tr>

<tr>
<td class="col-day">3</td>
<td class="col-task">
- Kiểm thử AWS Step Functions Workflow với nhiều bộ dữ liệu.<br>
- Theo dõi Execution History.<br>
- Kiểm tra dữ liệu truyền giữa các Task States.<br>
- Kiểm thử Lambda Project Import, Context Builder, Source File Service, AI Invoke Service, Result Service và History Service.<br>
- Điều chỉnh các lỗi phát sinh.
</td>
<td class="col-date">01/07/2026</td>
<td class="col-date">01/07/2026</td>
<td class="col-ref">AWS Step Functions Documentation</td>
</tr>

<tr>
<td class="col-day">4</td>
<td class="col-task">
- Kiểm thử chức năng sinh Unit Test bằng Amazon Bedrock Claude 3 Haiku.<br>
- Kiểm tra các dự án Java, Python và .NET.<br>
- Đánh giá chất lượng Unit Test.<br>
- Điều chỉnh Prompt Template.<br>
- Ghi nhận thời gian xử lý.
</td>
<td class="col-date">02/07/2026</td>
<td class="col-date">02/07/2026</td>
<td class="col-ref">Amazon Bedrock Documentation</td>
</tr>

<tr>
<td class="col-day">5</td>
<td class="col-task">
- Kiểm tra lưu trữ Unit Test trên Amazon S3.<br>
- Kiểm tra dữ liệu lịch sử trên Amazon RDS.<br>
- Đối chiếu dữ liệu giữa Amazon S3, Amazon RDS và Backend.<br>
- Kiểm tra truy xuất lịch sử xử lý.<br>
- Đánh giá tính toàn vẹn của dữ liệu.
</td>
<td class="col-date">03/07/2026</td>
<td class="col-date">03/07/2026</td>
<td class="col-ref">Amazon S3 & Amazon RDS Documentation</td>
</tr>

<tr>
<td class="col-day">6</td>
<td class="col-task">
- Theo dõi hệ thống bằng Amazon CloudWatch.<br>
- Kiểm tra CloudWatch Logs của từng Lambda Function.<br>
- Phân tích Timeout, Exception và Retry.<br>
- Điều chỉnh Timeout và Memory Allocation.<br>
- Kiểm tra IAM Roles và quyền truy cập.
</td>
<td class="col-date">04/07/2026</td>
<td class="col-date">04/07/2026</td>
<td class="col-ref">Amazon CloudWatch Documentation</td>
</tr>

<tr>
<td class="col-day">7</td>
<td class="col-task">
- Kiểm thử End-to-End toàn bộ hệ thống.<br>
- Kiểm tra quy trình từ Upload Project đến trả kết quả.<br>
- Đánh giá hiệu năng xử lý.<br>
- Tổng hợp các lỗi đã khắc phục.<br>
- Hoàn thiện tài liệu kỹ thuật và Workshop.
</td>
<td class="col-date">05/07/2026</td>
<td class="col-date">05/07/2026</td>
<td class="col-ref">AWS Documentation, Workshop Materials</td>
</tr>

</tbody>
</table>

### Kết quả đạt được

* Hoàn thành tích hợp Backend API với các dịch vụ AWS Serverless.
* Kiểm thử thành công quy trình sinh Unit Test từ đầu đến cuối.
* Kết nối thành công Amazon SQS, AWS Lambda, AWS Step Functions, Amazon Bedrock, Amazon S3 và Amazon RDS.
* Theo dõi và xử lý lỗi bằng Amazon CloudWatch Logs và AWS Step Functions Execution History.
* Tối ưu cấu hình Lambda Functions nhằm cải thiện hiệu năng và giảm thời gian xử lý.
* Đánh giá chất lượng Unit Test được sinh bởi Amazon Bedrock Claude 3 Haiku và cải thiện Prompt Template.
* Hoàn thiện tài liệu kiểm thử và cập nhật nội dung Workshop.
* Chuẩn bị đầy đủ môi trường và tài liệu phục vụ giai đoạn nghiệm thu và báo cáo.