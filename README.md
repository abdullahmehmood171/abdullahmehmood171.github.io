# Abdullah Mehmood Khichi — Portfolio

Personal portfolio website, built with plain HTML and CSS (no framework, no build step, no JavaScript) and hosted on GitHub Pages.

Parts of this website and the corrected bond workbook were produced with AI assistance; see the AI-use disclosure on the bond case-study page.

**Live site:** https://abdullahmehmood171.github.io

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | Homepage: introduction, skills, projects |
| `projects/bond-duration.html` | Bond Duration & Interest-Rate Analysis case study |
| `projects/triptic.html` | Triptic case study |
| `styles.css` | All styling; colors and widths are variables at the top |
| `favicon.svg` | AMK monogram icon |
| `downloads/bond_duration_reviewed.xlsx` | Corrected bond workbook (synthetic data, AI-assisted corrections) |

## Editing

1. Edit the HTML directly. Each section is labelled and the text is plain.
2. Preview locally by opening `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.
3. Commit and push to `main`. GitHub Pages republishes automatically within a minute or two.

To add a project, copy one `<article class="project">` block in `index.html` and one case-study page in `projects/`, then update the links.
