

# Package description
---------------------

A collection of datasets, originally for the book 'Computational Actuarial Science with R' 
edited by Arthur Charpentier. Now, the package contains a large variety of actuarial datasets
for students, teachers and researchers.


# Install
---------------------

Please make sure that [xts](https://CRAN.R-project.org/package=xts), 
[sp](https://CRAN.R-project.org/package=sp), 
[zoo](https://CRAN.R-project.org/package=zoo) packages are installed

To get the current released version from [UQAM](http://cas.uqam.ca/),
[CNRS](http://dutangc.perso.math.cnrs.fr/RRepository/)
or my [website](http://dutangc.free.fr/pub/RRepos/):

``` r
install.packages("CASdatasets", repos = "http://dutangc.free.fr/pub/RRepos/", type="source")
#or 
install.packages("CASdatasets", repos = "http://dutangc.perso.math.cnrs.fr/RRepository/", type="source")
#or
install.packages("CASdatasets", repos = "http://cas.uqam.ca/pub/R/", type="source")
library(CASdatasets)
```

To get the current development version from github, you may try but much longer than downloading the source file from a repository.

``` r
install.packages("devtools")
devtools::install_github("dutangc/CASdatasets", subdir="pkg")
library(CASdatasets)
```

# Authors and contact
---------------------


Issues can be reported on https://github.com/dutangc/CASdatasets/issues.

- Arthur Charpentier: charpentier.arthur<<@>>uqam.ca
- Christophe Dutang: dutangc<<@>>gmail.com

Authors gratefully acknowledge Julien Siharath for building up vignettes for the package.


# Citation
---------------------

If you use `CASdatasets`, you should cite: <br />
Christophe Dutang and Arthur Charpentier (2024). 
*CASdatasets: Insurance datasets*
R package version 1.0-13.
