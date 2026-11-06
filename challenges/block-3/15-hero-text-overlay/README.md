# Issue #15 — Build a hero section with a positioned text overlay

**Tier:** Advanced (6pt)

## What to build

Build a hero banner with a full-width background image, a dark overlay for readability, and a headline + call-to-action positioned over it using relative/absolute positioning.

## Requirements

- Hero container uses `position: relative` and a fixed `min-height` (e.g. `60vh`)
- A background image fills the hero (`background-size: cover` or an absolutely positioned `<img>` with `object-fit: cover`)
- A semi-transparent overlay layer (`position: absolute; inset: 0`) sits between the image and the text
- The text block is positioned above the overlay (`z-index`) and text meets AA contrast against the overlay
- The CTA is a real `<a>` styled as a button, with visible `:hover` and `:focus-visible` states

## Where to put your work

```
challenges/block-3/15-hero-text-overlay/(your-name)/index.html
challenges/block-3/15-hero-text-overlay/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- Headline and CTA are readable over the image, with layering controlled by positioning and z-index
- PR opened against `main`, linked to this issue (`Addresses #15`)

---

See [`example/`](example/) for a worked reference.
