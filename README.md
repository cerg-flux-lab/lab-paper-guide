# CERG-FLUX Lab: Writing and Publishing Papers

Guide, templates and checklists for publishing from the CERG-FLUX Lab (Fluids, Learning and Uncertainty in compleX systems), Department of Mechanical and Aeronautical Engineering, University of Pretoria.

**Two rules apply to every paper from the Lab.** All publication decisions require Prof Muaaz Bhamjee's (and co-supervisors') input and final approval, and every author must be able to defend every word (the viva test under the Lab's Intellectual Ownership Framework). The guide explains both.

## Start here

| If you want to | Open |
| --- | --- |
| Understand the whole process, from idea to published paper | [docs/how-to-write-a-paper.md](docs/how-to-write-a-paper.md) |
| Find the LaTeX template for a target journal or conference | [templates/README.md](templates/README.md) |
| Write the cover letter for a submission | [templates/cover-letter.md](templates/cover-letter.md) or the LaTeX version [templates/cover-letter.tex](templates/cover-letter.tex) |
| Respond to reviewers | [templates/response-to-reviewers.md](templates/response-to-reviewers.md) or the LaTeX version [templates/response-to-reviewers.tex](templates/response-to-reviewers.tex) |
| Propose a paper to Prof Bhamjee (and co-supervisors) (approval gate 1) | [templates/paper-proposal.md](templates/paper-proposal.md) or the LaTeX version [templates/paper-proposal.tex](templates/paper-proposal.tex) |
| Check the manuscript before internal review (gate 3) | [docs/pre-submission-checklist.md](docs/pre-submission-checklist.md) |
| Set up the Overleaf or Git project for a new manuscript | [templates/manuscript-skeleton/](templates/manuscript-skeleton/) and its [README](templates/manuscript-skeleton/README.md) |

## Repository layout

```
.
├── README.md
├── CONTRIBUTING.md
├── LICENSE
├── .gitignore                      LaTeX build artefacts
├── docs/
│   ├── how-to-write-a-paper.md     The guide
│   └── pre-submission-checklist.md Gate 3 checklist as a standalone file
└── templates/
    ├── README.md                   Index of publisher and conference templates
    ├── paper-proposal.md           One-page proposal for approval gate 1
    ├── paper-proposal.tex          Same proposal as a compilable LaTeX file
    ├── cover-letter.md             Submission cover letter
    ├── cover-letter.tex            Same letter as a compilable LaTeX file
    ├── response-to-reviewers.md    Point-by-point response document
    ├── response-to-reviewers.tex   Same response as a compilable LaTeX file
    └── manuscript-skeleton/        Starter LaTeX project; copy into each paper's own repository
        ├── README.md               How to use the skeleton and the Lab's manuscript conventions
        ├── main.tex                Manuscript; one \input per section
        ├── sections/               intro.tex, methods.tex, results.tex, conclusion.tex
        ├── figures/                Vector figures (empty; .gitkeep only)
        ├── refs.bib                One BibTeX file for the paper
        └── Makefile                latexmk build (make, make clean)
```

## Approval workflow in one line

Gate 1 proposal, Gate 2 venue, Gate 3 manuscript, Gate 4 submission, Gate 5 every response or resubmission. Nothing leaves the Lab between gates without Prof Bhamjee's (and co-supervisors') written sign-off. Details in section 12 of the guide.

## Maintainer

Prof Muaaz Bhamjee, Principal Investigator: CERG-FLUX Lab (Fluids, Learning and Uncertainty in compleX systems) | https://cerg-flux-lab.github.io/
