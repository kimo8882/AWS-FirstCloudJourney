---
title: "Báo cáo công việc Tuần 4"
date: 2026-10-05
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

> **Bản dự thảo:** Lịch thực hành đề xuất dựa trên FCJ; chưa xác nhận đã thực hiện. Các mục kết quả là mục tiêu dự kiến.

### Mục tiêu tuần 4:

- **Triển khai EC2:** Tìm hiểu cấp phát instance và kết nối ứng dụng.
- **Credential an toàn:** Tìm hiểu IAM role cho ứng dụng và CloudShell.
- **Hosting tĩnh:** Cấu hình và đánh giá website tĩnh S3 cùng quyền truy cập.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 (05/10) | **Thiết lập EC2**<br>• Chọn AMI và instance type; khởi tạo instance thử nghiệm với key pair và security group phù hợp.<br>• Lý thuyết: so sánh AMI, instance type, EBS root volume và key pair.<br>• Thực hành: chọn subnet lab, gắn security group giới hạn và kiểm tra trạng thái instance. | 05/10/2026 |  | [Module 1 - 6: Triển khai ứng dụng EC2](https://000004.awsfcaj.com/) |
| Thứ 3 (06/10) | **Triển khai ứng dụng mẫu trên EC2**<br>• Kết nối an toàn đến instance, cài web server, triển khai trang mẫu và kiểm tra phản hồi.<br>• Thực hành: kết nối qua SSH hoặc Systems Manager phù hợp, cài web server và tạo trang index mẫu.<br>• Kiểm tra: xem phản hồi HTTP, trạng thái dịch vụ và rule security group nếu lỗi kết nối. | 06/10/2026 |  | [Module 1 - 6: Triển khai ứng dụng EC2](https://000004.awsfcaj.com/) |
| Thứ 4 (07/10) | **IAM Role cho ứng dụng EC2**<br>• Tạo EC2 role có quyền giới hạn, gắn instance profile và kiểm thử quyền bằng thông tin xác thực tạm thời.<br>• Thực hành: gán IAM role có quyền S3 giới hạn cho EC2.<br>• Kiểm tra: xem caller identity và so sánh thao tác được cấp quyền với thao tác ngoài phạm vi policy. | 07/10/2026 |  | [Module 1 - 7: Phân quyền ứng dụng bằng IAM Role](https://000048.awsfcaj.com/) |
| Thứ 5 (08/10) | **AWS CLI trên trình duyệt**<br>• Tìm hiểu lab Cloud9 và dùng phiên bản CloudShell đã cập nhật; thực hành lệnh shell và AWS CLI cơ bản.<br>• Lý thuyết: tìm hiểu shell trên trình duyệt và khác biệt so với cài CLI cục bộ.<br>• Thực hành: chạy lệnh kiểm tra danh tính, liệt kê tài nguyên trên CloudShell mà không nhúng access key vào mã nguồn. | 08/10/2026 |  | [Module 1 - 8: CloudShell (lab Cloud9 đã cập nhật)](https://000049.awsfcaj.com/) <br> [AWS Cloud9 notice](https://aws.amazon.com/cloud9/getting-started/) |
| Thứ 6 (09/10) | **Website tĩnh Amazon S3**<br>• Tạo bucket lab, tải tệp HTML mẫu và tìm hiểu cấu hình static website hosting.<br>• Thực hành: tạo bucket lab tên duy nhất, tải index và trang lỗi, xem thiết lập website hosting.<br>• Lý thuyết: so sánh truy cập object qua S3 API endpoint và static website endpoint. | 09/10/2026 |  | [Module 1 - 9: Website tĩnh S3](https://000057.awsfcaj.com/) |
| Thứ 7 (10/10) | **Kiểm thử truy cập S3**<br>• Kiểm tra quyền truy cập bucket, thử website endpoint theo cấu hình lab và dọn tài nguyên thử nghiệm công khai.<br>• Kiểm tra: xem Block Public Access và bucket policy trước khi mở quyền public chỉ cho lab; kiểm thử endpoint.<br>• Dọn dẹp: xóa object thử nghiệm public và cấu hình bucket khi kết thúc. | 10/10/2026 |  | [Module 1 - 9: Website tĩnh S3](https://000057.awsfcaj.com/) |

### Kết quả tuần 4:

*Các kết quả dự kiến, chờ xác nhận thực tế.*

- **EC2 và triển khai ứng dụng:**
    - Giải thích lựa chọn AMI, instance type, storage và mạng.
    - Mô tả triển khai web server và kiểm tra kết nối HTTP.
- **Truy cập ứng dụng an toàn:**
    - Giải thích credential tạm thời từ instance role và kiểm tra quyền.
    - Sử dụng CloudShell như lựa chọn CLI trên trình duyệt trong lab dự kiến.
- **Hosting tĩnh:**
    - Mô tả S3 website hosting và phân biệt website endpoint với API endpoint.
    - Ôn bảo vệ quyền public và dọn lab.
