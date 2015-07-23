trNB: an R package for truncated negative binomial and truncated Poisson family objects
---------------------------------------------------------------------------------------

This R package defines family objects truncNB(sigma) for truncated negative binomial with a user-specified value of the overdispersion parameter sigma, and truncPoi for truncated Poisson. Both these families can be used and have been tested with stats::glm and mgcv::gam. The package also includes wrappers for glm(formula, family = truncNB(sigma)) and gam(formula, family = truncNB(sigma), optimizer = 'perf') with iteration with the maximum likelihood estimation of sigma, given the fitted means. For an overview and more details, see the package main help page by running help(trNB) after installation.

Package updates can be found at https://github.com/williamaeberhard/trnb.

Any requests/comments/bug reports should be sent to william.aeberhard@gmail.com.

### Contents

Files contained in this repository:

* trNB_0.3.tar.gz, a tarball containing the R package to be installed from R, see below;
* a LICENSE file;
* this README file.

### Version History

This is trNB version 0.3. This is the initial release.

Tested and compiled on R version 3.0.2. R CMD check returned all ok.

### Package Installation

1. Open R.
2. Make sure your working directory contains the file trNB_0.3.tar.gz.
3. Run install.packages('trNB_0.3.tar.gz',repos=NULL,type='source').
4. Load the package by running library(trNB).
5. Check out the main help page by running help(trNB).
