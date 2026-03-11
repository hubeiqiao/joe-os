# Repo Boundary and Publish Policy

Last reviewed: March 11, 2026

## Purpose

- Joe maintains two repos with different roles:
  - `joe-archive-private`: the full private archive and source of truth
  - `joe-os`: the public curated subset
- This repo exists for public orientation, not for full-archive backup.

## Core Rule

- Create and preserve source material in the private archive first.
- Publish only reviewed public-safe outputs to `joe-os`.
- Do not treat `joe-os` as a mirror of the private archive.

## What Belongs Here

- Public-safe memory and landscape docs
- Sanitized snapshots from already-public company, product, and personal-site sources
- Public repo docs such as `README.md`, `PUBLIC_SOURCES.md`, and `AGENTS.md`

## What Does Not Belong Here

- Anything from the private social-media archive
- Internal applications
- Private planning notes
- Raw exports or platform dumps
- Secrets, tokens, cookies, or unpublished private evidence
- Local filesystem paths unless intentionally sanitized

## Publish Workflow

1. Start in the private archive.
2. Decide whether the material is public-safe.
3. Rewrite or sanitize as needed.
4. Copy only the curated public-safe version into `joe-os`.
5. Commit and push the private and public repos separately.

## Working Principle

- The private repo is the archive.
- The public repo is the interface.
- The archive can hold the full source history.
- The interface should contain only what is intentionally public.
