# shreyasmily.github.io

Personal landing page — projects, technical writing, and short fiction. Served by GitHub Pages at
https://shreyasmily.github.io.

Plain HTML/CSS, no build step. `index.html` is the whole page; `styles.css` holds the styling
(light/dark mode via `prefers-color-scheme`).

To edit:
- **Bio/tagline**: top of `index.html`, inside `<header class="hero">`.
- **Projects**: each is an `<article class="entry">` under `#projects` in `index.html`.
- **Substack link**: the placeholder `<a href="#">Read on Substack →</a>` under `#fiction` — replace
  the `#` with your actual Substack URL.
- **Colors**: CSS custom properties at the top of `styles.css` (`:root` for light mode, the
  `prefers-color-scheme: dark` block below it for dark mode).

No GitHub Pages build config needed — a `<username>.github.io` repo is served automatically from the
default branch root once Pages is enabled in the repo's Settings → Pages.
