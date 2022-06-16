
<!-- README.md is generated from README.Rmd. Please edit that file -->

# `scicomptools`

<!-- badges: start -->
<!-- badges: end -->

The goal of scicomptools is to house all of the standalone functions
written by NCEAS Scientific Computing Team that lack a specific project.
Currently contains various tools to import, summarize and analyze data

## Installation

You can install the development version of scicomptools from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("NCEAS/scicomptools")
```

## Current Functions

-   **`zoom_webinar_fix()`**: Processes the raw CSVs output by Zoom
    after a webinar (handles both the attendance and post-webinar survey
    dataframes)

-   **`word_cloud_prep()`**: Performs text mining on a given text column
    of a dataframe to create a dataframe that is ready for word cloud
    creation.

    -   Note that there is also the companion function
        `word_cloud_plot()` that performs the mining *and* creates a
        simple `ggplot2` word cloud (for those who don’t want to handle
        their own plotting aesthetics)

-   **`()`**:
