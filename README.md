# Description

Coexistence between an invasive crayfish and native amphibians through non-overlapping isotopic niches. 

Invasive species are widely reported to cause local extinctions of native species. Where native species do persist, there is a unique opportunity to observe the mechanisms of coexistence at play and the modifications induced by the arrival of the invasive species.

The red swamp crayfish, _Procambarus clarkii_, has been repeatedly shown to alter communities of aquatic ecosystems in its invasive range, and multiple reports of amphibian species decline are of particular concern. The generalist and omnivorous diet of this crayfish, associated to its burrowing activity, makes it interacting in multiple ways with amphibians. Predation on larval amphibians, antagonistic behavioral interactions with newts, depletion of the aquatic vegetation required to their reproduction, modification of resource availability and of water quality have all been detected in experimental conditions. Studying the food webs of natural ecosystems where this crayfish coexists with native amphibians is a way to advance the comprehension of the mechanisms underlying the settlement of species coexistence. 

Despite multiple records of local amphibian extinctions after the introduction of the red swamp crayfish, the stable coexistence of these species has been observed in pond networks of the Natural Regional Park of Brière in northwestern France. What can be learned on the mechanisms of this coexistence based on isotopic niches?


## Clone this project locally

Open your R Terminal, and set the working directory to the folder where you want the project to be stored using cd. Then, type:

```
git clone git@gitlab.com:nbelouard/coexistence_isoniches.git
```

## (optional) Prepare your R for the analyses

The jumpID package relies on a variety of other R packages to function. They are specified as Imports in the DESCRIPTION file, and will be automatically installed with the jumpID package. If you wish to prepare the R environment for the jumpID package manually, you can do so by pasting this command into R or RStudio.

```
install.packages(c('tidyverse', 'here', 'magrittr', 'rmarkdown', 'ggplot2', 'pkgdown', 'knitr', 'sf', 'maps', 'DescTools', 'geosphere', 'leaflet', 'dplyr', 'gridExtra', 'ape', 'spdep', 'roxygen2'))
```

## Access and reproduce this analysis

If you wish to reproduce the analyses, once the project is cloned locally:
- access the folder and open the jumpID.Rproj file to open the project in Rstudio
- install the package using the R button "install and restart" in the Build tab of Rstudio. 

You can automatically run all the vignettes and build a site by using 
```
pkgdown::build_site()
```

You can manually access the analyses by opening the vignettes (folder vignettes/), modifying the code and running them.

# References

For further information, contact @nbelouard

