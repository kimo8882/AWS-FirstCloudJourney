---
title: "Báo cáo công việc Tuần 3"
date: 2026-09-28
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

> **Bản dự thảo:** Lịch thực hành đề xuất dựa trên FCJ; chưa xác nhận đã thực hiện. Các mục kết quả là mục tiêu dự kiến.

### Mục tiêu tuần 3:

- **Quản trị tài khoản:** Ôn MFA, thông báo ngân sách và quy trình hỗ trợ.
- **Phân quyền IAM:** Tìm hiểu identity policy, role policy và kiểm tra quyền tối thiểu.
- **Kiến trúc mạng:** Thiết kế subnet, route và kiểm soát truy cập VPC.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 (28/09) | **Bảo mật tài khoản và chi phí**<br>• Ôn MFA cho root và quyền truy cập; cấu hình ngân sách mẫu với cảnh báo email và tìm hiểu quy trình yêu cầu hỗ trợ.<br>• Lý thuyết: phân biệt quyền root và IAM, chi phí thực tế và dự báo, mục đích các gói hỗ trợ.<br>• Thực hành: kiểm tra MFA; đặt ngưỡng ngân sách và người nhận thông báo mẫu; xem trang billing và support. | 28/09/2026 |  | [Module 1 - 1: Tạo tài khoản AWS](https://000001.awsfcaj.com/) <br> [Module 1 - 2: AWS Budgets](https://000007.awsfcaj.com/) <br> [Module 1 - 3: AWS Support](https://000009.awsfcaj.com/) |
| Thứ 3 (29/09) | **Danh tính và quyền IAM**<br>• Tạo danh tính IAM và group trong lab; so sánh managed policy với custom policy và áp dụng quyền tối thiểu.<br>• Lý thuyết: so sánh policy dựa trên danh tính và quyền tạm thời qua role.<br>• Thực hành: cấu hình danh tính lab giới hạn, gán policy và xem quyền có hiệu lực. | 29/09/2026 |  | [Module 1 - 4: Quản lý truy cập IAM](https://000002.awsfcaj.com/) |
| Thứ 4 (30/09) | **Kiểm thử IAM Policy**<br>• Đọc các statement và trust relationship của role; kiểm thử thao tác được phép và bị từ chối trong lab.<br>• Thực hành: đọc Effect, Action, Resource và Condition; so sánh trust policy với permissions policy của role.<br>• Kiểm tra: dùng IAM policy simulator hoặc danh tính lab để so sánh yêu cầu được phép và bị từ chối. | 30/09/2026 |  | [Module 1 - 4: Quản lý truy cập IAM](https://000002.awsfcaj.com/) |
| Thứ 5 (01/10) | **Kiến trúc VPC**<br>• Thiết kế CIDR cho VPC và subnet public/private không trùng lặp tại các Availability Zone.<br>• Lý thuyết: phân biệt CIDR, Region và Availability Zone.<br>• Thực hành: phác thảo VPC hai AZ và cấp dải địa chỉ public/private không trùng nhau. | 01/10/2026 |  | [Module 1 - 5: Mạng VPC](https://000003.awsfcaj.com/) |
| Thứ 6 (02/10) | **Định tuyến và kết nối VPC**<br>• Cấu hình route table và Internet Gateway; tìm hiểu kết nối ra ngoài của private subnet và thiết lập DNS.<br>• Thực hành: liên kết route table với subnet, thêm route internet cho public subnet và kiểm tra route private subnet.<br>• Kiểm tra: xem đích định tuyến, thiết lập DNS và chi phí NAT Gateway có thể phát sinh. | 02/10/2026 |  | [Module 1 - 5: Mạng VPC](https://000003.awsfcaj.com/) |
| Thứ 7 (03/10) | **Bảo mật và kiểm tra mạng**<br>• Tìm hiểu security group và network ACL; kiểm tra kết nối và dọn tài nguyên mạng lab không dùng.<br>• Lý thuyết: so sánh security group stateful và network ACL stateless.<br>• Kiểm tra: xem rule inbound/outbound và xác định tài nguyên mạng không cần thiết để dọn sau lab. | 03/10/2026 |  | [Module 1 - 5: Mạng VPC](https://000003.awsfcaj.com/) |

### Kết quả tuần 3:

*Các kết quả dự kiến, chờ xác nhận thực tế.*

- **Quản trị tài khoản:**
    - Mô tả MFA, ngưỡng budget và cách gửi cảnh báo.
    - Xác định quy trình AWS Support phù hợp.
- **Bảo mật IAM:**
    - Phân biệt identity policy và role trust policy.
    - Giải thích cách kiểm tra quyền tối thiểu qua thao tác được phép và bị từ chối.
- **Mạng VPC:**
    - Thiết kế dải subnet không trùng và giải thích liên kết route table.
    - So sánh security group với network ACL và xác định bước dọn mạng.
