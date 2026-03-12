# The Center FAIRNESS

Center for Advanced Integrated Research on Network and Embedded System Security  
Departemen Teknik Elektro, Fakultas Teknik, Universitas Indonesia

Static site for **https://fairness-ui.github.io/** — plain HTML and CSS, no build step.

## Structure

| Page | URL |
|------|-----|
| Home | `/` or `/index.html` |
| Research Team | `/team/research-team.html` |
| Doctoral / Master / Bachelor Student | `/team/doctoral-student.html` etc. |
| Alumni | `/alumni.html` |
| Research | `/research.html` |
| Publications | `/publications.html` |
| Contacts | `/contacts.html` |

## Publish to GitHub Pages

1. Push this repo to `https://github.com/fairness-ui/fairness-ui.github.io`
2. **Settings → Pages**: Source = **Deploy from a branch**
3. Branch = **main** (or **master**), folder = **/ (root)**
4. Save. The site will be at **https://fairness-ui.github.io/**

## Local preview

Open `index.html` in a browser, or run a local server:

```bash
cd fairness-ui.github.io
python -m http.server 8000
```

Then open http://localhost:8000
