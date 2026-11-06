# Issue #8 — Keep the footer at the bottom of short pages with Flexbox

**Tier:** Beginner (1pt)

## What to build

On a page with very little content, keep the footer at the bottom of the window instead of floating halfway up — using a flex column layout.

## Requirements

- `body` (or a wrapper) uses `display: flex`, `flex-direction: column` and `min-height: 100vh`
- `main` uses `flex: 1` (or `flex-grow: 1`) to take up the remaining space
- No `position: fixed` or `absolute` on the footer
- With lots of content, the footer still sits after the content (not overlapping it)

## Where to put your work

```
challenges/block-4/08-sticky-footer-flex/(your-name)/index.html
challenges/block-4/08-sticky-footer-flex/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- Footer sits at the bottom of short pages and after content on long pages
- PR opened against `main`, linked to this issue (`Addresses #8`)

---

See [`example/`](example/) for a worked reference.
