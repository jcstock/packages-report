test.R
================
xoh067
Tue Jan 15 18:08:19 2019

``` r
library(here)
```

    ## here() starts at /Users/xoh067/Code/2019_rstudio-conf-2019/packages-report

``` r
.libPaths()
```

    ## [1] "/Library/Frameworks/R.framework/Versions/3.5.1-MRO/Resources/library"

``` r
ipt <- installed.packages()

nrow(ipt)
```

    ## [1] 133
