
<!-- README.md is generated from README.Rmd. Please edit that file -->

# TutorialIterar

<!-- badges: start -->

<!-- badges: end -->

El objetivo de este paquete contiene dos tutoriales para introducir el
concepto de iteración en R.

La iteración es la tarea de aplicar una función de forma iterativa a
cada elemento de un vector. El primer tutorial explicará qué es un
vector e introducirá dos formas de iterar en R: bucles *for* y el
paquete *purrr*.

El segundo tutorial introduce la familia de funciones *map* de *purrr*
para hacer que la iteración sea rápida y fácil. Aprenderás los secretos de
*map()* y sus variantes.

## Instalación

Para instalar la versión de desarrollo desde GitHub, usá:

``` r
# install.packages("remotes")
remotes::install_github("yabellini/TutorialIterar")
```

Si no tenes la ultima versión entonces tenés que instalar el paquete
learnr y luego ejecutar de esta manera el Tutorial:

  - Tutorial *Primeros pasos* para iterar con R:

<!-- end list -->

``` r
learnr::run_tutorial("PrimerosPasos", package = "TutorialIterar")
```

  - Tutorial *Introducción a las funciones Map* :

<!-- end list -->

``` r
learnr::run_tutorial("IntroFuncionesMap", package = "TutorialIterar")
```
