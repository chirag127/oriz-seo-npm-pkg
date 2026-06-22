# @chirag127/oriz-seo

[![npm](https://img.shields.io/npm/v/@chirag127/oriz-seo.svg)](https://www.npmjs.com/package/@chirag127/oriz-seo)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

Sitemap.xml + IndexNow ping + JSON-LD structured data + dynamic OG image generation via satori. SEO toolkit for Astro/Next sites.

## Install

```bash
pnpm add @chirag127/oriz-seo
```

## Status

v0.1.0 is a slug-reservation stub. Real implementation lands when oriz apps consume it.

## Planned API

- `buildSitemap(routes, opts)` — emits a spec-compliant sitemap.xml, with priority + changefreq.
- `pingIndexNow(urls, key)` — Bing/Yandex/Seznam IndexNow notification with a single host key.
- `jsonLd(type, data)` — typed JSON-LD builders for Article, Product, FAQPage, Organization.
- `ogImage(template, props)` — renders OG images with satori; returns PNG buffer or Response.
- Framework adapters for Astro endpoints and Next.js route handlers.

## License

MIT (c) 2026 Chirag Singhal
