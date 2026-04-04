# Public Source Map

Last updated: 2026-04-04

Purpose: define which parts of this repo are public raw sources versus public synthesis.

## Public Raw Source Layer

- `sources/company/` - sanitized snapshots from public company-facing materials
- `sources/product/` - sanitized snapshots from public product-facing materials
- `sources/personal-website/` - sanitized snapshots from public personal-site pages

## Public Memory Layer

- `ai-memory/` - public-safe summaries and landscape docs that help orient future AI sessions

## Public Wiki Layer

- `wiki/` - persistent public markdown synthesis maintained incrementally

## Maintenance Rule

When a new public-safe source is added:

1. Put it in the matching `sources/` folder.
2. Update relevant pages in `wiki/`.
3. Update `wiki/index.md` if the page catalog changes.
4. Append a dated entry to `../log.md` when the public wiki changes materially.
