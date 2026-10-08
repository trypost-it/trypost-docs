# TryPost docs — agent instructions

Read `CLAUDE.md` in this repo first; it is the single source of rules (URL architecture, frozen URLs, Cloud-first writing, OpenAPI flow, Knowledge Base groups, redirects). Everything below is a summary.

- Mintlify site: pages are MDX with YAML frontmatter; navigation, `openapi` and `redirects` live in `docs.json`.
- Preview with `mint dev`; check with `npx mint validate` and `npx mint broken-links`.
- Never rename or remove the frozen URLs listed in `CLAUDE.md`; every moved or removed slug gets a `docs.json` redirect.
- Every factual claim must trace to the app at `~/Herd/trypost` (cite `file:line` in the PR).
- Use active voice, second person, sentence-case headings, bold for UI labels exactly as in `lang/en/*.php`.
