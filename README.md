# rmd-article-template
Work in progress to create an RMarkdown journal article template for the building science group at UC Berkeley

### How to use this repo
- This repository contains all the code and data for this template
- To re-run the code to reproduce all of the text and figures in this template paper:
    - Fork this repository (green button)
    - Create a new RStudio project using the url for your new copy of the repository, which will download all of the files locally to the computer you are working on
    - Knit the file `Manuscript.Rmd` (you can do this by navigating to it in the `Files` pane, under `/Paper/Manuscript/`, and clicking "knit")
    - You may need to install some additional error packages if prompted to do so by errors during the knit. The packages used in this template are `tidyverse`, `here`, `knitr`, `stargazer`, `ggpmisc`. 