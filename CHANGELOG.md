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
