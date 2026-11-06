# Issue #7 — Stack items on mobile and line them up on desktop with flex-direction

**Tier:** Beginner (1pt)

## What to build

Build a row of 3 feature blocks that stack vertically on small screens and sit side by side on larger screens by changing `flex-direction` in a media query.

## Requirements

- Container uses `display: flex` with `flex-direction: column` as the base (mobile) style
- A `min-width` media query switches it to `flex-direction: row`
- Items share space equally on desktop (`flex: 1`)
- Spacing uses `gap`

## Where to put your work

```
challenges/block-4/07-flex-direction-switch/(your-name)/index.html
challenges/block-4/07-flex-direction-switch/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- Items stack on mobile and sit in a row on desktop
- PR opened against `main`, linked to this issue (`Addresses #7`)

---

See [`example/`](example/) for a worked reference.
