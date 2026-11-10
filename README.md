# Arjav Kala — Portfolio

A static, GitHub Pages-compatible portfolio focused on applied AI engineering.

## Run locally

From the repository root, run:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000. No dependency installation or build step is needed for the redesigned page.

## Edit

- `index.html`: introduction, selected work, expandable case studies, experience, and contact information.
- `css/portfolio.css`: responsive layout, visual system, print styles, and reduced-motion support.
- `js/portfolio.js`: progressive-enhancement mobile navigation and footer year.
- `img/AK_Profile.jpeg`: existing profile photograph.
- `img/favicon.svg`: portfolio favicon.

The earlier theme's assets and build files remain in the repository for compatibility and rollback. The redesigned page does not load Bootstrap, jQuery, icon fonts, or third-party font services.

## Content notes

The redesign uses the previous portfolio and owner-provided professional context. It does not claim current employment dates where those dates have not been confirmed. Project illustrations are conceptual, not product screenshots or live demos. The contact link uses the email displayed on the original portfolio.

## Validation

Static checks passed for HTML tag nesting, unique IDs, internal anchor destinations, local asset paths, JavaScript syntax, and CSS brace balance.

Browser rendering and interaction checks are still required before merging: the local execution/browser environment disconnected during implementation. Check desktop and narrow mobile widths, image cropping, keyboard focus, menu open/close/Escape behavior, and each case-study disclosure.
