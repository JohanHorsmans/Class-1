Untitled
================
Johan Horsmans
4/26/2021

  - [No](#no)
  - [shit](#shit)

# No

### Hi

``` r
library(tidyverse)
```

    ## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.0 ──

    ## ✓ ggplot2 3.3.3     ✓ purrr   0.3.4
    ## ✓ tibble  3.1.0     ✓ dplyr   1.0.3
    ## ✓ tidyr   1.1.2     ✓ stringr 1.4.0
    ## ✓ readr   1.4.0     ✓ forcats 0.5.1

    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

``` r
library(sf)
```

    ## Linking to GEOS 3.6.2, GDAL 2.2.3, PROJ 4.9.3

``` r
library(pacman)
p_load(rmarkdown)

2+2
```

    ## [1] 4

# shit

``` r
"asdashashdasd" 
```

    ## [1] "asdashashdasd"

``` r
organic_fields_2012<-st_read("data/Oekologiske_arealer_2012.shp") %>% na.omit()
```

    ## Reading layer `Oekologiske_arealer_2012' from data source `/home/cds-au618771/cds-spatial/groundwater_polution_dk/data/Oekologiske_arealer_2012.shp' using driver `ESRI Shapefile'
    ## Simple feature collection with 49904 features and 5 fields
    ## geometry type:  POLYGON
    ## dimension:      XY
    ## bbox:           xmin: 445062.9 ymin: 6050575 xmax: 891630.3 ymax: 6391823
    ## proj4string:    +proj=utm +zone=32 +ellps=GRS80 +units=m +no_defs

``` r
plot(st_geometry(organic_fields_2012$geometry))
```

<img src="test_files/figure-gfm/unnamed-chunk-2-1.png" width="65%" style="float:right; padding:10px" />

aLorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
occaecat cupidatat non proident, sunt in culpa qui officia deserunt
mollit anim id est laborum.Lorem ipsum dolor sit amet, consectetur
adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa
qui officia deserunt mollit anim id est laborum.Lorem ipsum dolor sit
amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Hi

``` r
#asasdl
```
