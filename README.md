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
