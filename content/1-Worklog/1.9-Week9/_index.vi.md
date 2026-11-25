---
title: "Báo cáo công việc Tuần 9"
date: 2026-11-09
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

> **Ghi chú:** Lịch công việc được sắp xếp lại từ phạm vi ông đã mô tả và source FE/BE ngày 25/11/2026; ngày thực hiện cụ thể cần xác nhận. Các mục sau 25/11 là kế hoạch, không phải kết quả đã hoàn thành.

### Mục tiêu tuần 9:

- Chuyển thiết kế storefront thành component React.
- Phát triển và tích hợp API homepage, danh mục và thương hiệu.
- Kết nối khám phá sản phẩm và thao tác khách hàng với dữ liệu động.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 (09/11) | **Chuẩn bị frontend và cấu trúc storefront**<br>• Tổ chức component React/TypeScript và route storefront theo thiết kế Figma.<br>• Xây dựng header/footer và điều hướng storefront bằng component tái sử dụng. | 09/11/2026 |  | `StorefrontLayout.tsx`, `Header.tsx`, `Footer.tsx` |
| Thứ 3 (10/11) | **API danh mục trang chủ**<br>• Phát triển API tổng hợp trang chủ, danh mục, banner và khám phá thương hiệu trên Spring Boot.<br>• Rà soát DTO và dữ liệu từ sản phẩm, khuyến mãi và danh mục. | 10/11/2026 |  | `HomePageController.java`, `CategoryController.java`, `BrandController.java` |
| Thứ 4 (11/11) | **Nhóm sản phẩm trang chủ**<br>• Kết nối storefront với dịch vụ homepage và ánh xạ dữ liệu API sang thẻ sản phẩm.<br>• Xây dựng carousel tái sử dụng cho sản phẩm nổi bật, bán chạy, giảm giá, đánh giá cao và flash sale; xử lý danh sách trống. | 11/11/2026 |  | `homeService.ts`, `HomeModel.tsx`, `ProductsSection.tsx`, `ProductCarousel.tsx` |
| Thứ 5 (12/11) | **Banner và khám phá sản phẩm**<br>• Tích hợp banner động với điều hướng coverflow, icon danh mục, thương hiệu đối tác và combo.<br>• Tinh chỉnh ảnh, khoảng cách thẻ và điều hướng đến trang danh mục/thương hiệu. | 12/11/2026 |  | `CoverflowSlider.tsx`, `CategorySection.tsx`, `PartnerStrip.tsx`, `CombosSection.tsx` |
| Thứ 6 (13/11) | **Điều hướng danh mục và giá**<br>• Làm việc với API danh sách, lọc thương hiệu, sản phẩm liên quan và giá theo bậc.<br>• Kết nối UI duyệt/mua hàng với MOQ, số lượng và giá từ dữ liệu thay vì giá hardcode. | 13/11/2026 |  | `ProductController.java`, `ProductPricingController.java`, `useCatalogBrowser.ts` |
| Thứ 7 (14/11) | **Tích hợp homepage và thao tác khách hàng**<br>• Tích hợp yêu thích và đăng ký newsletter vào giao diện khách hàng.<br>• Rà soát trạng thái tải/trống/lỗi và nội dung song ngữ; kiểm tra phản hồi API homepage và điều hướng. | 14/11/2026 |  | `FavoriteController.java`, `favoriteService.ts`, `newsletterService.ts`, `useNewsletterSignup.ts` |

### Kết quả tuần 9:

- Cấu trúc storefront và các khu vực homepage tái sử dụng có trong source frontend.
- API homepage, danh mục và giá có trong source backend.
- Tích hợp yêu thích, newsletter và nhóm sản phẩm thuộc phạm vi công việc.
