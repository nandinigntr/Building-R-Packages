---
title: "README"
author: "Nandini Guntur"
date: "08/07/2020"
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# FARS.functions

This package is the final assignment of the course "Building R Packages" from Coursera. It contains functions to map the data from the US National Highway Traffic Safety Administration's Fatality Analysis Reporting System (FARS).

At this repository you will find:

1. A DESCRIPTION and NAMESPACE file;
2. An R/ folder where the fars_functions.R are stored;
3. A man/ folder presenting the functions documented using ```roxygen2``` package;
4. A vignettes/ folder which includes a meaningful description of the package and some examples.
5. A tests/ folder with a test of the functions output


## Installation

Follow the steps below to install this package on you system.

1. Install the ```devtools``` package.
2. Install and load the ```FARS.functions``` package:
  - install_github("lahstorti/FARS.functions")
  - library("FARS.functions")



## Raw Data

This package contains a raw data file. To access this data you can use this lines of code:

