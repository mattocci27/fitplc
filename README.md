# Fit Hydraulic Vulnerability Curves in R

A fork from [fitplc](https://github.com/RemkoDuursma/fitplc)

- [Installation](#installation)

- [New feature](#new-feature)

To install the development version, use this command:

# Installation

```
# install.packages("devtools")
devtools::install_github("mattocci27/fitplc")

library(fitplc2)
 
```

# New feature

- Bootstrap is implemented for mixed models of `method = "Weibull"` and `method = "sigmoidal"` in `fitplc`

- `fitplc` has options for `method = "Inv_Weibull"` and `method =
"Inv_nls_sigmoidal"`, which estimates Px values using inverse functions of Weibull
and sigmoidal function, respectively.

