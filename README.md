# Description

This project contains all the scripts and data used in the article: N. Belouard, E.J. Petit, J. Cucherousset, J.M. Paillisson (2024). Variation of the stable isotope niches of native amphibians in ponds invaded by the red swamp crayfish, published in Neobiota.

Invasive species are widely reported to cause local extinctions of native populations. The red swamp crayfish, _Procambarus clarkii_, has been repeatedly shown to impact amphibians through predation and competition. Studying the trophic niches of native species in natural ecosystems is a way to better understand the proximate consequences of biological invasions on native species. 

## Pre-requisites

Before you can install this project, please make sure that Git is installed on your computer by typing the following line of code in R Terminal (Tools > Terminal > New terminal). If Git is not installed, you will need to download and install Git on your computer.
```
git --version 
```

In addition, to avoid any incompatibility, please make sure that you are using the latest version of R, and that all your packages are up to date (Tools > Check for package updates). This is the most common cause of errors when running the scripts.

## Clone and install this project locally

Open your R Terminal, and set the working directory to the folder where you want the project to be stored (manually or using cd). Type the following line of code in R Terminal to download all the project files:

```
git clone https://github.com/nbelouard/AmphibianIsotopicNiches.git
```

Then, access the folder and open the AmphibianIsotopicNiche.Rproj file to open the project in Rstudio, and install all the project dependencies and documentation by typing the following line of code in the R console:
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

