# search geonames

search geonames

## Usage

``` r
GNsearch(...)
```

## Arguments

- ...:

  search parameters

## Value

matched records

## Details

general search call

API doc for GNsearch is at
[http://www.geonames.org/export/geonames-search.html](http://www.geonames.org/export/geonames-search.md)

## Author

Barry Rowlingson

## Examples

``` r
if (FALSE) { # \dontrun{
# Find places called Lancaster and 'geocode' the result
(lanc_df <- GNsearch(name = "Lancaster", country = "UK"))
lanc_coords <- lanc_df[1, c("lng", "lat")]
} # }
```
