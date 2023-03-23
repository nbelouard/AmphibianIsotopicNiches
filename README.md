# Description

This project contains all the scripts and data used in the article: N. Belouard, E.J. Petit, J. Cucherousset, J.M. Paillisson. Local stable isotope niche partitioning and the coexistence between native amphibians and invasive crayfish, currently submitted to Oecologia.

Invasive species are widely reported to cause local extinctions of native species. The red swamp crayfish, _Procambarus clarkii_, has been repeatedly shown to impact amphibians through predation and competition. Studying species isotopic niches in natural ecosystems where this crayfish coexists with native amphibians is a way to test our comprehension of the mechanisms underlying species coexistence.  

## Pre-requisites

Before you can install this project, please make sure that Git is installed on your computer by typing the following line of code in R Terminal (Tools > Terminal > New terminal). If Git is not installed, you will need to download and install Git on your computer.
```
git --version 
```

In addition, to avoid any incompatibility, please make sure that you are using the latest version of RStudio (Help > Check for updates) and that all your packages are up to date (Tools > Check for package updates).  

## Clone and install this project locally

Open your R Terminal, and set the working directory to the folder where you want the project to be stored (manually or using cd). Type the following line of code in R Terminal to download all the project files:

```
git clone https://github.com/nbelouard/coexistence-isoniches.git
```

Then, access the folder and open the coexistence-isoniches.Rproj file to open the project in Rstudio, and install all the project dependencies and documentation by typing the following line of code in the R console:
```
devtools::document()
```


## Access and reproduce this analysis

You can manually access the analyses by opening the vignettes (folder vignettes/).  
Or you can automatically run all the vignettes using the following line of code; it will build a site that compiles all the vignettes and in which the code will still be visible.
```
pkgdown::build_site()
```

# References

For further information, contact @nbelouard

