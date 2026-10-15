# SO14 — Economy, livelihoods and wellbeing indicators

Static working site for the Tambopata landscape indicators.

**Published page:** https://rmcondor.github.io/so14-indicators/

**Repository:** https://github.com/rmcondor/so14-indicators

The site has three tabs: **Codebook**, **Indicators** and **Analysis**. The interface, variable documentation and indicator definitions are in English. Analysis uses simulated data only; pending definitions are identified throughout the site.

## Spanish questions and source traceability

Open a variable to see its English documentation. When Spanish wording is available, a **Question in Spanish** box appears at the end of the detail panel. It retains the Spanish question and response options, distinguishes source-based wording, adaptations, proposed translations and project drafts, and links the documented source and original item identifier.

For income stability, the box also retains the ENAHO P38A source question alongside the project version that adds a 12-month reference period. ENA is currently a reference for future shock-list adaptation; no question is attributed to ENA or ENDES without a documented source. Original English OECD and pro-WEAI wording remains available.

Codebook search supports English, retained Spanish wording and source identifiers. The CSV exports English metadata, Spanish questions and options, provenance, and source links. Preserve these fields when updating a variable; do not replace original wording with its translation. Response codes and dataset identifiers are independent of display language.

## Publication and updates

GitHub Pages serves branch `main`, folder `/(root)`. Edit `index.html` directly, check all three tabs and the codebook CSV, then push the reviewed change to `main` when publication is intended. `.nojekyll` serves the HTML without Jekyll. No dependencies or build step are required.

The repository contains only the public site and configuration. Q&A, trackers, original documents and data files remain outside it. The Spanish baseline HTML is archived in the parent workspace at `outputs/_archive/SO14_indicator_review.html`; it is a backup, not the source for future site updates. Public references use external links rather than local files.
