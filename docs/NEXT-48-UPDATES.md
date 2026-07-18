# Next 48 Updates — 07-PERSONAL-MARKETING-SYSTEM

## Why this file exists

This is a sequenced, honest backlog of at least 48 planned updates that keeps the portfolio website and personal-marketing system genuinely active over time. Each item is a real unit of work (one issue or pull request) that advances positioning, content, accessibility, performance, SEO, privacy, or maintenance — not artificial busywork. Items are ordered so that early work unblocks later work, and grouped into six release milestones. Nothing here is claimed as already done: this is the forward plan.

## How to use it

Convert each checkbox into a tracked issue, attach it to the matching milestone, and close it with the pull request that satisfies it. Aim for a steady cadence (for example one to three items per week) so commit history, releases, and changelog entries reflect continuous, verifiable progress. Re-open or add items whenever a project ships new evidence, positioning changes, or analytics/user feedback surface new work.

Total planned updates: **48** across **6** milestones.

## M1 — v0.1 Foundations & scaffolding

- [ ] **#01** Scaffold the portfolio site (framework, tokens, build pipeline) with a documented style layer
- [ ] **#02** Define the design-token layer (color, spacing, type) with WCAG contrast rules for light/dark
- [ ] **#03** Build the site information architecture: Home, Work, Open Source, Standards, Writing, About, Contact
- [ ] **#04** Establish the positioning statement and three proof categories on the Home page
- [ ] **#05** Set up local dev environment and content model for case studies (PCAAP fields)
- [ ] **#06** Add linting, formatting, type-checking, and a pre-commit hook
- [ ] **#07** Add CI that lints, builds, and runs a link-check on every pull request
- [ ] **#08** Publish an initial ADR set covering hosting, rendering strategy, and analytics/privacy choice

## M2 — v0.2 Core capability

- [ ] **#09** Build the Work index with five PCAAP case-study cards (problem, evidence, contribution, stack, status)
- [ ] **#10** Build the case-study detail template linking demo, repo, architecture, and test evidence
- [ ] **#11** Publish the Enterprise FSE Publishing Platform case study
- [ ] **#12** Publish the Resilient WooCommerce Commerce System case study
- [ ] **#13** Build the Open Source page pulling repositories, releases, and maintenance status
- [ ] **#14** Build the Engineering Standards page (accessibility, security, performance, testing, privacy, AI policy)
- [ ] **#15** Build an accessible contact form with spam protection and a stated response boundary
- [ ] **#16** Add a recruiter evidence map linking claims to reproducible proof

## M3 — v0.3 Testing, evidence & negative proof

- [ ] **#17** Add axe-core automated accessibility tests across all page templates
- [ ] **#18** Add keyboard-navigation and focus-visible tests for nav, forms, and interactive cards
- [ ] **#19** Add a broken-link and orphaned-asset check as a release gate
- [ ] **#20** Add visual regression snapshots across themes and breakpoints
- [ ] **#21** Add unit tests for the case-study data model and PCAAP field validation
- [ ] **#22** Create an evidence index mapping each public claim to its source or fixture
- [ ] **#23** Add a contact-form submission test (validation, error states, success state)
- [ ] **#24** Add screen-reader test notes (NVDA/VoiceOver) for the primary navigation and forms

## M4 — v0.4 Security, compatibility & performance

- [ ] **#25** Run a manual WCAG 2.2 AA audit of every page and record findings
- [ ] **#26** Add reduced-motion and prefers-contrast support with tests
- [ ] **#27** Add Core Web Vitals performance budgets enforced in CI
- [ ] **#28** Optimize and lazy-load images/media with explicit dimensions to prevent layout shift
- [ ] **#29** Add a Content-Security-Policy and security headers with a documented baseline
- [ ] **#30** Implement privacy-respecting analytics with a clear privacy policy and no PII leakage
- [ ] **#31** Define a browser and device support matrix and test the oldest supported set
- [ ] **#32** Add dependency and license scanning to CI

## M5 — v0.5 Content, SEO & discovery

- [ ] **#33** Add structured data (Person, CreativeWork, BreadcrumbList) and validate it
- [ ] **#34** Add canonical URLs, sitemap, robots, and per-page meta/OG/Twitter tags
- [ ] **#35** Publish the Hybrid Content Delivery, Design System, and UpdateProof case studies
- [ ] **#36** Build the Writing/Talks section and publish the first technical article
- [ ] **#37** Add an RSS/Atom feed for writing and release notes
- [ ] **#38** Refresh the GitHub profile README and pin the strongest repositories
- [ ] **#39** Sync LinkedIn and job-platform copy with the site positioning and evidence links
- [ ] **#40** Add a downloadable, accessible resume/CV generated from a single source of truth

## M6 — v1.0+ Cadence, outreach & maintenance

- [ ] **#41** Adopt semantic versioning for the site and an automated changelog
- [ ] **#42** Add protected-branch release automation with a preview-then-promote deploy flow
- [ ] **#43** Set a quarterly cadence to refresh case-study evidence and maintenance statuses
- [ ] **#44** Add a quarterly accessibility and performance re-audit to the roadmap
- [ ] **#45** Build the interview-and-application pack as a reusable, versioned document set
- [ ] **#46** Add an outreach log and follow-up cadence tied to the recruiter evidence map
- [ ] **#47** Add a demo-reel/screenshot pipeline that regenerates from the live projects
- [ ] **#48** Schedule recurring dependency-update and content-freshness reviews

## Honesty note

These updates are planned, not completed. They do not assert the site is already built, adopted, ranked, or that any project claim is validated. They describe the intended, testable path of work and the cadence for keeping the portfolio and its evidence current.
