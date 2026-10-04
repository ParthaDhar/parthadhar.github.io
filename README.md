# cv.parthadhar.com

Source of the CV page served by GitHub Pages from this branch. One hand-written `index.html` with its CSS inline, two self-hosted Carlito fonts (SIL OFL 1.1, see `assets/fonts/LICENSE.txt`), no build step.

`dl/Partha-Dhar-CV.pdf` is generated from the page, never edited by hand: `google-chrome --headless=new --no-pdf-header-footer --print-to-pdf=dl/Partha-Dhar-CV.pdf file://$PWD/index.html`.
