---
title: "Báo cáo công việc Tuần 6"
date: 2026-10-19
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

> **Bản dự thảo:** Lịch thực hành đề xuất dựa trên FCJ; chưa xác nhận đã thực hiện. Các mục kết quả là mục tiêu dự kiến.

### Mục tiêu tuần 6:

- **Giám sát:** Tìm hiểu CloudWatch alarm và thông báo.
- **DNS lai:** Tìm hiểu Route 53 Resolver và chuyển tiếp giữa các mạng.
- **CLI và tính sẵn sàng:** Thực hành CLI dùng role và tìm hiểu kiến trúc multi-AZ.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 (19/10) | **Cảnh báo và thông báo CloudWatch**<br>• Cấu hình metric alarm mẫu và đích nhận thông báo; tìm hiểu trạng thái alarm và dọn tài nguyên sau khi kiểm tra.<br>• Thực hành: chọn metric, ngưỡng và chu kỳ đánh giá; xem gửi thông báo qua SNS topic nếu cần.<br>• Kiểm tra: xem trạng thái OK, ALARM, INSUFFICIENT_DATA và lịch sử alarm. | 19/10/2026 |  | [Module 1 - 13: Amazon CloudWatch](https://000008.awsfcaj.com/) |
| Thứ 3 (20/10) | **Chuẩn bị DNS lai**<br>• Tìm hiểu cách DNS on-premises tích hợp với DNS trong VPC; xem môi trường lab, lưu lượng DNS và yêu cầu bảo mật.<br>• Lý thuyết: phân biệt DNS public, phân giải tên trong VPC private và chuyển tiếp DNS lai.<br>• Chuẩn bị: lập sơ đồ mạng local mô phỏng, VPC, DNS server và yêu cầu kết nối port 53. | 20/10/2026 |  | [Module 1 - 14: DNS lai Route 53](https://000010.awsfcaj.com/) |
| Thứ 4 (21/10) | **Route 53 Resolver**<br>• Tìm hiểu Resolver endpoint inbound/outbound và quy tắc chuyển tiếp; lên bài kiểm thử phân giải DNS hai chiều và dọn tài nguyên.<br>• Thực hành: xem thiết kế Resolver endpoint inbound/outbound và rule chuyển tiếp có điều kiện.<br>• Kiểm tra: lập kế hoạch kiểm thử phân giải tên hai chiều và xem phí endpoint theo giờ trước khi dọn. | 21/10/2026 |  | [Module 1 - 14: DNS lai Route 53](https://000010.awsfcaj.com/) |
| Thứ 5 (22/10) | **AWS CLI trên EC2**<br>• Tìm hiểu cài CLI trên EC2 Windows/Linux và dùng quyền từ instance role; kiểm tra danh tính và Region.<br>• Thực hành: xem cài AWS CLI cho EC2 Windows và Ubuntu; tìm hiểu chuỗi nguồn credential.<br>• Kiểm tra: dùng credential từ role và so sánh danh tính/Region với console. | 22/10/2026 |  | [Module 1 - 15: AWS CLI trên EC2](https://000011.awsfcaj.com/) |
| Thứ 6 (23/10) | **Thao tác tài nguyên bằng CLI**<br>• Thực hành liệt kê và lọc tài nguyên EC2, S3; so sánh kết quả CLI với console và xem lệnh dọn tài nguyên an toàn.<br>• Thực hành: dùng lệnh describe/list, filter và output format để xem EC2 và S3.<br>• An toàn: xác nhận tài khoản và Region trước lệnh thay đổi tài nguyên, xác định tài nguyên không dùng. | 23/10/2026 |  | [Module 1 - 15: AWS CLI trên EC2](https://000011.awsfcaj.com/) |
| Thứ 7 (24/10) | **Thiết kế ứng dụng sẵn sàng cao**<br>• Tìm hiểu kiến trúc web multi-AZ và xác định các thành phần VPC, compute, database, cân bằng tải và lưu trữ.<br>• Lý thuyết: theo dõi request từ load balancer đến tầng ứng dụng và cơ sở dữ liệu.<br>• Thiết kế: xác định điểm lỗi đơn, dự phòng AZ và vai trò health check. | 24/10/2026 |  | [Module 1 - 16: Ứng dụng web có tính sẵn sàng cao](https://000021.awsfcaj.com/) |

### Kết quả tuần 6:

*Các kết quả dự kiến, chờ xác nhận thực tế.*

- **Giám sát và cảnh báo:**
    - Mô tả ngưỡng alarm, chu kỳ đánh giá và gửi thông báo.
    - Giải thích các trạng thái alarm CloudWatch thường gặp.
- **Mạng lai:**
    - Giải thích Resolver endpoint inbound/outbound và chuyển tiếp có điều kiện.
    - Xác định yêu cầu kết nối DNS và lưu ý chi phí endpoint.
- **CLI và kiến trúc:**
    - Mô tả CLI dùng role và lọc tài nguyên.
    - Theo dõi request qua kiến trúc ứng dụng multi-AZ.
