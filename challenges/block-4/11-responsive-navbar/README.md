# Issue #11 — Build a responsive navbar that stacks on mobile (no JavaScript)

**Tier:** Intermediate (3pt)

## What to build

Build a header whose logo and links stack vertically on small screens and become a single horizontal bar on larger screens — CSS only, no hamburger menu.

## Requirements

- Mobile base: logo above links, links stacked or wrapped, each link with a comfortable tap target (at least 44px tall)
- At a `min-width` breakpoint the header becomes a flex row with logo left and links right
- Uses `flex-direction`, `flex-wrap` or `gap` changes in the media query — no fixed widths that break at in-between sizes
- The current page link is marked with `aria-current="page"` and styled differently

## Where to put your work

```
challenges/block-4/11-responsive-navbar/(your-name)/index.html
challenges/block-4/11-responsive-navbar/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- Navbar works at every width from 320px up with no overflow
- PR opened against `main`, linked to this issue (`Addresses #11`)

---

See [`example/`](example/) for a worked reference.
