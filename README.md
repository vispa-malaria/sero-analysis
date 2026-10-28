<!-- badges: start -->
[![Preprint](https://img.shields.io/badge/preprint-VeriXiv%203%3A313-blue)](https://verixiv.org/articles/3-313/v2)
[![CRAN status](https://www.r-pkg.org/badges/version/SeroTrackR)](https://CRAN.R-project.org/package=SeroTrackR)
<!-- badges: end -->

# Serological Data Analysis Tutorial

This repository contains the source for the **Serological Data Analysis ebook**: <https://vispa-malaria.github.io/sero-analysis/>

It is a comprehensive, step-by-step guide to analysing serology data using the [`{SeroTrackR}`](https://github.com/dionnecargy/SeroTrackR) R package and the [`{tidyverse}`](https://tidyverse.org/). It covers end-to-end workflows for the *Plasmodium vivax* serology test and treat (PvSeroTAT) strategy described in [Argyropoulos et al. 2026, VeriXiv](https://verixiv.org/articles/3-313/v2), as well as pathogen-agnostic use cases.

## Getting started

Install `{SeroTrackR}` from CRAN:

```r
install.packages("SeroTrackR")
library(SeroTrackR)
```

Or the development version from GitHub:

```r
pak::pak("dionnecargy/SeroTrackR")
```

## Related resources

- [SeroTrackR pkgdown site](https://dionnecargy.github.io/SeroTrackR/): function reference documentation and vignettes.
- [PvSeroApp](https://github.com/dionnecargy/PvSeroApp): the companion Shiny app implementing the same pipeline.
- [VISPA (Vivax Serology Partnership)](https://vispa.online/).

## Citing this work

If you use this ebook or `{SeroTrackR}` in your work, please cite **both**:

- Argyropoulos D, Conway E, Bourke C, Li-Wai-Suen C, Ruybal-Pesántez S, Smith L, Mueller I, Longley R. *PvSeroApp and SeroTrackR: An automated pipeline for Plasmodium vivax malaria serological analyses and machine learning classification of recent exposure.* VeriXiv 2026; 3:313. <https://verixiv.org/articles/3-313/v2>
- `SeroTrackR` R package (CRAN): <https://doi.org/10.32614/CRAN.package.SeroTrackR>

## Rendering the book locally

```bash
quarto render
```

## License

See [LICENSE.md](LICENSE.md).
