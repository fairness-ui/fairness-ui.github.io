# The Center FAIRNESS

**Center for Advanced Integrated Research on Network and Embedded System Security**  
Departemen Teknik Elektro, Fakultas Teknik, Universitas Indonesia

This site uses the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and is built for **https://fairness-ui.github.io/**.

## Structure

Content is provided as **Markdown (`.md`)** files:

| Section | Path | URL |
|--------|------|-----|
| Home | `_pages/about.md` | `/` |
| Team Member (dropdown) | `_pages/team.md` | `/team/` |
| Research Team | `_pages/team/research-team.md` | `/team/research-team/` |
| Doctoral / Master / Bachelor Student | `_pages/team/*.md` | `/team/doctoral-student/` etc. |
| Alumni | `_pages/alumni.md` | `/alumni/` |
| Research | `_pages/research.md` | `/research/` |
| Publications | `_pages/publications.md` | `/publications/` |
| Contacts | `_pages/contacts.md` | `/contacts/` |

- **News:** `_news/*.md`
- **Publications (BibTeX):** `_bibliography/papers.bib`
- **Blog posts (optional):** `_posts/*.md`

## Build and deploy on GitHub Pages

1. Push this repo to `https://github.com/fairness-ui/fairness-ui.github.io`.
2. In the repo: **Settings → Pages**  
   - Source: **Deploy from a branch**  
   - Branch: **gh-pages** (the workflow deploys there)  
   - Folder: **/ (root)**  
   If the repo is `fairness-ui.github.io`, the site will be at **https://fairness-ui.github.io/**.
3. Enable **Actions** and ensure the **Deploy site** workflow has run at least once (e.g. after the first push to `main`).
4. Give **Settings → Actions → General → Workflow permissions**: **Read and write permissions**.

The theme is loaded via `remote_theme: alshedivat/al-folio` in `_config.yml`; no need to copy theme files into this repo.

## Local build

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000 (or the URL Jekyll prints). For a production build:

```bash
JEKYLL_ENV=production bundle exec jekyll build
```

Output is in `_site/`.

## Customization

- **Site title, description, footer:** `_config.yml` (top section).
- **Navigation and new pages:** add or edit files in `_pages/`; use `nav: true` and `nav_order` for menu order.
- **Publications:** edit `_bibliography/papers.bib` and optionally scholar settings in `_config.yml`.
