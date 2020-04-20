inaturalist Flexboard
inat_flexdashboard_ARG
====

```{r echo=FALSE}
knitr::opts_chunk$set(
  warning = FALSE,
  message = FALSE,
  collapse = TRUE,
  comment = "#>"
)
```

Create a Flexdashboard in R Markdown to visualize observations data from a inaturalist project. Data may be obtained using the "rinat" package or downloaded from [inaturalist](https://www.inaturalist.org/) web site and imported via .csv. This Flexdashboard is made using data from the project [Biodiversidad Marina Bahía Pardelas](https://www.argentinat.org/projects/biodiversidad-marina-bahia-pardelas).

##Sources
Package used for getting inaturalist data:
* [rinat](https://github.com/ropensci/rinat)

Package for making maps of species occurrence data:
* [mapr](https://github.com/ropensci/mapr)


## Installation packages

Install `rinat`

Only available in the development version from GitHub
```{r eval=FALSE}
devtools::install_github("ropensci/rinat")
```



[![psub_footer](https://www.proyectosub.org.ar/wp-content/uploads/2020/04/logocepillos.png)](https://proyectosub.org)
