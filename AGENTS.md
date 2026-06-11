# AI Agent Guidance for jideedu.github.io

## Project purpose

This repository is a static portfolio website built from a Bootstrap template. There is no frontend build system, package manager, or backend framework in use.

## Key files and directories

- `index.html` — main page markup and site structure.
- `css/` — stylesheet assets, including `style.css` for custom theme changes.
- `js/` — client-side behavior and plugin scripts.
- `fonts/` and `img/` — static assets used by the template.
- `submit.php` — contact form submission endpoint.

## What an agent should do

- Make edits directly in the existing HTML/CSS/JS files.
- Preserve the Bootstrap template structure and avoid introducing unnecessary build tooling.
- Keep changes compatible with plain GitHub Pages-style hosting.
- Use `README.md` and `readme.txt` only as reference documentation for the site origin and licensing.

## What to avoid

- Do not assume a Node/npm workflow or add package manager config unless the user explicitly requests it.
- Do not remove or rewrite template credits/licensing information without explicit instruction.
- Do not add unrelated backend services; this is a small static site with a single PHP contact endpoint.

## Deployment context

This repository is best deployed as a static site, e.g. GitHub Pages. There is no automated build step to run.
