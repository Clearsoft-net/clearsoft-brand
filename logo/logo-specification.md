# Clearsoft — Logo Specification

> Brand usage guide · Version 1.0
> Holding & SaaS Governance · clearsoft.net

---

## 1. Color Palette

### The Synergy Lens (symbol)

Two interlocking optical lenses — the precise reading and the synergy across the holding's products.

| Element | Light mode | Dark mode |
|---|---|---|
| Primary lens (stroke) | `#334155` (Slate 700) | `#94A3B8` (Slate 400) |
| Accent lens (stroke) | `#0D9488` (Teal 600) | `#14B8A6` (Teal 500) |
| Core / highlight | `#38BDF8` (Sky 400) | `#38BDF8` (Sky 400) |

### Text

| Element | Light mode | Dark mode |
|---|---|---|
| "CLEAR" | `#0F172A` (Slate 900) | `#FFFFFF` (White) |
| "SOFT" | `#0D9488` (Teal 600) | `#2DD4BF` (Teal 400) |
| Subtitle `clearsoft.net` | `#0D9488` (Teal 600) | `#2DD4BF` (Teal 400) |

### Backgrounds

| Context | Color |
|---|---|
| Light background | `#FFFFFF` or `#F8FAFC` (Slate 50) |
| Dark product background | `#0F172A` (Slate 900) |
| Deep dark background | `#020617` (Slate 950) |
| Icon ring (light bg, 08) | `#E2E8F0` (Slate 200) |
| Icon tile (dark, 07) | `#0F172A` (Slate 900) |

---

## 2. Typography

| Element | Font | Weight | Details |
|---|---|---|---|
| **Wordmark** `CLEAR` | Sora | Extra Bold (800) | — |
| **Wordmark** `SOFT` | Sora | Light (300) | — |
| Subtitle / domain | JetBrains Mono | SemiBold (600) | lowercase, `clearsoft.net`, wide letter-spacing |
| Interface (UI) | Plus Jakarta Sans | 400–800 | dashboards, tables, and navigation |

**Logo font:** [Sora](https://fonts.google.com/specimen/Sora) (open source, Google Fonts)
**Fallback:** `system-ui, -apple-system, sans-serif`
**Mono (domain / data):** [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)
**UI:** [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans)

---

## 3. Logo Proportions

### Horizontal (01 / 02) — viewBox 250×56

```
←———————————————— 250px ————————————————→
┌───────────────────────────────────────────┐
│                                           │
│  ◉◉   CLEARSOFT                           │  ← 20px (CLEAR 800 / SOFT 300)
│  lenses ↑                                 │
│  r=15    clearsoft.net                    │  ← 9px, JetBrains Mono
└───────────────────────────────────────────┘
                    56px
```

| Element | Size | Reference |
|---|---|---|
| Symbol lenses | r=15 | centers (20,28) and (31,28), stroke 2.6 |
| Core (ellipse) | 5.5×11 | center (25.5,28) |
| "CLEARSOFT" | 20px | starts at x=56, baseline y=31 |
| Subtitle | 9px | starts at x=56, baseline y=46, tracking +1.8 |

### Stacked (03 / 04) — viewBox 180×110

```
┌──────── 180px ────────┐
│                        │
│         ◉◉             │  ← lenses r=16, centered
│                        │
│      CLEARSOFT         │  ← 19px, centered, baseline y=74
│                        │
│     clearsoft.net      │  ← 9px, baseline y=92
└────────────────────────┘
          110px height
```

### Text only (05 / 06) — viewBox 200×64

```
←——— 200px ———→
┌───────────────────────┐
│      CLEARSOFT        │  ← 20px, centered, baseline y=32
│     clearsoft.net     │  ← 9px, baseline y=48
└───────────────────────┘
         64px height
```

### Icon only (07 / 08) — 64×64

```
┌──── 64px ────┐
│              │
│      ◉◉      │  ← tile rx=14; lenses r=16
│              │
└──────────────┘
```

- **07 (dark):** tile `#0F172A`, lenses in light tones.
- **08 (light):** tile `#FFFFFF` with a `#E2E8F0` ring, lenses in dark tones.

---

## 4. Clear Space

- Around the logo, keep a minimum spacing equal to the height of the symbol (the diameter of one lens, `2r`).
- No element (text, icon, border) may intrude into this area.

---

## 5. Minimum Size

| Variation | Recommended minimum |
|---|---|
| Horizontal (01/02) | 150px width |
| Stacked (03/04) | 100px width |
| Text only (05/06) | 120px width |
| Icon only (07/08) | 24px (favicon) |

Below these sizes, use the icon only (07/08).

---

## 6. Don'ts

- ❌ Do not stretch or distort the logo
- ❌ Do not change the symbol's colors (Slate + Teal + Sky)
- ❌ Do not add shadows, gradients, or effects to the symbol
- ❌ Do not replace Sora with another font in the wordmark
- ❌ Do not write "Clear Soft" with a space — it is **CLEARSOFT**
- ❌ Do not use teal `#0D9488` as a primary background color (accents/CTAs only)
- ❌ Do not place the dark wordmark over dark backgrounds (use the dark variation)

---

## 7. Files

| File | Description |
|---|---|
| `01-dark-horizontal.svg` | Full logo — dark background |
| `02-light-horizontal.svg` | Full logo — light background |
| `03-dark-stacked.svg` | Stacked — dark background |
| `04-light-stacked.svg` | Stacked — light background |
| `05-dark-text-only.svg` | Text + domain only — dark background |
| `06-light-text-only.svg` | Text + domain only — light background |
| `07-dark-icon-only.svg` | Symbol only — dark background (slate tile) |
| `08-light-icon-only.svg` | Symbol only — light background (white tile, `#E2E8F0` ring) |

> The `.png` files are rendered at 4× from their corresponding `.svg` files (transparent background).
