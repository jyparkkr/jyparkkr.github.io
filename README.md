# jyparkkr.github.io

Personal homepage of Jaeyoung Park, served by GitHub Pages at https://jyparkkr.github.io/.

- `index.html`, `style.css`: the single-page site
- `cv/`: redirect page for the CV; `files/cv.pdf` is the CV itself
- `cv-src/cv.tex`: LaTeX source of the CV (build with `latexmk -pdf cv.tex`, then copy the PDF to `files/cv.pdf`)

The site is plain static files; `.nojekyll` tells GitHub Pages to serve them as-is.
