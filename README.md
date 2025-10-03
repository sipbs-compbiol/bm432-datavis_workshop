# `bm432-datavis_workshop` - `README.md`

This repository contains files to support the one-hour BM432 data visualisation workshop.

## Workshop plan

### 1. Flipped classroom/pre-preparation

Students are assigned four real journal figures, and are asked to assess these using a modified Strathclyde Marking Guide B scheme, entering their score and a free text account of what they think works about the figure, and what needs improvement.

### 2. Workshop

The main workshop slides are written in RMarkdown/Quarto and gather the data from completed Google Forms on the morning of the workshop. This data will be used in the workshop proper.

The first section of the workshop presents fictional data from an experimental study of gene function, presented in four figures. For each of these figures the data is presented in a manner that needs improvement, the data visualisation principles guiding that improvement are discussed, and an improved figure is presented.

1. The results of successful gene deletion: PCRs, gel results, and a pictogram showing gene context/primer location
2. Micrographs of cells: wild-type and deletion mutant
3. Presentation of quantitative measurements (e.g. cell size or expression level): bar charts and more informative representations of data distributions
4. Presentation of correlation/relationship data (e.g. expression under tunable promoter): scatterplot data, small multiples plots

The second section of the workshop returns to the figures from the pre-workshop preparation, presenting the figures and the free-text critiques from students, alongside the distribution of scores for each figure.

If there is time, a PowerPoint presentation with a Slido poll is shown, asking students to grade the same journal figures again. The score distributions before and after the workshop are compared.

### 3. Supporting website

This repository holds a Quarto website, presented via GitHub Pages, with the slide presentations and some supporting material around data visualisation for the students.

To show the slides for this workshop, follow the URL below

- [Workshop slides](https://sipbs-compbiol.github.io/bm432-datavis_workshop/bm432-datavis.html)

## Quick Start for Editors

- The project page for AY 2025-26 is at [this link](https://github.com/orgs/sipbs-compbiol/projects/4)

1. Clone this repository to your local machine (if needed)
2. Create a new branch for your changes. **NOTE:** large-scale changes for each academic year are handled under an umbrella branch, e.g. `2025-26` - please create new branches from this branch, where appropriate.
3. Edit the repository/make changes and check the rendering on your local machine. **NOTE:** `RStudio` is strongly recommended for this.
4. Push the changes to your branch.
5. When ready, make a pull request to the parent branch. **NOTE:** this might be the umbrella branch, e.g. `2025-26`.
6. If review is not required, and there are no conflict, merge the pull request. Otherwise, a review/discussion should follow on GitHub.

**Building of the GitHub Pages deployment from `main` is automatic, and managed by a GitHub Action (`.github/workflows/static.yml`) that builds on any push to the `main` branch.**

## Licence

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/sipbs-compbiol/bm432-datavis_workshop">BM432 Data Visualisation Workshop material</a> by <span property="cc:attributionName">Dr Morgan Feeney and Dr Leighton Pritchard</span> is licensed under <a href="http://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution-ShareAlike 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p> 