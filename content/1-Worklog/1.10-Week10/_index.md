---
title: "Week 10 Worklog"
date: 2026-11-16
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

> **Note:** This is a reconstructed worklog based on the reported scope and the FE/BE snapshots dated 25 November 2026. Individual task dates require confirmation. Entries after 25 November are planned, not completed.

### Week 10 Objectives:

- Develop product details and customer review interactions.
- Integrate notification APIs and customer account interfaces.
- Establish the e-commerce executive workspace integration.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon (16/11) | **Product details: data and presentation**<br>• Connect product detail, pricing and related product data to the detail route.<br>• Arrange gallery, product descriptions, specifications and nutrition information with loading/not-found handling. | 16/11/2026 |  | `useProductDetail.ts`, `CustomerProductInfo.tsx`, `ProductController.java` |
| Tue (17/11) | **Product details: purchase interaction**<br>• Implement purchase panel interactions for quantity, minimum order quantity and tier pricing.<br>• Integrate cart and favorite actions; review stock and purchase eligibility handling. | 17/11/2026 |  | `CustomerProductPurchase.tsx`, `cartStore.ts`, `ProductPricingController.java` |
| Wed (18/11) | **Customer review workflow**<br>• Work on customer review and product review APIs, rating summaries and review retrieval.<br>• Integrate review form, image upload/display and edit/delete operations with customer review UI. | 18/11/2026 |  | `CustomerReviewController.java`, `ProductReviewController.java`, `CustomerWriteReview.tsx` |
| Thu (19/11) | **Notifications backend**<br>• Work on notification list, unread count, mark-as-read and mark-all-as-read endpoints.<br>• Review notification preference retrieval/update and customer-specific access boundaries. | 19/11/2026 |  | `NotificationController.java`, `notificationService.ts` |
| Fri (20/11) | **Notifications frontend and profile integration**<br>• Connect notification dropdown, filters, selected item view and settings to backend responses.<br>• Review profile form, avatar cropping and upload integration; refine toggle alignment and feedback states. | 20/11/2026 |  | `NotificationSystem.tsx`, `ProfilePage.tsx`, `CustomerProfileController.java` |
| Sat (21/11) | **E-commerce workspace foundation**<br>• Set up executive workspace layout, shared controls and dashboard metric integration.<br>• Connect product listing/status and quote/review entry points; review role restrictions and API errors. | 21/11/2026 |  | `EcommerceDashboardPage.tsx`, `EcommerceProductsPage.tsx`, `ExecutiveOperationsController.java` |

### Week 10 Achievements:

- Product detail components and pricing/review endpoints are present in the supplied source.
- Notification list, unread state and preferences are represented across FE/BE.
- Executive workspace and dashboard/product management interfaces are included in the source.
