---
output: html_document
published: false
---



## Set up your credentials

Go to the developers console and create a new project if you don't already have one: https://console.developers.google.com/

There have been many packages built to access Google Analytics data. I recommend installing the RGA package:


```r
install.packages("RGA")
```


```r
require(dygraphs)
```

```
## Loading required package: dygraphs
```

```
## Warning in library(package, lib.loc = lib.loc, character.only = TRUE,
## logical.return = TRUE, : there is no package called 'dygraphs'
```

```r
lungDeaths <- cbind(mdeaths, fdeaths)
dygraph(lungDeaths)
```

```
## Error in dygraph(lungDeaths): could not find function "dygraph"
```

-----


```
## R version 3.4.1 (2017-06-30)
## Platform: x86_64-apple-darwin15.6.0 (64-bit)
## Running under: macOS Sierra 10.12.6
## 
## Matrix products: default
## BLAS: /System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vecLib.framework/Versions/A/libBLAS.dylib
## LAPACK: /Library/Frameworks/R.framework/Versions/3.4/Resources/lib/libRlapack.dylib
## 
## locale:
## [1] en_NZ.UTF-8/en_NZ.UTF-8/en_NZ.UTF-8/C/en_NZ.UTF-8/en_NZ.UTF-8
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## other attached packages:
## [1] markdown_0.8 knitr_1.17  
## 
## loaded via a namespace (and not attached):
## [1] compiler_3.4.1  magrittr_1.5    tools_3.4.1     yaml_2.1.14    
## [5] stringi_1.1.5   highr_0.6       stringr_1.2.0   evaluate_0.10.1
```
