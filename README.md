# ChromaSense

A color discernment game for GitHub Pages.

One swatch in the 3×3 grid is a different hue. Tap it before time runs out.
Colors get harder as you improve — difficulty is measured in **CIEDE2000 ΔE**, the standard
unit used in color science (ΔE < 1 = imperceptible, ΔE ~2 = just noticeable).

Inspired by the [Farnsworth-Munsell 100 Hue Test](https://en.wikipedia.org/wiki/Farnsworth%E2%80%93Munsell_100_hue_test) (1943).

---

## Play

Open `index.html` in any modern browser, or visit the GitHub Pages URL.

## Stack

- Zero dependencies — pure HTML + CSS + JS, single file
- `oklch()` color rendering (sRGB fallback for older browsers)
- CIEDE2000 ΔE implemented from scratch
- Scores stored in `localStorage`

## Screenshot

<!-- add screenshot here -->
