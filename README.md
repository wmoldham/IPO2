
<!-- README.md is generated from README.Rmd. Please edit that file -->

# IPO2

<!-- badges: start -->
<!-- badges: end -->

Isotopologue Parameter Optimization (IPO) is a commonly used tool to
optimize parameters for XCMS analysis of metabolomics data. The progress
in XCMS development has made it more difficult to utilize IPO, and so
IPO2 is an effort to more seamlessly integrate this method of parameter
optimization with the latest version of XCMS. While this package adopts
a similar approach of using isotope identification, scoring, and
design-of-experiments, the underlying code to accomplish these tasks is
different and the results are likely not exactly the same.

Please find a copy of the original IPO manuscript in the source of this
package.

``` r
citation("IPO")
#> 
#> To cite the IPO package in publications use:
#> 
#>   Libiseller, Dvorzak, Kleb, Gander, Eisenberg, Madeo, Neumann,
#>   Trausinger, Sinner, Pieber, Magnes IPO: A Tool for automated
#>   Optimization of XCMS Parameters BMC Bioinformatics (accepted)
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Article{,
#>     author = {Gunnar Libiseller and Michaela Dvorzak and Ulrike Kleb and Edgar Gander and Tobias Eisenberg and Frank Madeo and Steffen Neumann and Gert Trausinger and Frank Sinner and Thomas Pieber and Christoph Magnes},
#>     title = {IPO: a tool for automated optimization of XCMS parameters},
#>     journal = {BMC Bioinformatics},
#>     year = {(2015)},
#>     volume = {16},
#>     pages = {118},
#>   }
```

## Installation

You can install the original release version of IPO from
[Bioconductor](https://www.bioconductor.org/packages/release/bioc/html/IPO.html).

``` r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("IPO")
```

And the development version is available from
[GitHub](https://github.com/rietho/IPO).

``` r
if (!requireNamespace("devtools", quietly = TRUE))
    install.packages("devtools")
    
devtools::install_github("rietho/IPO")
```

You can install the development version of IPO2 from
[GitHub](https://github.com/rietho/IPO2) with:

``` r
if (!requireNamespace("devtools", quietly = TRUE))
    install.packages("devtools")
    
devtools::install_github("wmoldham/IPO2")
```

## Usage
