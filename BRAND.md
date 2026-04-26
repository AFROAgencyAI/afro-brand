# AFRO Brand Spec

Version 1.0 · Locked Apr 2026

Authoritative design-token reference. For positioning, voice, and strategy, see the [AFRO Brand Strategy Document](https://www.notion.so/34ec381f72d6815289b8e1305dd7eea5) in Notion.

---

## Identity

**Brand name:** AFRO
**Legal:** AFRO Agency AI
**Domain:** afroagency.ai
**Mark:** 4 orange rounded diamonds. Shadow version at scale ≥ 64px, flat at scale < 64px.

**Public tagline:** *20% more appointments without increasing ad spend.*

**Internal-only acronym** (do not surface in client-facing collateral): A·F·R·O = Acquisition · Fulfilment · Retention · Operations

---

## Colors

| Role | Hex | RGB | Usage |
|---|---|---|---|
| Primary orange | `#FF8000` | 255, 128, 0 | Logo, primary buttons, accents |
| Shadow orange | `#CC6600` | 204, 102, 0 | Logo extrusion only |
| Cream | `#FAF9F5` | 250, 249, 245 | Default page background |
| Black | `#141413` | 20, 20, 19 | Headlines, primary text on light |
| Body gray | `#5A5850` | 90, 88, 80 | Body copy on light backgrounds |
| Secondary gray | `#8A877D` | 138, 135, 125 | Captions, metadata, helper text |
| Border | `#DDD9D0` | 221, 217, 208 | Card borders, dividers |
| White | `#FFFFFF` | 255, 255, 255 | Card surfaces, contrast against cream |

Visual reference: see `swatches.png`.

### Background compatibility

Logo verified legible on cream `#FAF9F5`, white `#FFFFFF`, black `#141413`.

### Gradient rules

- Radial gradients **allowed** on section/container backgrounds for Apple-style bezel depth on rounded containers
- Buttons are **flat color only**. No gradients
- **No gradients on text**, ever

---

## Typography

**Primary:** Gilroy (Fontspring web license, self-hosted)
**Fallback:** `'Gilroy', sans-serif`
**No supporting font.** Gilroy handles everything.

### Weights loaded

| Weight | File | Use |
|---|---|---|
| 400 | Gilroy-Regular.woff2 | Body copy |
| 500 | Gilroy-Medium.woff2 | UI labels, buttons |
| 600 | Gilroy-SemiBold.woff2 | Subheadings |
| 700 | Gilroy-Bold.woff2 | Headlines, emphasis |

CDN URLs and the drop-in `@font-face` block: see `fonts.md`.

---

## Spacing scale

8-point system. Use only these values.

| Token | Value | Use |
|---|---|---|
| `xs` | 4px | Tight icon/text |
| `sm` | 8px | Element internal |
| `md` | 16px | Default gap |
| `lg` | 24px | Card padding |
| `xl` | 40px | Section internal |
| `2xl` | 64px | Section vertical |
| `3xl` | 96px | Hero vertical |
| `4xl` | 128px | Page-break vertical on desktop |

---

## Radius scale

| Token | Value | Use |
|---|---|---|
| `sm` | 6px | Inputs, small buttons |
| `md` | 12px | Cards |
| `lg` | 20px | Containers, large cards |
| `xl` | 32px | Hero blocks |
| `pill` | 9999px | Pills, tags, primary CTAs |

---

## Voice rules (top-line)

- Round numbers in pricing
- No em dashes unless absolutely necessary
- Information-dense, minimum words
- Warm, professional, conversion-focused. Not salesy
- Killed phrases: "rebuild in 4 hours", "seconds vs hours" lead response framing, "solo agency"

Full positioning lives in the Notion strategy doc linked above.
