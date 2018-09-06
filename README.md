# RTCGA.RPPA

A part of [RTCGA](https://github.com/RTCGA) family.

To install development version from GitHub use

````{R}
library(RTCGA)
installTCGA("RTCGA.RPPA")
````

Make sure you have [Rtools](https://cran.r-project.org/bin/windows/Rtools/) installed on your computer, if you are trying `devtools` on Windows.

To install Bioconductor development version use (the same as GitHub development version) - `still in the review`

````{R}
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("RTCGA.RPPA")
````

