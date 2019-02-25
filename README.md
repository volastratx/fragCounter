
<!-- README.md is generated from README.Rmd. Please edit that file -->



[![Build Status](https://travis-ci.org/mskilab/fragCounter.svg?branch=master)](https://travis-ci.org/mskilab/fragCounter) [![codecov.io](https://img.shields.io/codecov/c/github/mskilab/fragCounter.svg)](https://codecov.io/github/mskilab/fragCounter?branch=master)

fragCounter
===========

The goal of fragCounter is to correct WGS data for GC and mappability bias. The GC bias curve is determined by loess regression of read count by GC and mappability scores. Segmentation is done by circular binary segmentation (CBS) algorithm after getting tumor/normal ratios of corrected read counts.

Installation
------------

You can install fragCounter from github with:

``` {.r}
# install.packages("devtools")
devtools::install_github("mskilab/fragCounter")
```

Example:
-------

This is a basic example which shows you how to solve a common problem:

``` {.r}
## basic example code
```
