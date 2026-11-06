# Issue #10 — Build a row of equal-height cards that wraps on small screens

**Tier:** Intermediate (3pt)

## What to build

Build a row of 3 content cards with different amounts of text. On desktop they sit side by side at equal heights with their buttons aligned at the bottom; on small screens they wrap into a single column.

## Requirements

- Card container uses `display: flex`, `flex-wrap: wrap` and `gap`
- Cards use `flex` with a basis (e.g. `flex: 1 1 16rem`) so they wrap naturally without a media query
- Each card is itself a flex column so its button sits at the bottom (`margin-top: auto`)
- All cards are the same height on a row even though their text lengths differ

## Where to put your work

```
challenges/block-4/10-equal-height-card-row/(your-name)/index.html
challenges/block-4/10-equal-height-card-row/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- Cards are equal height with aligned buttons and wrap on small screens
- PR opened against `main`, linked to this issue (`Addresses #10`)

---

See [`example/`](example/) for a worked reference.
