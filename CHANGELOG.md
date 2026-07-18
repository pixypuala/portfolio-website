# Changelog

All notable changes to this project are documented here. The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and this project adheres
to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Repository scaffolding: governance files, docs, and CI skeleton.
- Accessible, responsive, dependency-free static portfolio site (site/index.html + styles.css): skip link, landmarks, light/dark tokens, scroll-to-top, reduced-motion support.
- Open Graph and Twitter Card metadata for rich link previews; CI smoke check now asserts they are present.
- GitHub Pages deploy workflow (`.github/workflows/deploy.yml`) publishing `site/` on push to main, with least-privilege permissions.
- CI smoke checks for a11y/SEO basics and local asset resolution.
- Per-project case-study pages under `site/case-studies/` for the flagship work (Enterprise FSE Publishing, Resilient WooCommerce, UpdateProof): same accessible template as the home page (lang, skip link, landmarks, OG/Twitter meta), honest problem/approach/what-is-built/boundary content, links back to the home page and each repository.
- On-brand `site/og-image.svg` (1200×630) referenced by absolute URL from every page's `og:image`/`twitter:image`; cards for the flagship case studies added to the home page.
- CI smoke now asserts each case-study page exists and passes the same a11y/SEO greps, and resolves local asset references relative to each page so `case-studies/` subfolder depth stays correct.
