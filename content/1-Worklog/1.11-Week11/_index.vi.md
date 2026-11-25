---
title: "Báo cáo công việc Tuần 11"
date: 2026-11-23
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

> **Ghi chú:** Lịch công việc được sắp xếp lại từ phạm vi ông đã mô tả và source FE/BE ngày 25/11/2026; ngày thực hiện cụ thể cần xác nhận. Các mục sau 25/11 là kế hoạch, không phải kết quả đã hoàn thành.

### Mục tiêu tuần 11:

- Tinh chỉnh quy trình marketing và vận hành executive.
- Cải thiện tìm kiếm, lịch sử avatar và tính nhất quán giao diện.
- Lập kế hoạch kiểm tra hồi quy tích hợp và review code.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 (23/11) | **Quản lý khuyến mãi và coupon**<br>• Tinh chỉnh biểu mẫu chiến dịch, loại/mức giảm và chọn sản phẩm; tích hợp tải/cắt ảnh chiến dịch.<br>• Kết nối API coupon, promotion và thao tác publish, disable, archive; rà soát kiểm tra dữ liệu và phản hồi. | 23/11/2026 |  | `EcommercePromotionsPage.tsx`, `EcommerceCouponsPage.tsx`, `ExecutiveMarketingController.java` |
| Thứ 3 (24/11) | **Xử lý báo giá và kiểm duyệt đánh giá**<br>• Rà soát chi tiết báo giá, kiểm tra điều kiện và thao tác chấp nhận/từ chối theo API executive.<br>• Tinh chỉnh danh sách, kiểm duyệt/xóa đánh giá; rà soát giới hạn quản lý sản phẩm theo role và tính nhất quán song ngữ. | 24/11/2026 |  | `EcommerceQuotesPage.tsx`, `EcommerceReviewsPage.tsx`, `ExecutiveOperationsController.java` |
| Thứ 4 (25/11) | **Tìm kiếm, lịch sử avatar và hoàn thiện storefront**<br>• Rà soát gợi ý tìm kiếm có debounce, lịch sử tìm kiếm và điều hướng trên header.<br>• Phát triển khôi phục ảnh đại diện cũ và rà soát thông báo, quản lý đánh giá, khoảng cách UI và xử lý lỗi executive. | 25/11/2026 |  | `useStoreSearch.ts`, `CustomerProfileController.java`, `useExecutiveReviews.ts` |
| Thứ 5 (26/11) | **Dự kiến: rà soát tìm kiếm và hồi quy API**<br>• Kiểm tra chuẩn hóa dấu câu/khoảng trắng, thời điểm gửi request gợi ý và phản hồi cũ.<br>• Rà soát phản hồi API tìm kiếm, chi tiết sản phẩm, thông báo so với UI; ghi nhận lỗi. | 26/11/2026 |  | `useStoreSearch.ts`, `ProductController.java`, `NotificationController.java` |
| Thứ 6 (27/11) | **Dự kiến: kiểm tra hồi quy executive**<br>• Kiểm tra validation coupon/promotion, chuyển trạng thái, xử lý báo giá và đánh giá với đúng role.<br>• Rà soát thông báo lỗi, trạng thái trống/tải và tính nhất quán payload FE/BE. | 27/11/2026 |  | `executiveAdminService.ts`, `ExecutiveMarketingController.java`, `ExecutiveOperationsController.java` |
| Thứ 7 (28/11) | **Dự kiến: tích hợp và tài liệu**<br>• Rà soát nhãn song ngữ, khoảng cách responsive, layout chung và luồng khách hàng/executive.<br>• Ghi nhận vấn đề còn lại và chuẩn bị ghi chú review code cho nhóm. | 28/11/2026 |  | FE/BE project source; Git review |

### Kết quả tuần 11:

- Source có quy trình promotion/coupon, xử lý báo giá và quản lý đánh giá.
- Gợi ý/lịch sử tìm kiếm và khôi phục avatar được thể hiện trong code.
- Dự kiến sau 25/11: kiểm tra hồi quy và tài liệu; chưa xác nhận hoàn thành.
