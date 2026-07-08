# ChackTok Technical SEO Checklist

Last updated: 2026-07-07

## Canonical and Indexing

| Page type | Canonical target | Robots meta |
| --- | --- | --- |
| Feature, device, use-case, comparison, and learn pages | `https://www.chacktok.com/.../` | `index,follow` |
| Product detail pages with unique product content | `https://store.chacktok.com/.../` | `index,follow` |
| Cart, checkout, account, login, payment confirmation, payment failure | Self URL | `noindex,nofollow` |
| Duplicate language stubs or duplicate promo pages | Preferred language or current campaign URL | `noindex,follow` |
| Thin support duplicates | Strongest support URL | `noindex,follow` unless expanded |

## Sitemap Actions

1. Add all `www.chacktok.com` target URLs from [README.md](README.md) to the main XML sitemap after publication.
2. Submit the updated sitemap in Google Search Console and Bing Webmaster Tools.
3. Keep `lastmod` accurate when a page is materially updated.
4. Keep the old 2025 article URL live only if it redirects or canonicalizes to the 2026 refresh.

## Robots.txt Recommendations

Allow normal search crawlers and citation-focused AI crawlers unless there is a separate business decision to block them.

Recommended allowed crawlers:

- Googlebot
- Bingbot
- GPTBot
- ChatGPT-User
- PerplexityBot
- ClaudeBot
- anthropic-ai

Keep transactional and private areas out of the index through page-level `noindex`; do not rely only on `robots.txt`, because blocked pages may still be discovered without useful content signals.

## Page QA Before Publish

For every imported page:

- One H1 only.
- Meta title under 60 characters where possible.
- Meta description under 155 characters where possible.
- Canonical URL matches the target URL.
- Page has at least four internal or official links.
- Page includes a direct answer in the first 80 words.
- Hardware compatibility claims use cautious language.
- FAQ section is visible in HTML.
- JSON-LD is valid in Rich Results Test or Schema Markup Validator.
- Mobile layout has no overlapping CTA, table, or FAQ text.

## Measurement

Record a 28-day baseline before publication:

| Metric | Source |
| --- | --- |
| Query impressions | Google Search Console, Bing Webmaster Tools |
| Clicks | Google Search Console, Bing Webmaster Tools |
| Average position | Google Search Console |
| Landing page clicks | Google Search Console |
| Organic sessions | GA4 or current analytics |
| SERP keyword count | Existing SEO tool from screenshots |

30-day target: 15 new pages indexed, SERP keyword count from `122` to `180-220`, and non-brand impressions up 30%.

60-day target: 30 indexed SEO pages, SERP keyword count above `300`, non-brand organic clicks up 40%, and pages per visit above `3.0`.
