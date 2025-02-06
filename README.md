
<!-- README.md is generated from README.Rmd. Please edit that file -->

# datamanager

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.xxxxxxx.svg)](https://doi.org/10.5281/zenodo.xxxxxxx)
[![codecov](https://codecov.io/gh/annyg/datamanager/branch/main/graph/badge.svg)](https://codecov.io/gh/annyg/datamanager)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

`datamanager` is an R package designed for the efficient management and
scoring of research data, particularly focusing on questionnaire and
survey data. It provides a suite of functions to handle common tasks in
data preparation and scoring, including support for instruments such as
RAND-12 and EMQ.

## Features

- **Data Management**: Effortlessly clean and organize questionnaire
  data.
- **Scoring Functions**: Compute scores for recognized instruments
  including RAND-12 and EMQ.
- **Efficient Workflow**: Streamline your data processing tasks in
  research settings.

## Installation

You can install the latest version of `datamanager` directly from GitHub
using the `devtools` package:

``` r
# Install devtools if you haven't already
install.packages("devtools")

# Install datamanager from GitHub
devtools::install_github("annyg/datamanager")
```

## Usage

Below are some examples demonstrating how to use the main functions in
`datamanager`.

### Data Management

``` r
library(datamanager)

# Example function call for cleaning data
cleaned_data <- clean_survey_data(raw_data)
```

### Scoring Instruments

#### RAND-12 Scoring

``` r
# Example for scoring RAND-12
rand12_scores <- score_rand12(cleaned_data)
```

#### EMQ Scoring

``` r
# Example for scoring EMQ
emq_scores <- score_emq(cleaned_data)
```

For detailed documentation on these functions and more, please refer to
the package help files or vignette.

## Citation

If you use `datamanager` in your research, please cite it as follows:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.xxxxxxx.svg)](https://doi.org/10.5281/zenodo.xxxxxxx)

Example BibTeX entry:

``` bibtex
@software{Anders B. Nygaard_2023_XXXXXXX,
  author       = {Anders B. Nygaard},
  title        = {datamanager: Tools for Questionnaire and Survey Data Management},
  month        = month,
  year         = 2023,
  publisher    = {GitHub},
  journal      = {GitHub repository},
  version      = {v1.0.0},
  doi          = {10.5281/zenodo.xxxxxxx},
  url          = {https://github.com/annyg/datamanager}
}
```

## Contributing

We welcome contributions! If you’d like to contribute to `datamanager`,
please fork the repository, create a branch, and submit a pull request.

## License

`datamanager` is licensed under the MIT License. See the `LICENSE` file
for more information. \#FIXME

------------------------------------------------------------------------

We hope you find `datamanager` useful in your research projects. For any
questions, issues, or suggestions, please open an issue on GitHub or
contact us.
