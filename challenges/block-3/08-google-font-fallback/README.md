# Issue #8 — Add a Google Font with a fallback font stack

**Tier:** Beginner (1pt)

## What to build

Load a font from Google Fonts and use it for your headings, with a sensible fallback stack in case it fails to load.

## Requirements

- Font is loaded with a `<link>` in `<head>` (from fonts.googleapis.com)
- Headings use the Google Font, followed by at least one fallback and a generic family (e.g. `"Poppins", Arial, sans-serif`)
- Body text uses a different font stack from the headings
- Only the font weights you actually use are requested

## Where to put your work

```
challenges/block-3/08-google-font-fallback/(your-name)/index.html
challenges/block-3/08-google-font-fallback/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- Headings use the web font with a working fallback stack
- PR opened against `main`, linked to this issue (`Addresses #8`)

---

See [`example/`](example/) for a worked reference.
