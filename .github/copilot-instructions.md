# Copilot Instructions for YixShao.github.io (Hugo Blox Academic CV)

## Project Overview
- **Purpose:** Academic CV and portfolio site built with [Hugo Blox](https://hugoblox.com/), using the Academic CV template.
- **Content:** Markdown, Jupyter Notebooks, and YAML files for site content and configuration.
- **Build System:** Hugo Extended (static site generator), managed via `pnpm` for JS dependencies.

## Key Structure
- `content/` — Main site content (Markdown, Notebooks, publications, blog, courses, etc.)
- `config/_default/` — Site configuration (YAML: `hugo.yaml`, `params.yaml`, etc.)
- `assets/` — Custom JS, CSS, and media assets
- `layouts/` — Custom Hugo templates/partials
- `static/` — Static files (uploads, images)
- `public/` — Build output (do not edit directly)
- `data/` — Structured data (YAML, e.g., author profiles)

## Developer Workflows
- **Local development:**
  ```bash
  pnpm install && hugo server
  ```
  - Site runs at `http://localhost:1313/`
- **Build output:**
  - Generated in `public/` by Hugo; do not manually edit this folder.
- **Content authoring:**
  - Use Markdown (`.md`) for most content.
  - Jupyter Notebooks (`.ipynb`) supported in some sections (e.g., `content/blog/notebook-onboarding/`).
  - YAML for configuration and data (e.g., `config/_default/`, `data/authors/`).
- **Configuration:**
  - Main site settings: `config/_default/hugo.yaml`, `params.yaml`
  - Menus, languages, modules: other YAML files in `config/_default/`
- **Custom assets:**
  - Place custom JS/CSS in `assets/`.
  - Use `static/` for files that should be served as-is (e.g., images, uploads).

## Conventions & Patterns
- **Do not edit `public/` directly.**
- **Content organization:**
  - Each major section (blog, courses, projects, etc.) has its own folder under `content/`.
  - Use `_index.md` for section landing pages.
- **Author profiles:**
  - Defined in `data/authors/` (YAML) and `content/authors/` (Markdown).
- **Custom layouts:**
  - Use `layouts/_partials/` for Hugo partials/hooks.
- **Media:**
  - Store author images and icons in `assets/media/authors/` and `assets/icons/`.

## External Integrations
- **Hugo Blox Builder:** Drag-and-drop site builder (optional, see [docs](https://docs.hugoblox.com/)).
- **Netlify:** Deployment config in `netlify.toml` (if used).

## Examples
- See `content/blog/data-visualization/` for a section with Markdown, JSON, and CSV data.
- See `content/blog/notebook-onboarding/` for Jupyter Notebook integration.

---
For more, see [README.md](../README.md) and [Hugo Blox Docs](https://docs.hugoblox.com/).
