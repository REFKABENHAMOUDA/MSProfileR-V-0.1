# MSProfileR

<!-- badges: start -->
[![license](https://img.shields.io/badge/license-GPL%20%28%3E=%203%29-brightgreen.svg?style=flat)](https://www.gnu.org/licenses/gpl-3.0.html)
<!-- badges: end -->

Web application to analyse mass spectra profiles, to assess their quality, to detect their peaks and to classify spectra by clustering tools based on their profiles.

## Installation

Get the development version from GitHub:

```R
install.packages("devtools")
devtools::install_github("Almeras-Lionel/MSProfileR")
```

Vignette installation may not work, in this case, run the following:

```R
devtools::install_github("Almeras-Lionel/MSProfileR", upgrade = "never")
```

R may require a session restart in order to properly run the application.

## Usage

To run the application, use this:

```R
library(MSProfileR)
runMSProfileR()
```

A tutorial on how to use the application is available [here](https://github.com/Almeras-Lionel/MSProfileR/raw/main/vignettes/PDF/MS-profileR_tutorial_V1.0.pdf).
