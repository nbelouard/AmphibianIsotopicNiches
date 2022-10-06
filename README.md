# Description

Local isotopic niche partitioning and the coexistence between native amphibians and invasive crayfish 

Invasive species are widely reported to cause local extinctions of native species. The red swamp crayfish, _Procambarus clarkii_, has been repeatedly shown to impact amphibians through predation and competition. Studying species isotopic niches in natural ecosystems where this crayfish coexists with native amphibians is a way to test our comprehension of the mechanisms underlying species coexistence.  

This package contains all the data and R code associated with an article currently submitted to Journal of Animal Ecology.

## Pre-requisites

Please make sure Git is installed on your computer by typing the following line of code in R Terminal (Tools > Terminal > New terminal). If Git is not installed, you will need to download and install Git.
```
git --version 
```

Please make sure you are using the latest version of R (Help > Check for updates) and that all your packages are up to date (Tools > Check for package updates)

## Clone this project locally

Open your R Terminal, and set the working directory to the folder where you want the project to be stored using cd. Then, type:

```
git clone https://github.com/nbelouard/coexistence-isoniches.git
```

## Access and reproduce this analysis

If you wish to reproduce the analyses, once the project is cloned locally:
- access the folder and open the coexistence-isoniches.Rproj file to open the project in Rstudio
- install the package using the R button "install and restart" in the Build tab of Rstudio. 


You can manually access the analyses by opening the vignettes (folder vignettes/).
Or you can automatically run all the vignettes and build a site by using 
```
pkgdown::build_site()
```

# References

For further information, contact @nbelouard

