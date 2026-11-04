# CV (source of truth)

Edit the `.tex` files here. Pushing to `main` runs `.github/workflows/build-cv.yml`,
which rebuilds the PDFs in this folder.

The portfolio site
([AbdelrahmanElsaidElsawy.github.io](https://github.com/AbdelrahmanElsaidElsawy/AbdelrahmanElsaidElsawy.github.io))
syncs only the PDFs — do not keep a second copy of the LaTeX there.

| Source | Variant | PDF |
| --- | --- | --- |
| `cv.tex` | English designed (color + LinkedIn QR) | `Abdelrahman_Elsaid_Elsawy_CV.pdf` |
| `cv_ats.tex` | English ATS (plain one-column) | `Abdelrahman_Elsaid_Elsawy_CV_ATS.pdf` |
| `cv_de.tex` | German designed | `Abdelrahman_Elsaid_Elsawy_CV_DE.pdf` |
| `cv_tr.tex` | Turkish designed | `Abdelrahman_Elsaid_Elsawy_CV_TR.pdf` |

Designed versions encode LinkedIn in the QR only (no LinkedIn URL text in the header).
The ATS version keeps a plain LinkedIn URL for parsers.
