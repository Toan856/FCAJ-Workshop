---
title: "Worklog Tuần 12"
date: 2026-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu:

* Hoàn thiện toàn bộ hệ thống ZeroBug Agent trên nền tảng AWS.
* Kiểm thử tổng thể và đánh giá hiệu năng của hệ thống.
* Tối ưu kiến trúc Serverless và xử lý các lỗi còn tồn tại.
* Hoàn thiện tài liệu Workshop và báo cáo thực tập.
* Chuẩn bị nội dung phục vụ trình bày và nghiệm thu dự án.

### Nội dung thực hiện trong tuần:

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
<td>1</td>
<td>
• Rà soát toàn bộ mã nguồn của hệ thống ZeroBug Agent.<br>
• Kiểm tra lại cấu trúc dự án Backend và các AWS Lambda Functions.<br>
• Kiểm tra các biến môi trường (Environment Variables) của từng Lambda.<br>
• Đánh giá việc phân quyền IAM giữa AWS Lambda, Amazon S3, Amazon RDS, AWS Step Functions và Amazon Bedrock.<br>
• Chuẩn hóa tên tài nguyên AWS nhằm thuận tiện cho việc quản lý và bảo trì.<br>
• Cập nhật tài liệu mô tả kiến trúc hệ thống theo phiên bản triển khai thực tế.
</td>
<td>06/07/2026</td>
<td>06/07/2026</td>
<td>Tài liệu AWS, tài liệu dự án</td>
</tr>

<tr>
<td>2</td>
<td>
• Thực hiện kiểm thử tổng thể (System Testing).<br>
• Kiểm tra toàn bộ quy trình:<br>
&nbsp;&nbsp;+ Người dùng tải Project lên hệ thống.<br>
&nbsp;&nbsp;+ Backend tiếp nhận yêu cầu.<br>
&nbsp;&nbsp;+ Amazon SQS nhận Message.<br>
&nbsp;&nbsp;+ Lambda Trigger kích hoạt AWS Step Functions.<br>
&nbsp;&nbsp;+ Workflow thực hiện các Lambda Functions.<br>
&nbsp;&nbsp;+ Amazon Bedrock sinh Unit Test.<br>
&nbsp;&nbsp;+ Amazon S3 lưu kết quả.<br>
&nbsp;&nbsp;+ Amazon RDS lưu lịch sử.<br>
&nbsp;&nbsp;+ Backend trả kết quả về giao diện người dùng.<br>
• Kiểm tra tính chính xác của dữ liệu trong từng bước xử lý.<br>
• Ghi nhận các lỗi còn tồn tại để tiếp tục điều chỉnh.
</td>
<td>07/07/2026</td>
<td>07/07/2026</td>
<td>Tài liệu AWS, ZeroBug Agent</td>
</tr>

<tr>
<td>3</td>
<td>
• Theo dõi toàn bộ hệ thống bằng Amazon CloudWatch.<br>
• Kiểm tra CloudWatch Logs của từng Lambda Function.<br>
• Theo dõi Execution History trên AWS Step Functions.<br>
• Phân tích các lỗi Retry, Timeout và Exception phát sinh trong quá trình xử lý.<br>
• Điều chỉnh Memory Size và Timeout của các Lambda Functions nhằm tối ưu hiệu năng.<br>
• Kiểm tra khả năng xử lý nhiều yêu cầu liên tiếp của hệ thống.
</td>
<td>08/07/2026</td>
<td>08/07/2026</td>
<td>Tài liệu Amazon CloudWatch</td>
</tr>

<tr>
<td>4</td>
<td>
• Đánh giá hiệu năng của hệ thống khi xử lý nhiều Project khác nhau.<br>
• Thực hiện kiểm thử với các Project Java, Python và .NET có quy mô khác nhau.<br>
• So sánh thời gian xử lý của từng Project.<br>
• Kiểm tra khả năng đọc dữ liệu từ Amazon S3 và lưu kết quả vào Amazon RDS.<br>
• Đánh giá mức sử dụng tài nguyên của các dịch vụ AWS trong quá trình xử lý.<br>
• Ghi nhận các thông số phục vụ quá trình tối ưu hệ thống.
</td>
<td>09/07/2026</td>
<td>09/07/2026</td>
<td>Tài liệu AWS</td>
</tr>

<tr>
<td>5</td>
<td>
• Hoàn thiện tài liệu kỹ thuật của dự án.<br>
• Cập nhật sơ đồ kiến trúc Serverless theo phiên bản triển khai thực tế.<br>
• Hoàn thiện sơ đồ AWS Step Functions Workflow.<br>
• Bổ sung mô tả chức năng của từng AWS Lambda Function.<br>
• Hoàn thiện tài liệu hướng dẫn triển khai hệ thống trên AWS.<br>
• Kiểm tra tính thống nhất giữa tài liệu và hệ thống thực tế.
</td>
<td>10/07/2026</td>
<td>10/07/2026</td>
<td>Tài liệu dự án</td>
</tr>

<tr>
<td>6</td>
<td>
• Chuẩn bị nội dung báo cáo và Workshop.<br>
• Tổng hợp các hình ảnh minh họa trong quá trình triển khai.<br>
• Chuẩn bị hình ảnh về:<br>
&nbsp;&nbsp;+ AWS Lambda.<br>
&nbsp;&nbsp;+ Amazon SQS.<br>
&nbsp;&nbsp;+ AWS Step Functions.<br>
&nbsp;&nbsp;+ Amazon Bedrock.<br>
&nbsp;&nbsp;+ Amazon CloudWatch.<br>
&nbsp;&nbsp;+ Amazon S3.<br>
&nbsp;&nbsp;+ Amazon RDS.<br>
• Chuẩn bị nội dung trình bày về kiến trúc Serverless và quy trình sinh Unit Test.<br>
• Thực hiện chạy thử bài trình bày và điều chỉnh các nội dung cần thiết.
</td>
<td>11/07/2026</td>
<td>11/07/2026</td>
<td>Tài liệu Workshop</td>
</tr>

<tr>
<td>7</td>
<td>
• Thực hiện kiểm tra lần cuối toàn bộ hệ thống.<br>
• Đối chiếu các chức năng với yêu cầu ban đầu của dự án.<br>
• Kiểm tra khả năng hoạt động ổn định của Workflow trên AWS.<br>
• Dọn dẹp các tài nguyên AWS không còn sử dụng nhằm tránh phát sinh chi phí.<br>
• Tổng hợp toàn bộ kết quả thực hiện trong quá trình thực tập.<br>
• Hoàn thiện báo cáo thực tập, Worklog và tài liệu Workshop.<br>
• Chuẩn bị hồ sơ và các tài liệu phục vụ buổi nghiệm thu dự án.
</td>
<td>12/07/2026</td>
<td>12/07/2026</td>
<td>Tài liệu dự án</td>
</tr>

</tbody>
</table>

### Kết quả đạt được:

* Hoàn thiện hệ thống ZeroBug Agent theo kiến trúc Serverless trên nền tảng AWS.
* Kiểm thử thành công toàn bộ quy trình xử lý từ khi người dùng gửi yêu cầu đến khi hệ thống sinh và trả về Unit Test.
* Tối ưu cấu hình của AWS Lambda, AWS Step Functions và Amazon SQS nhằm nâng cao hiệu năng và độ ổn định của hệ thống.
* Hoàn thiện việc lưu trữ kết quả trên Amazon S3 và lịch sử xử lý trên Amazon RDS.
* Theo dõi và đánh giá hoạt động của hệ thống thông qua Amazon CloudWatch Logs và Execution History của AWS Step Functions.
* Hoàn thiện đầy đủ tài liệu kỹ thuật, sơ đồ kiến trúc, tài liệu Workshop và báo cáo thực tập.
* Dọn dẹp các tài nguyên AWS không còn sử dụng, đảm bảo tối ưu chi phí vận hành.
* Hoàn thành các mục tiêu thực tập, tích lũy thêm kiến thức và kinh nghiệm về kiến trúc Serverless, dịch vụ AWS và ứng dụng AI Generative trong quá trình phát triển hệ thống hỗ trợ sinh Unit Test tự động.