# Nadiyah Ahmad — Product Portfolio

Personal product management portfolio. Case studies on systems I've built and interfaces I've studied, plus resume and contact info.

**Live site:** https://nad1yah.github.io

## Tech stack

Vanilla HTML, CSS, and JavaScript. No framework, no build step, no dependencies beyond two Google Fonts imports. Kept intentionally simple so it's fast, easy to maintain, and easy for anyone to read the source.

## Structure

```
.
├── index.html      # all page content and structure
├── style.css       # design tokens, layout, responsive rules
├── script.js       # mobile nav toggle + active-section highlighting on scroll
└── README.md
```

Each case study lives in `index.html` as a `<article class="proj">` block with a short teaser paragraph and a `<details>` element holding the full write-up — expand/collapse works natively with no JS required.

## Local development

No build step. Clone the repo and open `index.html` directly in a browser, or serve it locally:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Branching

- `main` — deployed branch, reflects the live site
- `dev` — active work; merged into `main` once changes are reviewed

## Deployment

Hosted on GitHub Pages, deployed from `main` at the repo root. To publish updates:

1. Open a PR from `dev` into `main`
2. Review and merge
3. GitHub Pages rebuilds automatically within a minute or two

## To do

- [ ] Swap placeholder email/LinkedIn/GitHub links in the Contact section
- [ ] Add resume PDF and wire up the download link
- [ ] Add a headshot/photo if desired
