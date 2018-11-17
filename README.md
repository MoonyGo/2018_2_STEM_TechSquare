# 2018 STEM TechSquare
================================
2018 STEM TechSquare, 2018.11.17, 14:00 - 17:00, Bayesian in Machine Learning: Probabilistic Programming with Stan

1. Slides
https://docs.google.com/presentation/d/1rkx6hBldIsKmsCPVJ2tZyyeaWMUMwmBOtVS8eA4cwwo/edit?usp=sharing

2. Please download this repository and open the RStudio project file `STEM_TechSquare2018.Rproj`.

In addition to the **rstan** package, which you should already have installed (if not see https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started), please install the following packages if not already installed:

```r
packages <- c(
    'bayesplot', 
    'ggplot2', 
    'lubridate', 
    'rmarkdown', 
    'shinystan', 
    'tidyverse'
)
install.packages(packages)
```
