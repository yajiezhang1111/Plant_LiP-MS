# Plant_LiP-MS_PeptideTypeAnnotation
R scripts adapted for peptide type annotation using the R Protti package (Quast, et al. 2022). The scripts are part of a LiP-MS protocol version adapted for plants.

## Installation
```r
#Install from CRAN using the install.packages() function.
install.packages("protti", dependencies = TRUE)

#Install the development version from GitHub using the devtools package
install.packages("devtools")
devtools::install_github("jpquast/protti", dependencies = TRUE)
```

## Reference
Quast, J.P., Schuster, D., Picotti, P. (2022). protti: an R package for comprehensive data analysis of peptide- and protein-centric bottom-up proteomics data. Bioinformatics Advances, 2(1).
