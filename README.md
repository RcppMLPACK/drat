## drat repository

This [drat](http://dirk.eddelbuettel.com/code/drat.html) package repository provides RcppMLPACK
packages. In particular it used for pre-release of _RcppMLPACK2_ which is based on
[MLPACK](https://www.mlpack.org) version 2.* which is not on [CRAN](https://cran.r-project.org)


### Usage

```{.r}
# first add the repo
drat::addRepo("RcppMLPACK")
# either install just one or more given packages
install.packages("RcppMLPACK")
# or update already installed packages
update.packages()
```

### License

Packages in this repository are available under their respective license, which is generally GPL
version 2 or newer.
