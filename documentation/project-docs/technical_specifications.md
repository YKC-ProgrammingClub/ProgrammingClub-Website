# Technical Specifications

## Tech Stack & Hosting
- **Markup:** Semantic HTML5
- **Styling:** CSS3 (custom properties, Flexbox/Grid, responsive breakpoints)
- **Scripting:** Vanilla JavaScript (ES6+)
- **Hosting:** GitHub Pages (static site hosting)
- **Join Form Delivery:** Third-party form endpoint (Web3Forms)

## Proposed Folder Structure
- `.github/` — Issue templates and pull request template
- `assets/` — Images, avatars, logos, and project screenshots
- `documentation/project-docs/` — Scope, tech specs, team assignments, roadmap
- `documentation/development-docs/` — Git workflow, commit rules, coding standards
- `src/components/` — Reusable UI fragments/templates if modularized
- `src/pages/` — Secondary HTML pages or section modules
- `src/styles/` — CSS stylesheets (base, layout, components, pages)
- `src/scripts/` — JS modules (filtering, rendering cards, form handling, nav)
- `src/data/` — Data files (e.g., `projects.js`, `members.js`, `faq.js`)
- `index.html` — Main entry point
- `contributing.md` — Contribution overview
- `README.md` — Project overview & setup

## Shared Conventions
- Agree on shared header/footer markup and CSS variables before building individual pages so styles stay consistent.
- Keep data (projects, members, FAQs) structured cleanly so UI rendering stays simple and maintainable.