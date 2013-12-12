# Installing Bioconductor and finding help

## Installing Bioconductor

Installing Bioconductor from the R command line takes only two lines:


```r
source("http://bioconductor.org/biocLite.R")
biocLite()
```


## Finding help


```r
`?`(functionName)
`?`("eSet-class"  # classes need the '-class' on the end
)
vignette("topic")
browseVignettes(package = "package")  # show vignettes for the package
functionName  # prints source code
getMethod("method", "class")  # prints source code for methods
showMethods(classes = "class")  # show all methods for class
```

