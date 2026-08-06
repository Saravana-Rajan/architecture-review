# ClimatePros — Architecture Review

Design and review documents for the FieldJetX auto-dispatch work (Techjays).

**Published:** https://saravana-rajan.github.io/architecture-review/

## Pages

| Page | Contents |
|---|---|
| [`index.html`](index.html) | Landing page — links to every document |
| [`dispatch-configuration.html`](dispatch-configuration.html) | **Use Case A — Dispatch Configuration.** ER diagram, field-by-field schema for all four tables (two reference, two config), the API contract with request/response examples, and the reasoning behind every column that was removed |
| [`spec-review-stream1.html`](spec-review-stream1.html) | **Stream 1 Unified Architecture review (round 2).** 13 areas scored, 49 findings, overall 7.2/10 |

> `spec-review-stream1.html` was previously served at the site root as `index.html`.
> It moved so the root could become a hub linking to every document; its content is unchanged.

## Publishing

GitHub Pages is already enabled on `main` → `/ (root)`. Pushing to `main` republishes
the site within about a minute.

Pages are plain HTML with inline CSS and inline SVG — no build step, no external
dependencies, so they render exactly as they do when opened locally.
