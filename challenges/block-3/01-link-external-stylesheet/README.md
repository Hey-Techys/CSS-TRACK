# Issue #1 — Link an external stylesheet and set base page styles

**Tier:** Beginner (1pt)

## What to build

Create an HTML page and a separate `style.css` file. Link the stylesheet in the `<head>` and use it to set the page's base font, text color and background color.

## Requirements

- CSS lives in a separate `style.css` file — no `<style>` tags or inline `style=""` attributes
- Stylesheet is linked with `<link rel="stylesheet" href="style.css">` inside `<head>`
- `body` sets `font-family` (with a generic fallback like `sans-serif`), `color` and `background-color`
- Page has at least a heading and two paragraphs so the styles are visible

## Where to put your work

```
challenges/block-3/01-link-external-stylesheet/(your-name)/index.html
challenges/block-3/01-link-external-stylesheet/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- All styling comes from the linked `style.css`
- PR opened against `main`, linked to this issue (`Addresses #1`)

---

See [`example/`](example/) for a worked reference.
