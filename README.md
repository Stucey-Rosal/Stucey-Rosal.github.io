# StuceyOS — Portfolio

An interactive macOS-style desktop portfolio for **Stucey Rosal**,
AI Automation Specialist under Huggy Bear Digital.

Single-file, no framework, no build step.

- `index.html` — the whole site (markup, styles, and JS in one file)
- `assets/projects/*.jpg` — project covers, designed in Figma (1600x1000)
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Running locally

Open `index.html` in a browser, or serve it so relative paths resolve:

    python -m http.server 8765

Then visit http://localhost:8765

## Adding a project

Add one object to the `PROJECTS` array in `index.html`. Numbering,
the gallery, Spotlight search, and the Terminal `projects` command all
pick it up automatically.

Set `draft:true` on an entry to mark it unfinished — it renders an amber
DRAFT badge and a warning banner until the write-up is real.

## Resume

Drop `Resume.pdf` in the repo root to enable the Download button in the
Preview window. Without it the button hides itself rather than 404ing.
