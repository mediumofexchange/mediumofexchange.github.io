# Medium of Exchange website

Source for [mediumofexchange.org](https://mediumofexchange.org), the project
overview linking the paper, protocol specification and TypeScript reference.

This repository contains a static HTML page with inline styles, no dependencies
and no build step.

| File | Purpose |
|---|---|
| [index.html](index.html) | Page content and styles. Open locally to preview. |
| [CNAME](CNAME) | Custom domain used by GitHub Pages. |
| [.nojekyll](.nojekyll) | Serves the files without Jekyll processing. |

## Editing

Keep the overview concise and link detailed implementation status to
[reference-ts](https://github.com/mediumofexchange/reference-ts). The paper and
normative protocol live in
[money-from-first-principles](https://github.com/mediumofexchange/money-from-first-principles).

Preview changes locally and check links before publishing. GitHub Pages serves
the `main` branch; pushing there publishes the site and requires deployment
authorization under the workspace rules.

## Licence

[CC0 1.0 Universal](LICENSE) — public domain dedication.
