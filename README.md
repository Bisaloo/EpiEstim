# EpiEstim

<!-- badges: start -->
[![R build status](https://github.com/mrc-ide/EpiEstim/workflows/R-CMD-check/badge.svg)](https://github.com/mrc-ide/EpiEstim/actions)
[![Codecov test coverage](https://codecov.io/gh/annecori/EpiEstim/branch/master/graph/badge.svg)](https://codecov.io/gh/annecori/EpiEstim?branch=master)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3871387.svg)](https://doi.org/10.5281/zenodo.3871387)
<!-- badges: end -->

EpiEstim is a tool to estimate the time-varying instantaneous reproduction number during epidemics.
To install the latest version, use:
```r
devtools::install_github("mrc-ide/EpiEstim", build_vignettes = TRUE)
```

## Vignettes
The following vignettes provide worked examples, FAQs and details about how EpiEstim can be used alongside some other R packages in an outbreak analysis workflow.

```r
vignette("short_demo", package = "EpiEstim")
vignette("full_EpiEstim_vignette", package = "EpiEstim")
```

To apply EpiEstim to temporally aggregated incidence data (e.g. weekly), please see:

```r
vignette("EpiEstim_aggregated_data", package = "EpiEstim")
```

To estimate the transmission advantage of pathogen variants or strains in real-time, please see the pre-print by Bhatia et al (https://www.medrxiv.org/content/10.1101/2021.11.26.21266899v1) and the vignette below:

```r
vignette("MV_EpiEstim_vignette", package="EpiEstim")   
```

To find out more about alternative software that may be more suitable for your specific data or analysis, please see below:

```r
vignette("alternative_software", package = "EpiEstim")
```

## Citing our paper
Anne Cori, Neil M. Ferguson, Christophe Fraser, Simon Cauchemez, [A New Framework and Software to Estimate Time-Varying Reproduction Numbers During Epidemics](https://doi.org/10.1093/aje/kwt133), American Journal of Epidemiology, Volume 178, Issue 9, 1 November 2013, Pages 1505–1512. 

> @article{Cori2013,
 author={Cori, A and Ferguson, NM and Fraser, C and Cauchemez, S},  
 year={2013},  
 title={{A New Framework and Software to Estimate Time-Varying Reproduction Numbers During Epidemics}},  
 journal={Am. J. Epidemiol.},  
 doi={10.1093/aje/kwt133},  
}


## Citing this code resource
We kindly request that you cite this codebase as follows (BibTeX format):

> @misc{Cori2021,
 author={Cori, A and Kamvar, ZN and Stockwin, J and Jombart, T and Dahlqwist, E and FitzJohn, R and Thompson, R},  
 year={2021},  
 title={{EpiEstim v2.2-3: A tool to estimate time varying instantaneous reproduction number during epidemics}},  
 publisher={GitHub},
 journal={GitHub repository},  
 howpublished = {\url{https://github.com/mrc-ide/EpiEstim}},
 commit={c18949d93fe4dcc384cbcae7567a788622efc781},  
}
