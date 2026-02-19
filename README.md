# 2026_umbrella_review


## Quick start
- Clone repo
- Run `make renv` to restore R environment
- Make changes
- Run `make .styler` to
    - Automatically ensure adherence to tidyverse style with styler::style_dir()
    - Lint R code with lintr::lint_dir()
- Fix lint warnings in R code

The 'cca_analysis.qmd' is the standalone code needed to replicate the CCA analyses. The markdown can be rendered or the resulting output viewed in the corresponding 'cca_analysis.html' file.

## Installation guide
The 'renv' package was used to capture the state of the computing environment and record all dependencies. The package can also be used for the relevant installations. To do so, follow the steps below:
- Install the 'renv' package: install.packages("renv")
- Open the R project using the .Rproj file and restore the environment using the provided .lock file: renv::restore()

