# Publisher and conference templates

Always download the template from the publisher's own page or Overleaf's official gallery, never from a third-party mirror, and always check the journal's guide for authors for the current version. Links checked 9 October 2026; report broken ones by pull request.

## Journals

Every journal below was on the DHET accredited list on the date checked. The Lab does not publish in a journal that is not on the current list, so confirm the entry on the [CREST list](https://db.crest.sun.ac.za/zapublications/) before each submission; the list changes every year and titles are delisted.

| Publisher | Journals the Lab targets | Template | Notes |
| --- | --- | --- | --- |
| Elsevier | Computers and Fluids; Int. J. Multiphase Flow; J. Computational Physics; Int. J. Heat and Mass Transfer; CMAME; Minerals Engineering; Applied Thermal Engineering; Engineering Applications of AI; Neural Networks; NIM A; Computers and Mathematics with Applications; J. Computational Science | `elsarticle` class: [Elsevier LaTeX instructions](https://www.elsevier.com/researcher/author/policies-and-guidelines/latex-instructions) and the [Overleaf elsarticle template](https://www.overleaf.com/latex/templates/elsevier-article-elsarticle-template/vwckvfrzvcht) | Use `preprint` option for submission, `review` for line numbers. Most Elsevier titles accept Your Paper Your Way (free format) at first submission. UP Read and Publish covers Elsevier hybrid titles. |
| Springer Nature | Scientific Reports; npj Quantum Information; Nature Portfolio; Springer engineering journals | `sn-jnl` class: [Springer Nature LaTeX support](https://www.springernature.com/gp/authors/campaigns/latex-author-support) and the [official Overleaf template](https://www.overleaf.com/latex/templates/springer-nature-latex-template/myxmhdsbzkyd) | Pick the reference style option (`sn-mathphys-num` for engineering and physics, `sn-nature` for Nature Portfolio). UP Read and Publish covers Springer Nature hybrid titles. |
| Cambridge University Press | Journal of Fluid Mechanics | [JFM author instructions](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/information/author-instructions) with the `jfm` class linked there | Strict style; read three recent JFM papers before drafting. |
| AIP Publishing | Physics of Fluids | [AIP author resources](https://publishing.aip.org/resources/researchers/authors/) and the [Overleaf AIP template](https://www.overleaf.com/latex/templates/template-for-submission-to-aip-publishing-journals/hbgstfxtkyvz) | Built on REVTeX 4.2 with the `aip` option. |
| American Physical Society | Physical Review E; Physical Review A; Physical Review Research | [REVTeX 4.2](https://journals.aps.org/revtex) | `\documentclass[aps,pre,reprint]{revtex4-2}` for PRE. |
| IOP Publishing / SISSA | Journal of Instrumentation (JINST); Machine Learning: Science and Technology; Quantum Science and Technology | JINST: [jinst class](https://jinst.sissa.it/jinst/help/JINST_TeXclass.jsp). IOP journals: [IOP LaTeX guidelines](https://publishingsupport.iopscience.iop.org/journals/how-to-prepare-your-article/) | JINST is the default for ATLAS ITk engineering and detector papers. |
| IEEE | IEEE Transactions on Nuclear Science; IEEE Transactions on Quantum Engineering; other Transactions | `IEEEtran` class via the [IEEE Template Selector](https://template-selector.ieee.org/) or the [official Overleaf IEEE templates](https://www.overleaf.com/gallery/tagged/ieee-official) | `\documentclass[journal]{IEEEtran}`. Always confirm the exact template through the Template Selector; some Transactions differ. |
| Quantum (Verein) | Quantum | [quantumarticle class](https://quantum-journal.org/papers/instructions/) | Overlay journal: paper is posted on arXiv first; Prof Bhamjee's (and co-supervisors') approval needed for the arXiv posting. |
| JMLR | Journal of Machine Learning Research | [JMLR format and style](https://jmlr.org/format/format.html) | Free, no APC. |
| ACM | ACM journals and proceedings | [ACM primary article template](https://www.acm.org/publications/proceedings-template) | UP Read and Publish covers ACM. |

## Conferences

| Conference family | Template | Notes |
| --- | --- | --- |
| IEEE conferences (IEEE Quantum Week QCE, NSS/MIC, and most IEEE-sponsored events) | `\documentclass[conference]{IEEEtran}` from the [IEEE Template Selector](https://template-selector.ieee.org/) or the [Overleaf IEEE conference template](https://www.overleaf.com/latex/templates/ieee-conference-template/grfzhhncsfqn) | Check the specific conference page: some use a modified template and strict page limits. Proceedings in IEEE Xplore are DHET-subsidised at 0.5 unit. |
| Springer LNCS (many computing and SciML venues) | [LNCS author instructions and template](https://www.springer.com/gp/computer-science/lncs/conference-proceedings-guidelines) | `llncs` class. Indexed in Scopus. |
| AIP Conference Proceedings | [AIP Conference Proceedings author guide](https://publishing.aip.org/resources/researchers/authors/aip-conference-proceedings/) | Common for physics-leaning conferences. |
| NeurIPS, ICML, ICLR workshops | Each year's style file is published on the conference site (for example [NeurIPS style files](https://neurips.cc/Conferences/2026/PaperInformation/StyleFiles)); check the current year | Double-anonymised: remove all identifying details. Workshop papers are usually not indexed. |
| SIAM conferences (CSE) | [SIAM author guidance](https://www.siam.org/publications/journals/about-siam-journals/information-for-authors) | Abstracts only for most SIAM conferences; no proceedings. |
| ECCOMAS, WCCM, ICMF, SACAM, SAIP | Template issued with each year's call for papers on the conference site | Check whether the proceedings are indexed before counting the paper as a DHET output. |
| TWEPP (CERN electronics) | Proceedings published in JINST; use the [jinst class](https://jinst.sissa.it/jinst/help/JINST_TeXclass.jsp) | ATLAS internal approval first. |

## Before you use any template

1. Confirm the venue is approved at gate 2 (see the guide, section 13).
2. Download the current template and read the guide for authors on the same day; templates change.
3. Start from `templates/manuscript-skeleton/` for the project layout, then swap in the publisher class.
