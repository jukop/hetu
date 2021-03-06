[![Build Status](https://travis-ci.org/rOpenGov/hetu.svg?branch=master)](https://travis-ci.org/rOpenGov/hetu)

<!--[![Coverage Status](https://coveralls.io/repos/github/rOpenGov/hetu/badge.svg?branch=master)](https://coveralls.io/github/rOpenGov/hetu?branch=master)-->

<!--[![rstudio mirror downloads](http://cranlogs.r-pkg.org/badges/grand-total/hetu)](https://github.com/metacran/cranlogs.app)-->

<!--[![cran version](http://www.r-pkg.org/badges/version/hetu)](http://cran.rstudio.com/web/packages/hetu)-->

hetu
==========

## Introduction

`hetu` is an R package for structural handling of identity numbers used in the Finnish administration, in particular the personal identity numbers (henkilötunnus). 

The syntax in this package is unified with the similar package for Swedish ID numbers, the [sweidnumbr](https://github.com/rOpenGov/sweidnumbr).


## Installation

To install from CRAN just write:

```r
install.packages(hetu)
```

Use the `devtools` package to install the latest version from GitHub:
```r
devtools::install_github("rOpenGov/hetu")
library(hetu)
```

A tutorial is included with the package and can be viewed with:
```r
vignette("hetu")
```

## Reporting bugs

Please use the GitHub issue tracker [here](https://github.com/rOpenGov/hetu/issues) for reporting bugs and making further feature requests.

IMPORTANT: When submitting a bug, you can make the lives of the developers easier by submitting the following information along with your bug report:
- The output of `sessionInfo()`
- The output of `packageVersion("hetu")`

