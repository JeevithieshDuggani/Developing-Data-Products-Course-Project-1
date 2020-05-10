RMarkdown and Leaflet
================

  - [Output the current Date](#output-the-current-date)
  - [Import leaflet](#import-leaflet)
  - [Display the current map of
    India](#display-the-current-map-of-india)

## Output the current Date

10 May, 2020

## Import leaflet

``` r
    suppressPackageStartupMessages(library(leaflet))
```

## Display the current map of India

``` r
    m <- leaflet() %>% addTiles() %>% addAwesomeMarkers(lng = 60.6452449, lat = 36.526833099999998, popup = "I am not here")
```
