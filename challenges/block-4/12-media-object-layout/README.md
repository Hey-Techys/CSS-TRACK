# Issue #12 — Build a media object: image beside text that stacks on mobile

**Tier:** Intermediate (3pt)

## What to build

Build a list of 3 "media objects" — e.g. testimonials or blog previews — each with an avatar image beside a block of text. They stack on small screens and sit side by side on larger ones.

## Requirements

- Each media object is a flex container with an image and a text block
- The image keeps its size (`flex-shrink: 0`) while the text block takes the remaining space (`flex: 1`)
- Base (mobile) styles stack image above text; a `min-width` query puts them side by side
- Images have `alt` text and use `border-radius`; `align-items` is used to control vertical alignment

## Where to put your work

```
challenges/block-4/12-media-object-layout/(your-name)/index.html
challenges/block-4/12-media-object-layout/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- Image and text sit side by side on desktop and stack on mobile without squashing the image
- PR opened against `main`, linked to this issue (`Addresses #12`)

---

See [`example/`](example/) for a worked reference.
