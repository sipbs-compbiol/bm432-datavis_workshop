# `bm432-datavis_workshop` - `README.md`

To show the slides for this workshop, follow the URL below

- [Workshop slides](https://sipbs-compbiol.github.io/bm432-datavis_workshop/bm432-datavis.html)

## BM432 Data Visualisation Flipped Workshop

This repository contains an RStudio project that builds slides for the BM432 flipped data visualisation workshop, by Morgan Feeney and Leighton Pritchard.

Students review real journal figures using a Google Form. The `bm432-datavis.Rmd` RMarkdown notebook pulls their entries from the corresponding Google Sheet and builds a series of slides showing:

- overall responses
- overall student ratings for all figures
- a breakdown of individual category scores across all figures
- scores and comments from students, for each of the figure
- wordclouds of student comments

### Building the slides

1. Make changes to `bm432-datavis.Rmd` as needed
2. Build slides locally in RStudio by knitting the `bm432-datavis.Rmd` file to build `bm432-datavis.html`
3. Commit your changes to the `bm432-datavis.Rmd` and `bm432-datavis.html` files
4. Push your changes to the repository

Building of the GitHub Pages deployment is automatic, and managed by a GitHub Action (`.github/workflows/static.yml`) that builds on any push to the `main` branch.