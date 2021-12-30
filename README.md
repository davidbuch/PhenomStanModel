# PhenomStanModel
A minimal R package featuring the Stan-derived sampling functions for the Phenom model by Tonner et al.

This package is explicitly designed to provide pre-compiled sampling functions to be used on the back end by a user-friendly web app (built with R Shiny) which will fit the Phenom model to user-provided data. 

The Phenom model was originally described in:
Tonner, P. D., Darnell, C. L., Bushell, F., Lund, P. A., Schmid, A. K., & Schmidler, S. C. (2020). A Bayesian non-parametric mixed-effects model of microbial growth curves. PLoS computational biology, 16(10), e1008366. https://doi.org/10.1371/journal.pcbi.1008366

The Stan code used in this package was written by Peter Tonner (ptonner) and is available on his github page in the phenom repository (https://github.com/ptonner/phenom).

A skeleton for this package was created with the R package "rstantools".
Of course, this package also depends on the R package "rstan".
