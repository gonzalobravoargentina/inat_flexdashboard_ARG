inat_flexdashboard_ARG
====

Create a Flexdashboard in R Markdown to visualize observations data from a inaturalist project. Data may be obtained using the "rinat" package, by API or downloaded from [inaturalist](https://www.inaturalist.org/) web site and imported via .csv. This Flexdashboard is made using data from the project [Biodiversidad Marina Bahía Pardelas](https://www.argentinat.org/projects/biodiversidad-marina-bahia-pardelas) and [Invertebrados Marinos Golfo Nuevo](https://www.argentinat.org/projects/invertebrados-marinos-golfo-nuevo) 

## Sources

Package used for getting inaturalist data:
* [rinat](https://github.com/ropensci/rinat)

Package for making maps of species occurrence data:
* [mapr](https://github.com/ropensci/mapr)

Package for importing observations using API:
* [curlconverter](https://github.com/hrbrmstr/curlconverter)

Code for exotic species Bubble Plot from:
* [Alexis Catherine](https://alexis-catherine.github.io/visualization/inaturalist-invasive-bubble-plot/)

## Installation packages

Install `rinat`

Only available in the development version from GitHub
```{r eval=FALSE}
devtools::install_github("ropensci/rinat")
```
Install `curlconverter`

Only available in the development version from GitHub
```{r eval=FALSE}
devtools::install_github("hrbrmstr/curlconverter")
```


[![psub_footer](https://www.proyectosub.org.ar/wp-content/uploads/2020/04/logoletras_org.png)](https://proyectosub.org.ar)
