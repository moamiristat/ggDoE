# ggDoE


[![R-CMD-check](https://github.com/toledo60/ggDoE/workflows/R-CMD-check/badge.svg)](https://github.com/toledo60/ggDoE/actions)


## Installation

You can get the development version from GitHub:

```{r}
install.packages("remotes") # if not installed yet
remotes::install_github("toledo60/ggDoE")
```

## Contributing to the package
I welcome feedback, suggestions, issues, and contributions!

### Bug reports

When reporting an [Issue](https://github.com/toledo60/ggDoE/issues), please spend some time making it easy to follow and reproduce your issue. For this, I highly recommend using [reprex package](https://reprex.tidyverse.org/)

### Package development

A good way to start is by contributing additional examples or improving the documentation.
Additionally, you can submit a [Pull Request](https://github.com/toledo60/ggDoE/pulls) to integrate your own function(s) in a new branch.

If you want to submit a new function please provide: the new function(s) with code and roxygen tags (with examples) as shown below

```{r}
#' Add together two numbers
#' 
#' @param x A number.
#' @param y A number.
#' @return The sum of \code{x} and \code{y}.
#' @examples
#' add(1, 1)
#' add(10, 1)
add <- function(x, y) {
  x + y
}
```
