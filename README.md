
<!-- README.md is generated from README.Rmd. Please edit that file -->

# metamedian: Meta-Analysis of Medians

[![Build_Status](https://travis-ci.org/stmcg/metamedian.svg?branch=master)](https://travis-ci.org/stmcg/metamedian)
[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/metamedian)](https://cran.r-project.org/package=metamedian)
[![CRAN_Download_Badge](https://cranlogs.r-pkg.org/badges/metamedian)](https://www.r-pkg.org/pkg/metamedian)
[![CRAN_Download_Badge_All](https://cranlogs.r-pkg.org/badges/grand-total/metamedian)](https://www.r-pkg.org/pkg/metamedian)

The `metamedian` package implements several methods to meta-analyze
studies that report the sample median of the outcome. When the primary
studies are one-group studies, the methods of [McGrath et
al. (2019)](https://onlinelibrary.wiley.com/doi/abs/10.1002/sim.8013?af=R)
can be applied to estimate the pooled median. In the two-group context,
the methods of [McGrath et
al. (2020a)](https://onlinelibrary.wiley.com/doi/abs/10.1002/bimj.201900036)
can be applied to estimate the pooled difference of medians across
groups.

Additionally, this package implements methods to estimate the
study-specific means and their standard errors from studies reporting
sample medians in order to estimate the pooled (difference of) means.
Specifically, one can apply the methods of [McGrath et
al. (2020b)](https://journals.sagepub.com/doi/full/10.1177/0962280219889080)
and [Cai et
al. (2021)](https://journals.sagepub.com/doi/full/10.1177/09622802211047348)
to estimate study-specific means and standard deviations, and one can
apply the parametric bootstrap approach of [McGrath et
al. (2022)](https://arxiv.org/abs/2206.14386) to estimate their
corresponding standard errors.

## Installation

You can install the released version of `metamedian` from CRAN with:

``` r
install.packages("metamedian")
```

After installing the `devtools` package (i.e., calling
`install.packages(devtools)`), the development version of `metamedian`
can be installed from GitHub with:

``` r
devtools::install_github("stmcg/metamedian")
```
