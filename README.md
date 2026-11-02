# Personal CV Website

Source of my personal resume website, built with **Hugo** and available in English, German and Portuguese.

**Live:** https://site-curriculo-sisinfo-bhfpaschoal-2fc8d5249990d3d82c5dfbd4cb72.e.usp.br/

## What's inside

- Resume: education (TUM M.Sc., USP double degree), experience, projects and certifications
- Expertise pages (optimization, machine learning, robotics) with linked papers
- Three languages: English at the root, German at `/de/`, Portuguese at `/pt/`, with a language switch on every page

## How it works

- `content/` has one Markdown file per page and language (`resume.md`, `resume.de.md`, `resume.pt.md`)
- `i18n/` holds the short UI strings per language
- `layouts/` holds the custom Hugo templates
- `static/` holds images and the paper PDFs
- `.gitlab-ci.yml` rebuilds the site with Hugo and publishes it to GitLab Pages on every push to `master`

## Run locally

```bash
hugo server
```

Then open http://localhost:1313.
