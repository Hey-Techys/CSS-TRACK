# Issue #11 — Fix a stylesheet with specificity conflicts

**Tier:** Intermediate (3pt)

## What to build

The stylesheet below has rules that don't apply the way the author expected because of specificity. Copy it into your folder with matching HTML, fix it **without using `!important`**, and explain each fix in a CSS comment.

```css
#intro p { color: gray; }
.lead { color: navy; }            /* expected: lead paragraph is navy */
#main-nav a { color: black; }
.active { color: orange; }        /* expected: active link is orange */
p { font-size: 1rem !important; }
.small { font-size: 0.8rem; }     /* expected: .small text is smaller */
```

## Requirements

- The `.lead` paragraph inside `#intro` displays navy
- The `.active` nav link displays orange
- `.small` text is smaller, and `!important` is removed from the stylesheet entirely
- A CSS comment beside each fix explains the specificity problem (e.g. "ID beats class")

## Where to put your work

```
challenges/block-3/11-fix-specificity-conflicts/(your-name)/index.html
challenges/block-3/11-fix-specificity-conflicts/(your-name)/style.css
```

## Definition of done

- Builds and displays correctly in a browser
- All three conflicts are fixed without !important and explained in comments
- PR opened against `main`, linked to this issue (`Addresses #11`)

---

See [`example/`](example/) for a worked reference.
