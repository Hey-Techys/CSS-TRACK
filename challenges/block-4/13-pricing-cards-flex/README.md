# Issue #13 — Build responsive pricing cards with a highlighted plan

**Tier:** Intermediate (3pt)

## What to build

Build 3 pricing cards (e.g. Free, Pro, Team) with a highlighted middle plan. Cards stack on mobile and sit in a row on larger screens, with the highlighted card visually emphasised.

## Requirements

- Cards stack on mobile and become a flex row at a `min-width` breakpoint
- Each card is a flex column with a list of features and a button pinned to the bottom
- The highlighted card is emphasised using border/color and `flex-grow` or `transform: scale()` — without breaking alignment
- On mobile, the highlighted card appears first using the `order` property

## Where to put your work

```
challenges/block-4/13-pricing-cards-flex/(your-name)/index.html
challenges/block-4/13-pricing-cards-flex/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- Cards are responsive, the featured plan stands out, and it appears first on mobile
- PR opened against `main`, linked to this issue (`Addresses #13`)

---

See [`example/`](example/) for a worked reference.
