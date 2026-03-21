# al-folio Preview — Walid Iguider

This is a preview of the al-folio theme configured with your content.

## How to test locally

### Option 1: Docker (recommended)

```bash
cd al-folio-preview
docker compose pull
docker compose up
```

Then visit: http://localhost:8080

### Option 2: Ruby/Bundler

```bash
cd al-folio-preview
bundle install
bundle exec jekyll serve
```

Then visit: http://localhost:4000

## What's configured

- **About page** (`_pages/about.md`) — your bio, profile pic, social links
- **Publications** (`_bibliography/papers.bib`) — 3 papers in BibTeX format with abstracts and links
- **CV** (`_data/cv.yml`) — full work history, education, awards
- **News** (`_news/`) — 3 career milestone announcements
- **Config** (`_config.yml`) — Google Scholar, ORCID, ResearchGate, GitHub, X, LinkedIn

## Content to review

1. Profile image: currently using `images/profile.png` from the old site
2. News items: add more career milestones as needed
3. Projects: `_projects/` folder is empty — add project cards if desired
4. Blog posts: `_posts/` folder is empty — add posts if desired

## Migration steps (when ready)

1. Review this preview and confirm you're happy with the content
2. Replace the root site files with the al-folio structure
3. Update GitHub Actions workflow for deployment (`.github/workflows/deploy.yml`)
4. Push to main branch
