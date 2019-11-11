# EVPI Poster

## Poster on the use of Expected Value of Perfect Information (EVPI)

Use the `postr` package and `rmarkdown` `flexdashboard` and `webshot` to re-create the poster template from [odeleongt](https://odeleongt.github.io/postr/). 

### Preparing a new poster
Install odeleongt/postr package from github

`devtools::install_github("odeleongt/postr")`

### Create a new R Markdown document in Rstudio based on the poster template, or run

`rmarkdown::draft("EVPI_poster.Rmd", template = "poster", package = "postr")`

Render a printable A1 image

`postr::render("EVPI_poster/EVPI_poster.Rmd")`

## References

JJ Allaire, Yihui Xie, Jonathan McPherson, Javier Luraschi, Kevin Ushey, Aron Atkins, Hadley Wickham, Joe Cheng and Winston Chang (2017). rmarkdown: Dynamic Documents for R. R package version 1.8. https://CRAN.R-project.org/package=rmarkdown

Barbara Borges and JJ Allaire (2017). flexdashboard: R Markdown Format for Flexible Dashboards. R package version 0.5.1. https://CRAN.R-project.org/package=flexdashboard

Winston Chang (2017). webshot: Take Screenshots of Web Pages. R package version 0.5.0. https://CRAN.R-project.org/package=webshot