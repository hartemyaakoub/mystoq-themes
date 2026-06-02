# Mystoq Themes

> Open catalogue of storefront themes available on [Mystoq](https://mystoq.com).

Each Mystoq tenant can pick a theme that ships with a coherent design system:
colors, typography, hero variants, category layout, product card styles.

## Available themes

| ID | Name | Best for |
|----|------|----------|
| `beauty` | Beauty | Cosmetics, perfume, skincare |
| `luxe` | Luxe | Jewelry, watches, high-end |
| `sahara` | Sahara | Traditional crafts, leather |
| `aurora` | Aurora | Tech, electronics, lifestyle |
| `classic` | Classic | General stores |

→ Live previews: https://demo.mystoq.com

## Apply a theme

In your dashboard: Settings → Theme → pick one.

Programmatically via the [SDK](https://github.com/hartemyaakoub/mystoq-js-sdk):

```js
await mystoq.applyTheme("luxe");
```

## Why public?

Transparency. Every Mystoq merchant can audit which themes ship by default,
suggest improvements via PRs, or build their own variant.

→ https://mystoq.com

## License

MIT.

<!-- TKAWEN-ECOSYSTEM-FOOTER -->
## TKAWEN Ecosystem

This project is part of the [TKAWEN](https://tkawen.com) ecosystem — open APIs and tools for emerging-market digital infrastructure.

- [Mystoq](https://mystoq.com) — multi-tenant e-commerce platform for MENA
- [Algeria Certify](https://algeriacertify.com) — national digital credentialing
- [LIQAA](https://liqaa.io) — sovereign video conferencing
- [TKAWEN Academy](https://tkawen.com/academy) — online learning platform
- [SEO Toolkit](https://www.npmjs.com/package/@mystoq/seo-toolkit) — llms.txt, sitemap, Schema.org JSON-LD generators

Built by [Hartem Yaakoub](https://hartem.tkawen.com) - MIT licensed - Refreshed 2026-06-02.
