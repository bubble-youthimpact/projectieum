# Project IEUM

Jeju support guide — simple, verified information and support services for foreign residents in Jeju.

## Structure
- `index.html` — the whole site (pages, styles and scripts).
- One folder per page (e.g. `housing/contract/payments/index.html`) so clean URLs like `/housing/contract/payments/` work when visited directly or refreshed. These are copies of the same site, generated automatically — edit the main page and regenerate rather than editing each copy.
- `404.html` — shown by GitHub Pages for any address that doesn't exist.
- `assets/` — logo files.

## Publish on GitHub Pages
1. Upload these files to the root of a repository.
2. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save.
3. The site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Editing content
- Guide text lives in the `P` object inside `index.html` (search for the page title).
- Support organisations live in the `SVC` list. Only add organisations you have verified, and update `verifiedOn`.
