<!-- README.md is generated from README.Rmd. Please edit that file -->

# disscompendium <img src="man/figures/compendium-sticker.png" align="right" style="float:right; height:120px;"/>

<!-- badges: start -->

[![License: GPL (&gt;=
2)](https://img.shields.io/badge/License-GPL%20%28%3E%3D%202%29-blue.svg)](https://choosealicense.com/licenses/gpl-2.0/)
<!-- badges: end -->

<p align="left">
• <a href="#overview">Overview</a><br> •
<a href="#features">Features</a><br> •
<a href="#content">Content</a><br> •
<a href="#installation">Installation</a><br> •
<a href="#usage">Usage</a><br> • <a href="#citation">Citation</a><br> •
<a href="#contributing">Contributing</a><br> •
<a href="#acknowledgments">Acknowledgments</a><br> •
<a href="#references">References</a>
</p>

## Overview

This research compendium is for my dissertation. It includes code, and whenever possible, data that is not of a proprietary nature, for research reproducibility purposes. This is a work in progress. 

## Features

The main purpose of this compendium is to:
1. make my dissertation code available for use, under a GPL-3 license (TLDR: if you use it, you need to provide attribution and make any code that you use it with publicly available).
2. provide a means of working between multiple machines
3. organize and document my process for my committee members to readily access.
4. to get in the habit of doing open science-oriented documentation for my projects moving forward and use this as an opportunity to develop a workflow habit.
5. as an additional backup in the event of catastrophic failure, because I've seen too many horror stories about people who lose their dissertation. 

## Content

This repository is structured as follow:

-   [`DESCRIPTION`](https://github.com/afbat/disscompendium/tree/main/DESCRIPTION):
    contains project metadata (authors, date, dependencies, etc.)

-   [`make.R`](https://github.com/afbat/disscompendium/tree/main/make.R):
    main R script to run the entire project

-   [`R/`](https://github.com/afbat/disscompendium/tree/main/R):
    contains R functions developed especially for this project

-   **{{ LIST ADDITIONAL FILES/FOLDER }}**

## Installation

To install this compendium:

-   [Fork](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)
    this repository using the GitHub interface.
-   [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
    your fork using `git clone fork-url` (replace `fork-url` by the URL
    of your fork). Alternatively, open [RStudio
    IDE](https://posit.co/products/open-source/rstudio/) and create a
    New Project from Version Control.

## Usage

Launch the
[`make.R`](https://github.com/afbat/disscompendium/tree/main/make.R)
file with:

    source("make.R")

**Notes**

-   All required packages listed in the `DESCRIPTION` file will be
    installed (if necessary)
-   All required packages and R functions will be loaded
-   Some analyses listed in the `make.R` might take time

## Citation

Please use the following citation:

> **{{ ADD A CITATION }}**

## Contributing

All types of contributions are encouraged and valued. For more
information, check out our [Contributor
Guidelines](https://github.com/afbat/disscompendium/blob/main/CONTRIBUTING.md).

Please note that this project is released with a [Contributor Code of
Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.

## Acknowledgments
[TODO: COMPLETE]
- skeleton structure/package setup: Rcompendium

## References

**{{ OPTIONAL SECTION }}**
