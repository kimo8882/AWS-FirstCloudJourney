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
| Thứ 2 (28/09) | **Bảo mật tài khoản, ngân sách và hỗ trợ**<br>– **Lý thuyết:** Root MFA, quyền IAM, ngưỡng chi phí và các hình thức hỗ trợ.<br>– **Thực hành:**<br> + Kiểm tra MFA.<br> + cấu hình ngân sách mẫu có cảnh báo email.<br> + tìm hiểu cách tạo yêu cầu hỗ trợ. | 28/09/2026 |  | [Module 1 - 1: Tạo tài khoản AWS](https://000001.awsfcaj.com/)<br>[Module 1 - 2: AWS Budgets](https://000007.awsfcaj.com/)<br>[Module 1 - 3: AWS Support](https://000009.awsfcaj.com/) |
| Thứ 3 (29/09) | **IAM User, Group và Policy**<br>– **Lý thuyết:** Quyền dựa trên danh tính, managed policy và nguyên tắc đặc quyền tối thiểu.<br>– **Thực hành:**<br> + Tạo danh tính và nhóm thực hành có quyền giới hạn.<br> + gán policy phù hợp và kiểm tra quyền. | 29/09/2026 |  | [Module 1 - 4: Quản lý truy cập IAM](https://000002.awsfcaj.com/) |
| Thứ 4 (30/09) | **IAM Role và kiểm tra Policy**<br>– **Lý thuyết:** Trust policy, thông tin xác thực tạm thời và đánh giá quyền.<br>– **Thực hành:**<br> + Kiểm tra Effect, Action, Resource, Condition.<br> + so sánh thao tác được phép và bị từ chối bằng danh tính thử nghiệm hoặc Policy Simulator. | 30/09/2026 |  | [Module 1 - 4: Quản lý truy cập IAM](https://000002.awsfcaj.com/) |
| Thứ 5 (01/10) | **Thiết kế VPC và Subnet**<br>– **Lý thuyết:** CIDR, subnet public/private và Availability Zone.<br>– **Thực hành:**<br> + Lập sơ đồ VPC trên hai AZ, phân bổ các dải địa chỉ không chồng lấn. | 01/10/2026 |  | [Module 1 - 5: Mạng VPC](https://000003.awsfcaj.com/) |
| Thứ 6 (02/10) | **Định tuyến và kết nối VPC**<br>– **Lý thuyết:** Route Table, Internet Gateway, DNS và kết nối ra ngoài từ private subnet.<br>– **Thực hành:**<br> + Liên kết bảng định tuyến với subnet.<br> + cấu hình tuyến public.<br> + kiểm tra tuyến private và chi phí NAT Gateway. | 02/10/2026 |  | [Module 1 - 5: Mạng VPC](https://000003.awsfcaj.com/) |
| Thứ 7 (03/10) | **Bảo mật mạng và dọn tài nguyên**<br>– **Lý thuyết:** Security Group stateful và Network ACL stateless.<br>– **Thực hành:**<br> + Kiểm tra quy tắc inbound/outbound, xác minh định tuyến và xác định tài nguyên không dùng cần xóa. | 03/10/2026 |  | [Module 1 - 5: Mạng VPC](https://000003.awsfcaj.com/) |

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
