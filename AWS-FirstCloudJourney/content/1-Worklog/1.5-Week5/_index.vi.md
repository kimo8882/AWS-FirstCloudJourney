---
title: "Báo cáo công việc Tuần 5"
date: 2026-10-12
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

> **Bản dự thảo:** Lịch thực hành đề xuất dựa trên FCJ; chưa xác nhận đã thực hiện. Các mục kết quả là mục tiêu dự kiến.

### Mục tiêu tuần 5:

- **Dịch vụ database:** Tìm hiểu kết nối RDS private, backup và khả năng phục hồi.
- **Compute co giãn:** So sánh Lightsail và EC2; tìm hiểu scaling và cân bằng tải.
- **Giám sát:** Ôn tín hiệu giám sát CloudWatch và chi phí.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 (12/10) | **Mạng và thiết lập RDS**<br>• Chuẩn bị DB subnet group và security group; tìm hiểu database engine, instance class và cấu hình truy cập riêng tư.<br>• Lý thuyết: so sánh RDS được quản lý với tự cài cơ sở dữ liệu trên EC2.<br>• Thực hành: chọn database engine, private subnet group và security group chỉ cho ứng dụng lab truy cập. | 12/10/2026 |  | [Module 1 - 10: Cơ sở dữ liệu RDS](https://000005.awsfcaj.com/) |
| Thứ 3 (13/10) | **Kết nối và sao lưu RDS**<br>• Kiểm thử kết nối database từ môi trường ứng dụng, thực hành truy vấn cơ bản và tìm hiểu snapshot, Multi-AZ.<br>• Thực hành: xem database endpoint và port, kết nối từ môi trường ứng dụng và chạy truy vấn đơn giản.<br>• Kiểm tra: xem thời hạn backup, snapshot thủ công và đánh đổi khi triển khai Multi-AZ. | 13/10/2026 |  | [Module 1 - 10: Cơ sở dữ liệu RDS](https://000005.awsfcaj.com/) |
| Thứ 4 (14/10) | **Amazon Lightsail**<br>• Tìm hiểu gói chi phí tính toán; lên cấu hình triển khai web nhỏ, xem firewall và so sánh Lightsail với EC2.<br>• Lý thuyết: so sánh gói Lightsail với hạ tầng EC2 có thể tùy chỉnh.<br>• Thực hành: xem blueprint instance mẫu, thiết lập mạng/firewall, public IP và chi phí tháng dự kiến. | 14/10/2026 |  | [Module 1 - 11: Amazon Lightsail](https://000045.awsfcaj.com/) |
| Thứ 5 (15/10) | **Thiết lập EC2 Auto Scaling**<br>• Chuẩn bị launch template và target group; tìm hiểu desired, minimum và maximum capacity của Auto Scaling group.<br>• Thực hành: định nghĩa EC2 launch template và cấu hình Auto Scaling group qua hai AZ.<br>• Ôn tập: liên kết group với target group và xem min, desired, max capacity. | 15/10/2026 |  | [Module 1 - 12: EC2 Auto Scaling](https://000006.awsfcaj.com/) |
| Thứ 6 (16/10) | **Co giãn và cân bằng tải**<br>• Tìm hiểu target tracking policy và health check của load balancer; lên bài kiểm thử scaling có kiểm soát và kiểm tra thay thế instance.<br>• Lý thuyết: phân biệt target tracking với scaling thủ công và hiểu cơ chế thay instance lỗi.<br>• Kiểm tra: chuẩn bị tải thử nhỏ có kiểm soát, xem target health và lịch sử scaling. | 16/10/2026 |  | [Module 1 - 12: EC2 Auto Scaling](https://000006.awsfcaj.com/) |
| Thứ 7 (17/10) | **Giám sát CloudWatch**<br>• Tìm hiểu metric EC2 và log group; chuẩn bị dashboard và xác định metric hữu ích để giám sát ứng dụng.<br>• Lý thuyết: phân biệt CloudWatch metrics, logs và dashboard.<br>• Thực hành: xác định CPUUtilization, network metrics và tín hiệu log ứng dụng; xem retention và chi phí dashboard. | 17/10/2026 |  | [Module 1 - 13: Amazon CloudWatch](https://000008.awsfcaj.com/) |

### Kết quả tuần 5:

*Các kết quả dự kiến, chờ xác nhận thực tế.*

- **Cơ sở dữ liệu được quản lý:**
    - Giải thích yêu cầu subnet và bảo mật RDS.
    - Mô tả kết nối endpoint, snapshot và tùy chọn Multi-AZ.
- **Chi phí compute và co giãn:**
    - So sánh giá gói Lightsail với EC2.
    - Giải thích launch template, scaling capacity và target health check.
- **Khả năng quan sát:**
    - Phân biệt CloudWatch metrics, logs và dashboard.
    - Xác định tín hiệu giám sát ứng dụng và lưu ý chi phí.
