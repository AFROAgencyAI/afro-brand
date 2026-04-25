# AFRO Agency AI — Brand Assets

## Files

| File | Use case | Source |
|---|---|---|
| `afro-logo.svg` | Primary logo (web, hero, all UI ≥ 256px) | shadow version |
| `afro-logo-flat.svg` | Where shadow muddies (small UI, embossing, single-color print) | flat version |
| `afro-logo-1024.png` | Marketing creative, social media, print masters | shadow, transparent |
| `afro-logo-512.png` | App icon, OG image base | shadow, transparent |
| `afro-logo-256.png` | Email signatures, dashboards | shadow, transparent |
| `favicon-32.png` | Browser tab, taskbar | flat, transparent |
| `favicon-16.png` | Address bar, tiny UI | flat, transparent |
| `favicon.ico` | Universal favicon (16+32+48 multi-res) | flat |

## Why two SVGs

Below 64px the cylindrical extrusion shadow renders as visual noise and the inner star disappears. Use `afro-logo-flat.svg` for any rendering target ≤ 64px.

## Color palette

- Primary orange: `#FF8000`
- Shadow orange: `#CC6600` (extrusion only)
- Cream: `#FAF9F5`
- Black: `#141413`

## Background compatibility

Verified legible on cream `#FAF9F5`, white `#FFFFFF`, and black `#141413`.

## HTML usage

```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" type="image/svg+xml" href="/afro-logo-flat.svg">
<link rel="apple-touch-icon" href="/afro-logo-256.png">
```
