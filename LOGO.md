# ChartBoard — Logo Design Brief

## Concept
ChartBoard is a dark-themed stock market chart viewer. The logo should feel **professional, modern, and data-driven** — somewhere between a fintech product and a developer tool. Think TradingView meets Linear.

---

## Brand Personality
- Dark, sleek, minimal
- Trustworthy and precise
- For traders and investors who care about data

---

## Color Palette
| Role | Hex |
|---|---|
| Background | `#0d0d0d` |
| Surface | `#1a1a1a` |
| Accent (primary) | `#2962ff` |
| Text | `#e0e0e0` |

The accent blue `#2962ff` should be the dominant color in the icon/logo.

---

## Logo Concepts

### Option A — Icon embedded in the wordmark
The icon sits to the left of the text "ChartBoard", same height as the capital letters.

```
[▣] ChartBoard
```
The icon is a small square with a stylized upward area chart curve inside, rendered in `#2962ff` on a slightly lighter dark background. The text "ChartBoard" is white, bold, sans-serif (Inter or Geist).

---

### Option B — Stacked (icon above text)
```
    ▣
ChartBoard
```
A square icon (~80×80px) with rounded corners, dark background `#141414`, and a blue area chart inside. Below it, the wordmark in white.

---

### Option C — Icon only (for favicon / app icon)
A single square with:
- Background: `#141414` or `#0d0d0d`
- Rounded corners (20% radius for app icon, 4px for favicon)
- A blue area chart curve (`#2962ff`) that fills ~60% of the canvas
- Optional: a subtle grid of horizontal lines behind the chart in `#1f1f1f`

---

## Icon Design Details

**Shape:** Square with rounded corners  
**Background:** `#141414`  
**Chart element:** Area chart (filled below the line), line color `#2962ff`, fill `rgba(41,98,255,0.25)`  
**Chart style:** 2–3 data points forming a gentle upward curve, like the mini charts in the app itself  
**No text inside the icon**

### Proportions (for a 512×512 canvas)
- Padding: 80px on all sides
- Chart area: 352×352px
- Line thickness: ~14px
- The curve goes from bottom-left to top-right with a slight S-curve in the middle

---

## Typography
- **Wordmark font:** Inter Bold or Geist Bold (weight 700–800)
- **Letter spacing:** -0.5px (slightly tight, modern feel)
- **Case:** Title case — "ChartBoard" (not all caps, not all lowercase)

---

## Deliverables Needed
- [ ] SVG icon (scalable, for embedding in HTML)
- [ ] SVG wordmark (icon + text side by side)
- [ ] PNG favicon 32×32
- [ ] PNG app icon 512×512 (for Netlify / social sharing)
- [ ] Dark background version (primary)
- [ ] Light background version (optional)

---

## Embedding in the App
The final SVG icon should replace the emoji `📈` currently used in the consent modal, and ideally be embedded inline in the `<div class="app-title">` in the header so it renders at any resolution without loading an external file.

Target header result:
```
[svg icon 18×18]  ChartBoard
```
Both the icon and the text share the blue-to-white gradient currently on the wordmark.

---

## Reference / Inspiration
- TradingView logo (chart-in-a-box icon style)
- Linear.app (dark, minimal, precise)
- Vercel (clean wordmark with geometric icon)
