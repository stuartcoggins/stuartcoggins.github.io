---
title       : Random Number Generator
subtitle    : A Shiny demo
author      : Stuart
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

- You may find yourself in a situation where you need some random numbers from a normal distribution
- You also want to specify the mean and the standard deviation of those numbers
- My random number generator has this function

--- .class #id 

## Generating random numbers manually

The following R code produces some random normally distributed numbers:


```r
rnorm(10)
```

```
##  [1] -0.45435820 -0.39812728  0.69267170  0.09603216  2.03803119
##  [6]  0.67671288 -0.78418740 -0.41417676  0.90378870  0.79931571
```

But it would be preferable if we had an online tool with controls that made it easier to change parameters.

--- .class #id
## Where to find the tool

You can find the random number generator at https://stuartcoggins.shinyapps.io/dataproducts


--- .class #id
## Thank you

Thank you for your time and I hope you find the random number generator app useful!
