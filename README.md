# mariacjimeneza.github.io

Personal academic website of María Camila Jiménez Amaya, served by GitHub Pages at
<https://mariacjimeneza.github.io>.

Plain HTML and CSS — no Jekyll, no build step. Edit a file, commit, and the site updates in a minute or two.

## Files

| File | What it holds |
|---|---|
| `index.html` | About page: bio, job-market note, research interests, education, contact |
| `research.html` | Job market paper, work in progress, publications, reports, presentations |
| `teaching.html` | Teaching experience grouped by institution |
| `assets/css/style.css` | All styling. Colours and fonts are variables at the top (`:root`) |
| `assets/img/` | Profile photo and favicon |
| `files/` | CV and paper PDFs |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

The header, sidebar and footer are repeated in the three HTML pages. If you change a link there
(e.g. add Google Scholar), change it in all three.

## Pending items

Search the code for `TODO` — every placeholder is marked, and shows on the page with a yellow highlight
until it is replaced.

1. **Photo** – save as `assets/img/profile.jpg` (portrait, roughly 800 × 1000 px) and follow the comment
   above the `portrait placeholder` div in each page.
2. **CV** – upload the public version as `files/CV_Jimenez_Amaya.pdf`.
3. **Job market paper** – title, abstract, keywords, and the PDF (e.g. `files/Jimenez_JMP.pdf`; point the
   "Latest version" button to it).
4. Dissertation sentence and supervisors (About page), PhD expected year, job-market season.
5. ORCID / Google Scholar links (commented out in the sidebar).

## Adding a publication

Copy one `<li>` block inside `<ul class="pubs">` in `research.html` and edit title, authors, journal and links.
The abstract opens and closes with the `<details>` element; no JavaScript is involved.

## Publishing

In the repository settings → *Pages*, set **Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
