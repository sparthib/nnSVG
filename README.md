# nnSVG

[![R build status](https://github.com/lmweber/nnSVG/workflows/R-CMD-check-bioc/badge.svg)](https://github.com/lmweber/nnSVG/actions)

R/Bioconductor package implementing our method `nnSVG` for scalable identification of spatially variable genes (SVGs) using nearest-neighbor Gaussian processes in spatially resolved transcriptomics (ST) data.


## Installation

The package can be installed from GitHub as follows.

```
remotes::install_github("lmweber/nnSVG")
```

The current development version depends on the development version of the [BRISC](https://cran.r-project.org/package=BRISC) R package from GitHub, which can be installed as follows.

```
remotes::install_github("ArkajyotiSaha/BRISC-extensions")
```


## Tutorial

An extended example and tutorial is available in the package vignette.


## Citation

A preprint describing `nnSVG` will be submitted to bioRxiv soon.


## Additional references

- Nearest-neighbor Gaussian processes (NNGP): [Datta et al. (2016)](https://www.tandfonline.com/doi/full/10.1080/01621459.2015.1044091)
- BRISC: [Saha and Datta (2018)](https://onlinelibrary.wiley.com/doi/full/10.1002/sta4.184)

