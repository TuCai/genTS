---
title: "README"
author: "Hanming Tu"
date: "10/17/2019"
output: html_document
---

## About this package


This is a R Shiny app for creating simplified TS domain to meet FDA requirement for data submission. 

## How to install 


* Install from CRAN

```
install.packages(“genTS”)
```

* Install from GitHub

```
install.packages("devtools")
library(devtools)
install_github(”TuCai/genTS")
```

## How to use

```
library(genTS)
start_app()               # start with default settings
start_app(msg_lvl = 3)    # start and display detailed message at level 3
start_app(n=7)            # to start the 7th application
```

## Package history

* V0.1.0

Did not submit to CRAN

* V0.1.1

01/20/2020: Submitted to CRAN 
