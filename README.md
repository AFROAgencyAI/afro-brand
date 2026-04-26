# AFRO Agency AI — Brand Assets

Single source of truth for AFRO brand. Logo files, design tokens, typography spec, and color palette.

**Public tagline:** *20% more appointments without increasing ad spend.*

---

## What's here

| File | Use |
|---|---|
| `BRAND.md` | Full design spec: colors, typography, spacing, radius, gradient rules |
| `fonts.md` | Gilroy CDN URLs + drop-in `@font-face` block for GHL |
| `swatches.png` | Visual color reference, hex + RGB labeled |
| `afro-logo.svg` | Primary logo, shadow version, scale ≥ 64px |
| `afro-logo-flat.svg` | Flat version, scale < 64px |
| `afro-logo-1024.png` | Marketing creative, social, print masters (transparent) |
| `afro-logo-512.png` | App icon, OG image base (transparent) |
| `afro-logo-256.png` | Email signatures, dashboards (transparent) |
| `favicon-32.png` | Browser tab, taskbar |
| `favicon-16.png` | Address bar, tiny UI |
| `favicon.ico` | Universal favicon (16, 32, 48 multi-res) |

---

## Quick reference

**Logo:** Use shadow `afro-logo.svg` at scale ≥ 64px. Use flat `afro-logo-flat.svg` below 64px. The 4-diamond mark loses fidelity below 32px.

**Colors:** Primary `#FF8000`, default background `#FAF9F5`, headlines `#141413`. Full table in `BRAND.md`.

**Typography:** Gilroy only, self-hosted via jsDelivr. Drop-in block in `fonts.md`.

---

## CDN access (jsDelivr)

```
https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-brand@main/afro-logo.svg
https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-brand@main/afro-logo-flat.svg
https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-brand@main/favicon.ico
```

For a stable version that won't shift on commits, pin to a release tag:

```
https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-brand@v1.0/...
```

## HTML head integration (GHL Tracking Code)

```html
<link rel="icon" href="https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-brand@main/favicon.ico" sizes="any">
<link rel="icon" type="image/svg+xml" href="https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-brand@main/afro-logo-flat.svg">
<link rel="apple-touch-icon" href="https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-brand@main/afro-logo-256.png">
```

---

## Stable share-link

For external collaborators, designers, or briefs, share the latest tagged release:

```
https://github.com/AFROAgencyAI/afro-brand/releases/latest
```

GitHub auto-generates a downloadable `.zip` of the full repo at every release.

---

## License

These assets are property of AFRO Agency AI. Internal team and contracted vendors may use for AFRO marketing purposes only. External use, including in client deliverables outside AFRO branding, requires written permission.

Gilroy webfonts (in `afro-fonts` repo) are licensed via Fontspring. Self-hosting permitted under existing webfont license. Do not redistribute the `.woff2` files outside the AFRO ecosystem.
