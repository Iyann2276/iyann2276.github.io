# Copilot Instructions for Iyann2276 Static Site

## Project Overview
This is a simple static website project. The main files are:
- `index.html`: Main HTML file, entry point for the site
- `style.css`: Global styles for all pages
- `img/`: Contains image assets (e.g., `profile.jpg`)
- `favicon.png`, `M.jpeg`: Additional image assets

## Architecture & Patterns
- All content is rendered client-side using HTML and CSS only. No JavaScript or backend.
- Navigation bars should use semantic HTML (`<nav>`, `<ul>`, `<li>`, `<a>`) and be styled in `style.css`.
- Images are referenced with relative paths (e.g., `img/profile.jpg`).
- Keep markup clean and minimal; avoid unnecessary wrappers or divs.

## Developer Workflow
- No build step or package management; edit files directly.
- Preview changes by opening `index.html` in a browser.
- No automated tests or scripts; manual verification only.

## Conventions
- Use semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<footer>`) where possible.
- CSS should be placed in `style.css` only; avoid inline styles.
- All links should use relative paths unless linking to external sites.
- Keep file and folder names lowercase and descriptive.

## Examples
- To add a navigation bar, insert a `<nav>` block in `index.html` and style it in `style.css`.
- To add an image, place it in `img/` and reference it with `<img src="img/filename.jpg">`.

## Key Files
- `index.html`: Main structure and content
- `style.css`: All styling rules
- `img/`: All image assets

---
For questions about project structure or conventions, check this file and the root `README.md`.
