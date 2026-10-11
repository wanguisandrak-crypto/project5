# Copilot instructions

## Build, test, and lint

- There is no build system, package manifest, test runner, or linter configured.
- Preview the site by opening `index.html` in a browser; no build step is needed.
- There is no configured command for running a single test.

## Architecture

- This repository is a plain, single-page HTML/CSS site with `index.html` as its entry point.
- `style.css` is the stylesheet file, but it is currently empty and is not linked from `index.html`.
- There is no JavaScript, framework, asset pipeline, or other application layer currently in the repository.

## Repository conventions

- Keep page markup in `index.html` and page styling in `style.css`; if adding styles, link the stylesheet from the page.
- The document currently declares English (`lang="en"`), a responsive viewport, and the `scroll-smooth` class on the root `<html>` element. Preserve these existing document-level settings when editing the page.
- `readme.md` is currently empty and does not define additional project setup or contribution instructions.
