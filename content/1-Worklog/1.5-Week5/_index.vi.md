---
title: "Worklog Tuần 5"
date: 2026-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Tìm hiểu dịch vụ lưu trữ đối tượng Amazon S3 trên nền tảng AWS.
* Thực hành tạo và quản lý Amazon S3 Bucket phục vụ lưu trữ dữ liệu.
* Triển khai Static Website Hosting bằng Amazon S3.
* Nghiên cứu cơ chế phân phối nội dung thông qua Amazon CloudFront.
* Tìm hiểu các tính năng quản lý dữ liệu và bảo mật như Bucket Policy, Versioning và Object Ownership.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|------|-----------|--------------|-----------------|----------------|
|18/05|Tìm hiểu tổng quan về Amazon S3, mô hình Object Storage, các khái niệm Bucket, Object, Key, Prefix, Storage Class; so sánh Object Storage, File Storage và Block Storage; nghiên cứu các Storage Classes và các trường hợp ứng dụng của Amazon S3.|18/05/2026|18/05/2026|AWS Documentation|
|19/05|Tạo Amazon S3 Bucket, cấu hình Region, Object Ownership, Block Public Access, Default Encryption (SSE-S3, SSE-KMS), kiểm tra các thông số sau khi tạo Bucket.|19/05/2026|19/05/2026|Cloud Journey|
|20/05|Chuẩn bị mã nguồn website tĩnh, upload HTML, CSS, JavaScript, hình ảnh lên S3 Bucket; tìm hiểu upload bằng AWS Console và AWS CLI; kiểm tra cập nhật Object và trạng thái lưu trữ.|20/05/2026|20/05/2026|Cloud Journey|
|21/05|Kích hoạt Static Website Hosting, cấu hình Index Document, Error Document, Bucket Policy, Block Public Access; kiểm tra S3 Website Endpoint và xử lý lỗi 403, 404.|21/05/2026|21/05/2026|AWS Documentation|
|22/05|Kiểm thử website sau triển khai, kiểm tra khả năng hiển thị, tốc độ truy cập, phân tích luồng truy cập và đánh giá ưu, nhược điểm của việc triển khai website trên Amazon S3.|22/05/2026|22/05/2026|AWS Documentation|
|23/05|Thực hiện Lab Accelerate Static Websites with Amazon CloudFront. Tạo CloudFront Distribution, cấu hình S3 Bucket làm Origin, thiết lập Cache Behavior, Viewer Protocol Policy, kiểm tra hiệu năng giữa S3 Website Endpoint và CloudFront.|23/05/2026|23/05/2026|Cloud Journey|
|24/05|Kích hoạt Bucket Versioning, thực hiện cập nhật nhiều phiên bản Object, Restore dữ liệu, tìm hiểu vai trò của Versioning, dọn dẹp tài nguyên, kiểm tra AWS Billing Dashboard và tổng kết kiến thức trong tuần.|24/05/2026|24/05/2026|AWS Documentation|

### Kết quả đạt được tuần 5:

* Hiểu nguyên lý hoạt động của Amazon S3 và mô hình Object Storage.
* Tạo và quản lý Amazon S3 Bucket theo các khuyến nghị bảo mật của AWS.
* Triển khai thành công Static Website Hosting trên Amazon S3.
* Thành thạo quy trình upload, quản lý và cập nhật Object.
* Cấu hình thành công Amazon CloudFront Distribution để tăng tốc độ truy cập website.
* Hiểu cơ chế hoạt động của CDN và lợi ích của Amazon CloudFront.
* Thực hành thành công Bucket Versioning và khôi phục các phiên bản dữ liệu.
* Củng cố kiến thức về lưu trữ, bảo mật và phân phối nội dung trên nền tảng AWS.