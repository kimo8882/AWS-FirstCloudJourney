---
title: "Báo cáo công việc Tuần 7"
date: 2026-10-26
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

> **Bản dự thảo:** Lịch thực hành đề xuất dựa trên FCJ; chưa xác nhận đã thực hiện. Các mục kết quả là mục tiêu dự kiến.

### Mục tiêu tuần 7:

- **Kiến trúc nhiều tầng:** Tổng hợp dịch vụ mạng, ứng dụng và database.
- **Phục hồi và vận hành:** Ôn cân bằng tải, health check, backup và giám sát.
- **Tổng kết nền tảng:** Ôn 16 module, xác định tài nguyên cần dọn và phần học còn lại.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 (26/10) | **Ứng dụng sẵn sàng cao: mạng**<br>• Chuẩn bị mạng cho ứng dụng mẫu gồm nhiều Availability Zone, bố trí subnet và security group theo từng tầng.<br>• Thực hành: lập kế hoạch subnet public cho load balancer và subnet ứng dụng/database qua hai AZ.<br>• Kiểm tra: xem cấp CIDR, liên kết route table và rule security group giữa các tầng. | 26/10/2026 |  | [Module 1 - 16: Ứng dụng web có tính sẵn sàng cao](https://000021.awsfcaj.com/) |
| Thứ 3 (27/10) | **Ứng dụng sẵn sàng cao: ứng dụng và dữ liệu**<br>• Tìm hiểu triển khai ứng dụng web mẫu trên EC2, kết nối RDS và phân quyền truy cập ứng dụng.<br>• Thực hành: xem cấu hình ứng dụng và kết nối database endpoint; không đưa credential vào mã nguồn.<br>• Kiểm tra: lập kế hoạch health check ứng dụng mẫu và thử đọc/ghi database cơ bản. | 27/10/2026 |  | [Module 1 - 16: Ứng dụng web có tính sẵn sàng cao](https://000021.awsfcaj.com/) |
| Thứ 4 (28/10) | **Ứng dụng sẵn sàng cao: phân phối lưu lượng**<br>• Tìm hiểu đăng ký target, health check của Application Load Balancer và cấu hình Auto Scaling cho tầng web.<br>• Thực hành: xem ALB listener, target group, health check path và thiết lập Auto Scaling group.<br>• Kiểm tra: tìm hiểu cách traffic được chuyển tới target khỏe mạnh ở nhiều AZ. | 28/10/2026 |  | [Module 1 - 16: Ứng dụng web có tính sẵn sàng cao](https://000021.awsfcaj.com/) |
| Thứ 5 (29/10) | **Ứng dụng sẵn sàng cao: khả năng phục hồi**<br>• Lên bài kiểm tra instance lỗi và khả năng phục hồi database multi-AZ; tìm hiểu quy trình backup và restore.<br>• Lý thuyết: phân biệt availability, fault tolerance và disaster recovery.<br>• Kiểm tra: lập kế hoạch tình huống thay target lỗi, xem RDS Multi-AZ failover và backup/restore. | 29/10/2026 |  | [Module 1 - 16: Ứng dụng web có tính sẵn sàng cao](https://000021.awsfcaj.com/) |
| Thứ 6 (30/10) | **Ôn kiến trúc và quản lý chi phí**<br>• Ôn luồng request, phân quyền, giám sát và các khoản chi phí có thể phát sinh từ kiến trúc thực hành.<br>• Ôn tập: đối chiếu tín hiệu giám sát, quyền role và quyền truy cập mạng với luồng request.<br>• Chi phí: ước tính các thành phần tính phí chính, xem cảnh báo budget và thứ tự dọn tài nguyên. | 30/10/2026 |  | [Module 1 - 2: AWS Budgets](https://000007.awsfcaj.com/) <br> [Module 1 - 4: Quản lý truy cập IAM](https://000002.awsfcaj.com/) <br> [Module 1 - 13: Amazon CloudWatch](https://000008.awsfcaj.com/) <br> [Module 1 - 16: Ứng dụng web có tính sẵn sàng cao](https://000021.awsfcaj.com/) |
| Thứ 7 (31/10) | **Tổng kết Explore AWS Services**<br>• Ôn đủ 16 chủ đề workshop, ghi lại kiến thức chính và các vấn đề còn vướng, kiểm tra tài nguyên phát sinh phí cần dọn.<br>• Tổng hợp: phân nhóm 16 workshop thành tài khoản/chi phí, IAM, mạng, compute, lưu trữ, database, giám sát và khả năng phục hồi.<br>• Ôn tập: ghi câu hỏi còn lại và kiểm tra tài nguyên có thể tiếp tục phát sinh phí. | 31/10/2026 |  | [Module 1 - 16: Ứng dụng web có tính sẵn sàng cao](https://000021.awsfcaj.com/) <br> [Explore AWS Services](https://cloudjourney.awsfcaj.com/1-explore/) |

### Kết quả tuần 7:

*Các kết quả dự kiến, chờ xác nhận thực tế.*

- **Kiến trúc nhiều tầng:**
    - Giải thích cô lập mạng, kết nối ứng dụng và vị trí database.
    - Theo dõi định tuyến ALB và đăng ký target Auto Scaling.
- **Khả năng phục hồi và vận hành:**
    - Xác định health check, thay target lỗi và database failover.
    - Mô tả backup, restore, giám sát và kiểm tra quyền.
- **Tổng hợp nền tảng:**
    - Tóm tắt 16 workshop Explore AWS Services theo nhóm dịch vụ.
    - Xác định phần thực hành còn lại, rủi ro chi phí và ưu tiên dọn tài nguyên.
