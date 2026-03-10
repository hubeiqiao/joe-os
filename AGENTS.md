# AGENTS.md

This repository is the public curated package for Joe Hu. It is for AI and human orientation, not for backing up the full private archive. The full archive backup lives separately in the private repo `hubeiqiao/joe-archive-private`.

## Allowed Content

- `ai-memory/`: public-safe summaries, memory cards, and landscape docs
- `sources/company/`: sanitized snapshots that map to public company pages
- `sources/product/`: sanitized snapshots that map to public product pages
- `sources/personal-website/`: sanitized snapshots that map to public personal-site pages
- `README.md` and `PUBLIC_SOURCES.md`

## Forbidden Content

- anything from the private `Social Media/` archive
- any `non-corpus/` material
- raw exports, zip files, tokens, cookies, or other secrets
- internal applications, planning notes, or private operational documents
- absolute local filesystem paths unless intentionally sanitized away before commit

## Maintenance Rules

- Prefer canonical public URLs over copied exports where possible.
- Keep metrics date-scoped and conservative when sources disagree.
- Do not add local-only evidence or internal-only claims to this repo.
- Treat this repo as a curated subset, not a mirror of `/Users/joehu/Joe`.
- If a file references a local path, secret-like token, or raw export artifact, sanitize it before commit.
- If a change is meant to preserve the full archive or includes private source material, it belongs in `joe-archive-private`, not here.
