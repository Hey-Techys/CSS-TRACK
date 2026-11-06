# Issue #13 — Style a data table with borders, zebra rows and a caption

**Tier:** Intermediate (3pt)

## What to build

Style an HTML table (e.g. the language comparison table from Block 1) so it's easy to scan: collapsed borders, padded cells, a distinct header row and alternating row colors.

## Requirements

- `border-collapse: collapse` with a visible border on cells
- `th` and `td` have padding; header cells are visually distinct (background or weight)
- Alternating row colors using `tr:nth-child(even)` (or `odd`)
- The table has a `<caption>` that is styled (e.g. alignment, weight, spacing)

## Where to put your work

```
challenges/block-3/13-style-data-table/(your-name)/index.html
challenges/block-3/13-style-data-table/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- The table is easy to scan with zebra rows and a styled header and caption
- PR opened against `main`, linked to this issue (`Addresses #13`)

---

See [`example/`](example/) for a worked reference.
