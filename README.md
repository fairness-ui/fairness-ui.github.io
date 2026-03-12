# The Center FAIRNESS

Center for Advanced Integrated Research on Network and Embedded System Security  
Departemen Teknik Elektro, Fakultas Teknik, Universitas Indonesia

Simple static site for GitHub Pages. Placeholder structure only; content can be filled in later.

## Structure

- **Home** (`index.html`)
- **Team Member** (submenu)
  - Research Team (`team/research-team.html`) – sample page with chair and members
  - Doctoral Student, Master Student, Bachelor Student – placeholders
- **Alumni**, **Research**, **Publications** – placeholders
- **Contacts** – basic contact info from ee.ui.ac.id

## Run locally

Open `index.html` in a browser, or use a simple server, e.g.:

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

## GitHub Pages

1. Create a repo named `fairness-ui.github.io` (or your org/username).
2. Push this folder to the repo.
3. In repo **Settings → Pages**, set source to main branch (root or /docs if you use a docs folder).
4. Site will be at `https://fairness-ui.github.io` (or your repo URL).

## Team photos

Research Team page uses [UI Avatars](https://ui-avatars.com) for placeholder images. Replace with real photos from [ee.ui.ac.id/research-group/the-fairness](https://ee.ui.ac.id/research-group/the-fairness/) by saving images to e.g. `team/images/` and updating the `src` in `team/research-team.html`.
