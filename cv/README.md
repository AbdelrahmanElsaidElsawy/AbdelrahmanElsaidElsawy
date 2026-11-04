# CV (source of truth)

Edit the `.tex` files here. Pushing to `main` runs `.github/workflows/build-cv.yml`,
which rebuilds the PDFs in this folder.

The portfolio site
([AbdelrahmanElsaidElsawy.github.io](https://github.com/AbdelrahmanElsaidElsawy/AbdelrahmanElsaidElsawy.github.io))
syncs only the PDFs — do not keep a second copy of the LaTeX there.

| Source | Variant | PDF |
| --- | --- | --- |
| `cv.tex` | English designed | `Abdelrahman_Elsaid_Elsawy_CV.pdf` |
| `cv_ats.tex` | English ATS | `Abdelrahman_Elsaid_Elsawy_CV_ATS.pdf` |
| `cv_de.tex` | German designed | `Abdelrahman_Elsaid_Elsawy_CV_DE.pdf` |
| `cv_ats_de.tex` | German ATS | `Abdelrahman_Elsaid_Elsawy_CV_DE_ATS.pdf` |
| `cv_tr.tex` | Turkish designed | `Abdelrahman_Elsaid_Elsawy_CV_TR.pdf` |
| `cv_ats_tr.tex` | Turkish ATS | `Abdelrahman_Elsaid_Elsawy_CV_TR_ATS.pdf` |
| `cv_fr.tex` | French designed | `Abdelrahman_Elsaid_Elsawy_CV_FR.pdf` |
| `cv_ats_fr.tex` | French ATS | `Abdelrahman_Elsaid_Elsawy_CV_FR_ATS.pdf` |
| `cv_ar.tex` | Arabic designed (XeLaTeX) | `Abdelrahman_Elsaid_Elsawy_CV_AR.pdf` |
| `cv_ats_ar.tex` | Arabic ATS (XeLaTeX) | `Abdelrahman_Elsaid_Elsawy_CV_AR_ATS.pdf` |

Designed versions: LinkedIn is the QR only (clickable, no URL text in the header).
ATS versions keep a plain LinkedIn URL for parsers.
Arabic CVs compile with XeLaTeX + Amiri.
