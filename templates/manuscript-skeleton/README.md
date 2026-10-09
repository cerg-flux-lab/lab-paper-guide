# Manuscript skeleton

Starter layout for a new paper. Copy this folder into the paper's own repository or Overleaf project, then replace `article` in `main.tex` with the publisher class from `templates/README.md`.

```
.
├── main.tex         Manuscript; one \input per section keeps diffs readable
├── sections/        intro.tex, methods.tex, results.tex, conclusion.tex (discussion lives in results.tex, or add discussion.tex if the journal wants it separate)
├── figures/         Vector PDF or SVG; legible at single-column width
├── refs.bib         One BibTeX file; every entry verified against the source
├── Makefile         latexmk build
└── RESPONSE.md      Not included; copy templates/response-to-reviewers.md or .tex here once reviews arrive
```

Conventions: UK English unless the journal mandates US English; no em dashes; SI units; every symbol defined at first use; nomenclature in `sections/nomenclature.tex` if the journal wants one. Share the Overleaf project with Prof Bhamjee from the first draft.
