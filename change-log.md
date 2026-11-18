# Change log

## 2026-11-18 02:23:09 PST (UTC−08:00)

Request: Patch the documentation site's transitive Zod dependency for [GHSA-mrhx-c7xc-m3w5](https://github.com/advisories/GHSA-mrhx-c7xc-m3w5) without changing direct dependencies.

- `site/package-lock.json` — updated the shared Zod resolution for Astro and its sitemap plugin from 4.4.3 to 4.6.7, the patched follow-up release with npm provenance.
- `CHANGELOG.md` — recorded the docs-site build security fix in the unreleased notes.
