---
title: "Báo cáo công việc Tuần 8"
date: 2026-11-02
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

> **Ghi chú:** Lịch công việc được sắp xếp lại từ phạm vi ông đã mô tả và source FE/BE ngày 25/11/2026; ngày thực hiện cụ thể cần xác nhận. Các mục sau 25/11 là kế hoạch, không phải kết quả đã hoàn thành.

Ngày 01/11 là Chủ nhật; không có công việc cụ thể được cung cấp cho ngày này.

Chi tiết Figma được mô tả theo phạm vi đã cung cấp và giao diện trong source; chưa đối chiếu trực tiếp file Figma.

### Mục tiêu tuần 8:

- Xác định định hướng giao diện và điều hướng storefront B2B.
- Thiết kế trang khách hàng và workspace nhân viên trên Figma.
- Thiết lập mẫu giao diện tái sử dụng trước khi phát triển.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 (02/11) | **Khảo sát và phác thảo trang chủ**<br>• Phân tích hành trình mua hàng B2B và xác định thứ tự nội dung trang chủ.<br>• Thiết kế banner coverflow, điều hướng danh mục, dải thương hiệu và các nhóm sản phẩm. | 02/11/2026 |  | Figma; `HomePage.tsx`, `CoverflowSlider.tsx` |
| Thứ 3 (03/11) | **Trang chi tiết sản phẩm**<br>• Thiết kế thư viện ảnh, mô tả, thông số và khu vực mua hàng.<br>• Bố trí giá theo số lượng, chọn số lượng, đánh giá, sản phẩm liên quan và trạng thái tải/không khả dụng. | 03/11/2026 |  | Figma; `CustomerProductDetailPage.tsx`, `CustomerProductPurchase.tsx` |
| Thứ 4 (04/11) | **Hồ sơ và thông báo khách hàng**<br>• Thiết kế sidebar tài khoản, biểu mẫu hồ sơ và tương tác chọn/cắt ảnh đại diện.<br>• Thiết kế dropdown thông báo, chỉ báo chưa đọc, xem chi tiết và tùy chọn thông báo. | 04/11/2026 |  | Figma; `ProfilePage.tsx`, `NotificationSystem.tsx` |
| Thứ 5 (05/11) | **Giao diện nhân viên giao hàng**<br>• Thiết kế điều hướng giao hàng, tổng quan chuyến hiện tại và màn hình chi tiết kiện hàng.<br>• Bố trí bản đồ/tuyến đường, lịch sử giao hàng và chỉ báo trạng thái cho quy trình tài xế. | 05/11/2026 |  | Figma; `CurrentTripPage.tsx`, `DeliveryHistoryPage.tsx`, `DeliveryPackagePage.tsx` |
| Thứ 6 (06/11) | **Giao diện nhân viên logistics**<br>• Thiết kế tổng quan tồn kho, bảng hàng tồn và giao diện nhập hàng.<br>• Phác thảo màn hình yêu cầu sản phẩm, điều hướng kho và rà soát mật độ thông tin. | 06/11/2026 |  | Figma; `InventoryPage.tsx`, `ReceivePage.tsx`, `ProductRequestsPage.tsx` |
| Thứ 7 (07/11) | **Giao diện E-commerce và bố cục dùng chung**<br>• Thiết kế dashboard, quản lý danh mục, khuyến mãi, coupon, báo giá và đánh giá.<br>• Xây dựng header/footer, tìm kiếm, điều hướng tài khoản, khoảng cách và phong cách component dùng chung; rà soát thiết kế trước khi chuyển sang code. | 07/11/2026 |  | Figma; `EcommerceLayout.tsx`, `Header.tsx`, `Footer.tsx` |

### Kết quả tuần 8:

- Phạm vi Figma: trang chủ, chi tiết sản phẩm, hồ sơ và thông báo.
- Phạm vi nhân viên: giao diện shipper, logistics và workspace E-commerce.
- Bố cục chung: header, footer, điều hướng và mẫu component nhất quán.
