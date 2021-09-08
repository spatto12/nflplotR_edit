
<!-- README.md is generated from README.Rmd. Please edit that file -->

# nflplotR

<!-- badges: start -->

[![CRAN
status](https://img.shields.io/cran/v/nflplotR?style=flat-square&logo=R&label=CRAN)](https://CRAN.R-project.org/package=nflplotR)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg?style=flat-square)](https://lifecycle.r-lib.org/articles/stages.html)
[![R build
status](https://img.shields.io/github/workflow/status/nflverse/nflplotR/R-CMD-check?label=R%20check&style=flat-square&logo=github)](https://github.com/nflverse/nflplotR/actions)
[![nflverse
discord](https://img.shields.io/discord/591914197219016707.svg?color=5865F2&label=nflverse%20discord&logo=discord&logoColor=5865F2&style=flat-square)](https://discord.com/invite/5Er2FBnnQa)
<!-- badges: end -->

The goal of nflplotR is to provide functions and geoms that help
visualization of NFL related analysis. It provides a ggplot2 geom that
does the heavy lifting of plotting NFL logos in high quality, with
correct aspect ratio and possible transparency.

## Installation

<!-- You can install the released version of nflplotR from [CRAN](https://CRAN.R-project.org) with: -->
<!-- ``` r -->
<!-- install.packages("nflplotR") -->
<!-- ``` -->
<!-- And the development version from [GitHub](https://github.com/) with: -->
<!-- ``` r -->
<!-- # install.packages("devtools") -->
<!-- devtools::install_github("nflverse/nflplotR") -->
<!-- ``` -->

You can install `nflplotR` with

``` r
if (!require("remotes")) install.packages("remotes")
remotes::install_github("nflverse/nflplotR")
```

## Getting help

The best places to get help on this package are:

-   the [nflverse discord](https://discord.com/invite/5Er2FBnnQa) (for
    both this package as well as anything R/NFL related)
-   opening [an
    issue](https://github.com/nflverse/nflplotR/issues/new/choose)

## Contributing

Many hands make light work! Here are some ways you can contribute to
this project:

-   You can [open an
    issue](https://github.com/nflverse/nflplotR/issues/new/choose) if
    you’d like to request specific data or report a bug/error.

-   If you’d like to contribute code, please check out [the contribution
    guidelines](https://nflplotr.nflverse.com/CONTRIBUTING.html).

## Terms of Use

The R code for this package is released as open source under the [MIT
License](https://nflplotr.nflverse.com/LICENSE.html). NFL data accessed
by this package belong to their respective owners, and are governed by
their terms of use.
