# ChackTok SERP Entry Page Pack

Last updated: 2026-07-07

This folder implements the first wave of the ChackTok SERP gap plan. It is designed for import into `www.chacktok.com` as indexable pages, while `store.chacktok.com` remains the purchase and product-catalog destination.

## Publishing Model

| Area | Canonical role | Indexing rule |
| --- | --- | --- |
| `www.chacktok.com` | SEO hub, feature pages, comparison pages, tutorials, use cases | Index |
| `store.chacktok.com` | Product detail, checkout, support, account, active promotions | Index product/support pages only |
| Cart, checkout, account, payment, duplicate promo pages | Transactional or duplicate pages | Noindex |

All imported pages should show `Last updated: 2026-07-07`, use the canonical URL listed below, and link to the App Store, Google Play, official store, tutorials, and support pages where relevant.

## URL Map

| Target URL | Source draft | Primary intent |
| --- | --- | --- |
| `/software/photo-booth-software/` | [pages/software/photo-booth-software.md](pages/software/photo-booth-software.md) | Photo booth software |
| `/software/360-photo-booth-software/` | [pages/software/360-photo-booth-software.md](pages/software/360-photo-booth-software.md) | 360 booth software |
| `/software/photo-booth-app/` | [pages/software/photo-booth-app.md](pages/software/photo-booth-app.md) | Photo booth app |
| `/devices/ipad-photo-booth-app/` | [pages/devices/ipad-photo-booth-app.md](pages/devices/ipad-photo-booth-app.md) | iPad booth app |
| `/devices/android-photo-booth-app/` | [pages/devices/android-photo-booth-app.md](pages/devices/android-photo-booth-app.md) | Android booth app |
| `/devices/gopro-photo-booth-app/` | [pages/devices/gopro-photo-booth-app.md](pages/devices/gopro-photo-booth-app.md) | GoPro booth app |
| `/software/photo-booth-business-software/` | [pages/software/photo-booth-business-software.md](pages/software/photo-booth-business-software.md) | Operator business software |
| `/use-cases/start-a-photo-booth-business/` | [pages/use-cases/start-a-photo-booth-business.md](pages/use-cases/start-a-photo-booth-business.md) | New operator guide |
| `/use-cases/wedding-photo-booth-software/` | [pages/use-cases/wedding-photo-booth-software.md](pages/use-cases/wedding-photo-booth-software.md) | Wedding operators |
| `/use-cases/corporate-event-photo-booth-software/` | [pages/use-cases/corporate-event-photo-booth-software.md](pages/use-cases/corporate-event-photo-booth-software.md) | Brand activations |
| `/compare/touchpix-alternative/` | [pages/compare/touchpix-alternative.md](pages/compare/touchpix-alternative.md) | Touchpix alternative |
| `/compare/dslrbooth-alternative/` | [pages/compare/dslrbooth-alternative.md](pages/compare/dslrbooth-alternative.md) | dslrBooth alternative |
| `/compare/snappic-alternative/` | [pages/compare/snappic-alternative.md](pages/compare/snappic-alternative.md) | Snappic alternative |
| `/compare/lumabooth-alternative/` | [pages/compare/lumabooth-alternative.md](pages/compare/lumabooth-alternative.md) | LumaBooth alternative |
| `/learn/best-360-photo-booth-software-2026/` | [pages/learn/best-360-photo-booth-software-2026.md](pages/learn/best-360-photo-booth-software-2026.md) | Refresh old 2025 article |
| `/learn/best-photo-booth-app-2026/` | [pages/learn/best-photo-booth-app-2026.md](pages/learn/best-photo-booth-app-2026.md) | Best app sibling page |
| `/learn/best-photo-booth-software-2026/` | [pages/learn/best-photo-booth-software-2026.md](pages/learn/best-photo-booth-software-2026.md) | Best software sibling page |

## Required Internal Links

Each imported page should include at least four links:

- App download: `https://apps.apple.com/us/app/chacktok-photo-booth-event/id1613120226`
- Android download: `https://play.google.com/store/apps/details?id=com.youfan.chacktok&hl=en_US&gl=US`
- Store: `https://store.chacktok.com/`
- Tutorial hub: `https://www.chacktok.com/how-to-use-chacktok/`
- Support: `https://store.chacktok.com/support-2/`
- Related ChackTok SEO pages from this pack

## Implementation Notes

- Do not publish unsupported compatibility claims. Keep `where supported`, `confirm before a commercial event`, and `test the full workflow` language where hardware is involved.
- Do not add review schema unless the review source is real, public, and verifiable.
- Comparison pages should be fair, source-linked, and dated. Avoid stale competitor pricing values; link to live pricing pages instead.
- See [technical-seo-checklist.md](technical-seo-checklist.md) for canonical, noindex, sitemap, and validation tasks.
- See [schema-templates.md](schema-templates.md) for JSON-LD blocks to adapt per page.
