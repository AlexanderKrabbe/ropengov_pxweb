pxweb
====== 

[![Build Status](https://travis-ci.org/rOpenGov/pxweb.svg?branch=master)](https://travis-ci.org/rOpenGov/pxweb) [![Build status](https://ci.appveyor.com/api/projects/status/40abe0fpxw2jftf3/branch/master?svg=true)](https://ci.appveyor.com/project/MansMeg/pxweb/branch/master)
[![Stories in Ready](https://badge.waffle.io/ropengov/pxweb.png?label=TODO)](http://waffle.io/ropengov/pxweb)
[![Coverage Status](https://coveralls.io/repos/rOpenGov/pxweb/badge.svg)](https://coveralls.io/r/rOpenGov/pxweb) [![rstudio mirror downloads](http://cranlogs.r-pkg.org/badges/grand-total/pxweb)](https://github.com/metacran/cranlogs.app)
[![cran version](http://www.r-pkg.org/badges/version/pxweb)](http://cran.rstudio.com/web/packages/pxweb) [![Join the chat at https://gitter.im/rOpenGov/pxweb](https://badges.gitter.im/rOpenGov/pxweb.svg)](https://gitter.im/rOpenGov/pxweb?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The easiest way to use pxweb is to simply install it from CRAN:

```r
install.packages('pxweb')
```

To get the latest stabile development version use:

```r
library(devtools)
install_github('ropengov/pxweb')
```

In some cases, the organization requires manual proxy settings. This can be set as follows:

```r
library(devtools)
library(httr)
set_config(
  use_proxy(url="organizationProxyURL", port=1234)
)
install_github('ropengov/pxweb')
```
 


# Overview of pxweb R package

pxweb is an R package to interface with the PX-WEB API, and it offers
methods to utilize information about the data hierarchy stored behind
the PXWEB API used by many Statistics authorities. Many API services 
are still in their early stages, and data quality is sometimes 
compromised. Issue reports are welcome.

For installation and usage, check the [tutorial/vignette](https://htmlpreview.github.io/?https://github.com/rOpenGov/pxweb/blob/test/vignettes/pxweb.html).  

Authors: [Måns Magnusson](https://github.com/MansMeg/), [Leo Lahti](https://github.com/antagomir). Part of [rOpenGov](http://ropengov.github.io/).
  
You are welcome to contact us:

  * [submit suggestions and bug reports](https://github.com/ropengov/pxweb/issues) (provide the output of `sessionInfo()` and `packageVersion("pxweb")`)
  * [send a pull request](https://github.com/ropengov/pxweb/)
  * public email list ropengov-forum@googlegroups.com
  * join IRC at ropengov@Freenode
  * [join or follow our community](http://ropengov.github.io/contribute/)  

