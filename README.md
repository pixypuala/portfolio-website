# Personal Marketing System

## Getting started

A static, dependency-free site — no build step. Open `site/index.html` directly, or serve it:

```bash
python3 -m http.server --directory site 8000   # then visit http://localhost:8000
```

## What is built today

- `site/index.html` — a semantic, accessible single-page portfolio: skip link, landmark regions,
  keyboard-friendly navigation, and a progressively-enhanced scroll-to-top control.
- `site/styles.css` — token-driven styling with WCAG-AA contrast in light and dark, fluid
  typography, a responsive project grid, visible focus rings, and `prefers-reduced-motion` support.
- Content links to the five showcase projects and the extracted open-source tools, framed honestly
  as in-progress reference implementations (no fabricated metrics or testimonials).
- `site/case-studies/*.html` — per-project case studies for the flagship work (Enterprise FSE
  Publishing, Resilient WooCommerce, UpdateProof): each states the problem, approach, what is built,
  and the honest contribution boundary, reusing the same accessible template and shared styles.
- `site/og-image.svg` — an on-brand 1200×630 Open Graph/Twitter share image, referenced by absolute
  URL from every page's `og:image`/`twitter:image`.
- CI smoke-checks accessibility/SEO basics on the home page and every case study, and that every
  local asset reference resolves — including relative paths from the `case-studies/` subfolder.

## What ships now

The raster **`site/og-image.png`** (1200×630, rendered from the source `og-image.svg`) ships and is
what every page's `og:image`/`twitter:image` now references — scrapers that favour raster over vector
get a real PNG. CI asserts the PNG exists and is exactly 1200×630. The static-host deploy is a GitHub
Pages workflow (`.github/workflows/deploy.yml`) publishing `site/` on every push to `main`, and
per-project case studies live under `site/case-studies/`.

Nothing outstanding remains for this repo beyond ongoing content.

## Purpose

The portfolio website and personal-marketing layer that turns the five projects and eight open-source repositories into an evidence-led career narrative. It leads with the problems solved, not a list of technologies, and every public claim links to reproducible proof.

This system is not complete when the site looks good. It must present accessible, honest, verifiable evidence: case studies with contribution boundaries, links to demos and test artifacts, and a maintenance status for every project.

## Contents

- [`PORTFOLIO-WEBSITE.md`](PORTFOLIO-WEBSITE.md) — site positioning, required pages, case-study cards, and trust signals.
- [`GITHUB-PROFILE.md`](GITHUB-PROFILE.md) — profile README and pinned-repository strategy.
- [`LINKEDIN-AND-JOB-PLATFORMS.md`](LINKEDIN-AND-JOB-PLATFORMS.md) — platform copy aligned to the site positioning.
- [`RECRUITER-EVIDENCE-MAP.md`](RECRUITER-EVIDENCE-MAP.md) — each claim mapped to its reproducible proof.
- [`CASE-STUDY-TEMPLATE.md`](CASE-STUDY-TEMPLATE.md) — the PCAAP case-study structure reused per project.
- [`INTERVIEW-AND-APPLICATION-PACK.md`](INTERVIEW-AND-APPLICATION-PACK.md) — reusable application and interview material.
- [`TECHNICAL-WRITING-AND-TALKS.md`](TECHNICAL-WRITING-AND-TALKS.md) — writing and talk plan tied to project evidence.
- [`AGENCY-TEAM-AND-CLIENT-MARKETING.md`](AGENCY-TEAM-AND-CLIENT-MARKETING.md) — positioning for agency, team, and client audiences.
- [`NEXT-48-UPDATES.md`](NEXT-48-UPDATES.md) — sequenced backlog keeping the site and its evidence current.

## Positioning

> I build WordPress and web systems that editors can use, developers can maintain, and teams can update with evidence instead of hope.

Supported by three proof categories: publishing systems, revenue/application systems, and engineering assurance.

## Honesty rule

Never publish a claim without proof. Never invent users, revenue, conversion, accessibility conformance, performance results, or testimonials. Use measured data, clearly labeled fixtures, or an explicit "not yet validated" statement.
