<!-- badges: start -->
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Travis build status](https://travis-ci.org/roblanf/sangeranalyseR.svg?branch=master)](https://travis-ci.org/roblanf/sangeranalyseR) ![documentation build status](https://readthedocs.org/projects/pip/badge/) ![os](https://img.shields.io/badge/platform-macOS_/Linux_/Windows-green.svg)
<!-- badges: end -->

# Description:
This is a forked version of **sangeranalyseR** with a fix for the deprecated <code>TreeLine</code> function in newer releases of the **DECIPHER** package dependency.

# Changes Made:
  - UtilitiesFunc.R&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;TreeLine -> Treeline (Line 336)
  - sangeranalyseR_package.R	&nbsp;&nbsp;&nbsp;&nbsp;TreeLine -> Treeline (Line 19)

# Installation:
How to install this fixed version of **sangeranalyseR**
```r
remotes::install_github("bdaisley/
```
# Reference:
See here for the main **sangeranalyseR** GitHub page: [https://github.com/roblanf/sangeranalyseR](https://github.com/roblanf/sangeranalyseR)
