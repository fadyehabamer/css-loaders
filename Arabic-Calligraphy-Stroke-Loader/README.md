# Arabic-Calligraphy-Stroke-Loader

> SVG loader that writes أهلاً stroke by stroke

### [View Live Demo](https://fadyehabamer.github.io/css-loaders/Arabic-Calligraphy-Stroke-Loader/)

## Overview

The word أهلاً ("welcome") is split into five SVG paths: the alef with hamza, the heh, the lam, the alef and the tanween. Each path is traced with `stroke-dashoffset`, filled in, then faded out, one after the other from right to left, and the cycle repeats.

The letter outlines were taken from the [Amiri](https://github.com/aliftype/amiri) typeface (SIL Open Font License 1.1) and shaped with HarfBuzz, so the joins and the lam-alef ligature are correct. No font file is loaded by the page.

## Built With

**Languages:** HTML · CSS · SVG

## Techniques Demonstrated

- `pathLength="1"` so every path uses the same dash values
- `stroke-dasharray` / `stroke-dashoffset` drawing animation
- Staggered delays through a `--i` custom property
- `role="status"` with visually hidden loading text
- `prefers-reduced-motion` fallback that shows the full word with a soft fade

## Files

```
index.html
style.css
```

## Run Locally

```bash
git clone https://github.com/fadyehabamer/css-loaders.git
cd css-loaders/Arabic-Calligraphy-Stroke-Loader
```

Then open `index.html` in your browser.

---
↩ Part of the [**css-loaders**](../) collection · [all my repos](https://github.com/fadyehabamer?tab=repositories) · [@fadyehabamer](https://github.com/fadyehabamer)
