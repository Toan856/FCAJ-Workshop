---
title: "Worklog Tuần 3"
date: 2026-01-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3

* Tiếp tục nghiên cứu và thực hành các bài Lab trên nền tảng AWS.
* Tìm hiểu dịch vụ quản lý danh tính và phân quyền (IAM) trên AWS.
* Nghiên cứu kiến trúc mạng AWS thông qua Virtual Private Cloud (VPC).
* Thực hành triển khai Amazon EC2 và cấu hình kết nối mạng.
* Tìm hiểu cơ chế kết nối Site-to-Site VPN giữa hệ thống nội bộ và AWS Cloud.

### Các công việc cần triển khai trong tuần này

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|------|-----------|--------------|-----------------|----------------|
|04/05|Thực hiện Lab **Create IAM Group and IAM User**. Tìm hiểu vai trò của IAM, tạo Admin Group, Admin User, gán quyền AdministratorAccess và thực hành đăng nhập bằng IAM User thay vì Root User. So sánh Root User và IAM User, đồng thời tìm hiểu nguyên tắc Least Privilege.|04/05/2026|04/05/2026|Cloud Journey|
|05/05|Thực hiện Lab **Create IAM Role and IAM User**. Nghiên cứu IAM Role, tạo IAM Role AdministratorAccess, tạo OperatorUser và tìm hiểu mô hình phân quyền RBAC.|05/05/2026|05/05/2026|Cloud Journey|
|06/05|Thực hiện Lab **Switch Role**. Cấu hình OperatorUser chuyển đổi Role, thực hành Switch Role, tìm hiểu Assume Role và AWS STS, đánh giá lợi ích của IAM Role.|06/05/2026|06/05/2026|Cloud Journey|
|07/05|Nghiên cứu Amazon VPC, Security Group, Network ACL, cấu hình Security Group cho SSH và HTTP, tìm hiểu VPC Resource Map.|07/05/2026|07/05/2026|AWS Documentation|
|08/05|Chuẩn bị hạ tầng mạng: tạo VPC, Public Subnet, Internet Gateway, Route Table, Security Group, bật VPC Flow Logs và kiểm tra kết nối mạng.|08/05/2026|08/05/2026|AWS Documentation|
|09/05|Thực hiện Lab **Deploying Amazon EC2 Instances**. Khởi tạo EC2, cấu hình Key Pair, kết nối EC2, giám sát bằng CloudWatch, sử dụng Reachability Analyzer và tìm hiểu NAT Gateway.|09/05/2026|09/05/2026|Cloud Journey|
|10/05|Thực hiện Lab **Setting Up Site-to-Site VPN Connection in AWS**. Tạo CGW, VGW, VPN Connection, cấu hình VPN Tunnel, kiểm tra kết nối và tổng hợp kiến thức.|10/05/2026|10/05/2026|AWS Documentation|

### Kết quả đạt được tuần 3

* Hiểu rõ vai trò của AWS IAM trong quản lý người dùng và phân quyền.
* Thực hành thành công tạo IAM User, IAM Group và IAM Role.
* Nắm được cơ chế Switch Role, Assume Role và AWS STS.
* Hiểu kiến trúc Amazon VPC gồm VPC, Subnet, Route Table, Internet Gateway, Security Group và Network ACL.
* Triển khai thành công Amazon EC2 và giám sát bằng Amazon CloudWatch.
* Tìm hiểu NAT Gateway, Reachability Analyzer và AWS Systems Manager.
* Thiết lập mô hình Site-to-Site VPN giữa hệ thống nội bộ và Amazon VPC.
* Củng cố kiến thức về quản trị hạ tầng, bảo mật và mạng trên AWS.