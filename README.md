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
| `bio.html` | Short personal biography |
| `assets/css/style.css` | All styling. Colours and fonts are variables at the top (`:root`) |
| `assets/img/` | Profile photo and favicon |
| `files/` | CV and paper PDFs |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

The header, sidebar and footer are repeated in the four HTML pages. If you change a link there
(e.g. add Google Scholar), change it in all four.

## Pending items

Search the code for `TODO` — every placeholder is marked, and shows on the page with a yellow highlight
until it is replaced.

1. **CV** – upload the public version as `files/CV_Jimenez_Amaya.pdf`.
2. **Job market paper** – title, abstract, keywords, and the PDF (e.g. `files/Jimenez_JMP.pdf`; point the
   "Latest version" button to it).
3. Work in progress entries and the expected PhD completion year (About → Education).

To change the photo, replace `assets/img/profile.jpg` (portrait, 4:5, e.g. 640 × 800 px).

## Adding a publication

Copy one `<li>` block inside `<ul class="pubs">` in `research.html` and edit title, authors, journal and links.
The abstract opens and closes with the `<details>` element; no JavaScript is involved.

## Publishing

In the repository settings → *Pages*, set **Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
