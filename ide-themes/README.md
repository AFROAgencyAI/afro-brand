# IDE Themes

AFRO-brand editor themes. Keeps every dev machine on-brand and visually consistent.

| File | Editor | Mode |
|---|---|---|
| `antigravity-dark.jsonc` | Antigravity IDE | Dark |

---

## Install — Antigravity IDE (dark)

1. Open the settings JSON: `Cmd+Shift+P` → type **`Preferences: Open User Settings (JSON)`** → Enter. (Pick the **(JSON)** entry, not plain "Open User Settings".)
2. Select all (`Cmd+A`), delete, then paste the contents of `antigravity-dark.jsonc` (drop the leading `//` comment lines if you like — they're valid JSONC either way).
3. Save (`Cmd+S`). Applies instantly — no window reload needed.

**macOS live settings path:** `~/Library/Application Support/Antigravity IDE/User/settings.json`
(A second dir `~/Library/Application Support/Antigravity/User/` may exist — it is NOT the active install. The Command Palette always opens the correct file.)

Already have settings in that file? Merge: paste the `workbench.colorCustomizations` and `editor.tokenColorCustomizations` keys inside your existing top-level `{ }`, minding commas.

---

## Design notes

- **Base:** brand black `#141413`, with derived elevation shades `#1C1B19` / `#232220` / `#2E2C28`.
- **Text:** softened cream `#E8E6DF` — pure `#FAF9F5` glares over long sessions.
- **One-glance differentiator:** the activity bar — bright orange `#FF8000` icon glyphs with a shadow-orange `#CC6600` fill behind the active view. (Per-glyph outline-vs-fill two-tone isn't possible; activity-bar icons are single-color glyphs.)
- **Syntax:** orange hero + warm gold `#F0C36D` / green `#A3BE6F` / sand `#D9C68A`, plus one cool blue `#82AAC4` for numbers & constants so they stand out against the otherwise-warm palette.
- **Buttons:** black text on orange for WCAG AA contrast.

All colors trace to `../BRAND.md`. Antigravity is a VS Code fork, so `antigravity-dark.jsonc` is portable to VS Code / Cursor / other forks with the same keys.
