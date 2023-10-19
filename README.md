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

**Building of the GitHub Pages deployment is automatic, and managed by a GitHub Action (`.github/workflows/static.yml`) that builds on any push to the `main` branch.**

## Licence

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/sipbs-compbiol/bm432-datavis_workshop">BM432 Data Visualisation Workshop Slide material</a> by <span property="cc:attributionName">Dr Morgan Feeney and Dr Leighton Pritchard</span> is licensed under <a href="http://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution-ShareAlike 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p> 