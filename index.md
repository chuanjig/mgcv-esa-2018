---
layout: page
---

# Welcome to the `mgcv` course webpage.

<img src="images/mgcv-inside-transparent.png" align="right" width="150">A course! To be given at the Ecological Society of America conference in Fort Lauderdale, Saturday August 5th 8am-5pm, 2018. Program link [here](https://eco.confex.com/eco/2018/webprogram/Session13118.html).

This site contains slides, exercises and other materials for the course.

## Course overview

To address the increase in both quantity and complexity of available data, ecologists require flexible, robust statistical models, as well as software to perform such analyses. This workshop will focus on how a single tool, the mgcv package for the R language, can be used to fit models to data from a wide range of sources.

mgcv is one of the most popular packages for modelling non-linear relationships. However, many users do not know how versatile and powerful a tool it can be. This workshop will focus on teaching participants how to use mgcv in a wide variety of situations (including spatio-temporal, zero-inflated, heavy-tailed, time series, and survival data) and advanced use of mgcv (fitting smooth interactions, seasonal effects, spatial effects, Markov random fields and varying-coefficient models).

The workshop will give paricipants an understanding of:

- practical elements of smoothing theory, with a focus on why they would choose to use different types of smoothers
- model checking and selection
- the range of modelling possibilities using mgcv.

Participants will be assumed to be familiar with the basics of R (loading/manipulating data, functions, and plotting) and regression in R (`lm()` and `glm()`). The organizers have extensive practical experience with ecological statistics and modelling using `mgcv`.

## Downloads and Installation

- You should have [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/#download) installed
- Download <https://github.com/noamross/mgcv-esa-2018/archive/master.zip>, unzip, and open `mgcv-esa-2018.Rproj` in RStudio. (You can clone if you are a git user)
- Use `install.packages` to install any of these packages you may not have:

```
install.packages(c(
  "mgcv",
  "plyr",
  "ggplot2",
  "viridis",
  "dplyr",
  "tidyr",
  "mvtnorm",
  "statmod"
))
```
