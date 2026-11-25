---
title: "Week 9 Worklog"
date: 2026-11-09
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

> **Note:** This is a reconstructed worklog based on the reported scope and the FE/BE snapshots dated 25 November 2026. Individual task dates require confirmation. Entries after 25 November are planned, not completed.

### Week 9 Objectives:

- Translate the storefront design into React components.
- Develop and integrate homepage, catalog and brand APIs.
- Connect customer discovery and actions to dynamic data.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon (09/11) | **Frontend setup and storefront structure**<br>• Organize React/TypeScript storefront components and route structure around the Figma design.<br>• Build shared header/footer and storefront navigation with reusable UI components. | 09/11/2026 |  | `StorefrontLayout.tsx`, `Header.tsx`, `Footer.tsx` |
| Tue (10/11) | **Homepage catalog APIs**<br>• Work on Spring Boot homepage aggregation, categories, banners and brand discovery endpoints.<br>• Review DTO mapping and data from product, promotion and category records. | 10/11/2026 |  | `HomePageController.java`, `CategoryController.java`, `BrandController.java` |
| Wed (11/11) | **Homepage product collections**<br>• Connect the storefront to homepage services and map API responses to product cards.<br>• Build reusable carousels for featured, best-selling, discount, top-rated and flash-sale collections; handle empty collections. | 11/11/2026 |  | `homeService.ts`, `HomeModel.tsx`, `ProductsSection.tsx`, `ProductCarousel.tsx` |
| Thu (12/11) | **Homepage banners and discovery**<br>• Integrate dynamic banners with coverflow navigation, category icons, partner brands and combo sections.<br>• Refine image fit, card spacing and navigation to catalog or brand pages. | 12/11/2026 |  | `CoverflowSlider.tsx`, `CategorySection.tsx`, `PartnerStrip.tsx`, `CombosSection.tsx` |
| Fri (13/11) | **Catalog navigation and pricing**<br>• Work with catalog listing, brand filtering, related product and tiered pricing endpoints.<br>• Connect browsing and purchase UI with MOQ, quantity and pricing data rather than hard-coded prices. | 13/11/2026 |  | `ProductController.java`, `ProductPricingController.java`, `useCatalogBrowser.ts` |
| Sat (14/11) | **Homepage integration and customer actions**<br>• Integrate favorites and newsletter signup with customer-facing controls.<br>• Review loading, empty/error states and bilingual text; check homepage API responses and navigation. | 14/11/2026 |  | `FavoriteController.java`, `favoriteService.ts`, `newsletterService.ts`, `useNewsletterSignup.ts` |

### Week 9 Achievements:

- Storefront structure and reusable homepage sections are represented in the frontend snapshot.
- Homepage, catalog and pricing endpoints are represented in the backend snapshot.
- Favorites, newsletter and product collection integrations are included in the work scope.
