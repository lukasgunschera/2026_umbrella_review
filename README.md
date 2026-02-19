# 2026_umbrella_review


## Quick start
- Clone repo
- Run `make renv` to restore R environment
- Make changes
- Run `make .styler` to
    - Automatically ensure adherence to tidyverse style with styler::style_dir()
    - Lint R code with lintr::lint_dir()
- Fix lint warnings in R code

## System requirements
We provide the renv.lock file which captures the state of the computing environment at the time of writing.

## Installation guide
The 'renv' package was used to capture the state of the computing environment and record all dependencies. The package can also be used for the relevant installations. To do so, follow the steps below:
- Install the 'renv' package: install.packages("renv")
- Open the R project using the .Rproj file and restore the environment using the provided .lock file: renv::restore()

## Demo
The code 

## Instructions for use
