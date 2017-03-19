#   R Packages

##  Obtaining R packages
*   The primary location is CRAN
    *   Can obtain additional information using available.packages() function
        *   available.packages()
        *   head(rownames(a), 3)  Show the names of the first few packages starting with a
*   If familiar, Task Views link groups packages by topic

##  Installing an R Package
*   install.packages("slidify")
*   install.packages(c("slidify", "ggplot2", "devtools"))

##  Installing an R Package from Bioconductor
*   source("http://bioconductor.org/biocLite.R")
    *   gets the basic installer and basic set of R packages
*   biocLite()
    *   biocLite(c("GenomicFeatures","AnnotationDbi"))

##  Loading R Packages
  ### After installing the packages are not immediately available for use
*   library() = function to load R packages
    * library(ggplot2)
        *   do not put package name in quotations!!!
*   after loading the package you can view all dependencies
    *   library(ggplot2)
        *   search()
            *   lists dependencies                                            