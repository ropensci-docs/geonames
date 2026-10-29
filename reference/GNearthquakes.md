# recent earthquakes

recent earthquakes

## Usage

``` r
GNearthquakes(north, east, south, west, date, minMagnitude, maxRows = 10)
```

## Arguments

- north:

  north bound

- east:

  east bound

- south:

  south bound

- west:

  west bound

- date:

  optional date

- minMagnitude:

  optional minimal magnitude

- maxRows:

  max records to return

## Value

earthquake records

## Details

get recent earthquakes in a region

API doc for GNearthquakes is at
<http://www.geonames.org/export/JSON-webservices.html#earthquakesJSON>

## Author

Barry Rowlingson

## Examples

``` r
if (FALSE) { # \dontrun{
GNearthquakes(north=44.1,south=-9.9,east=-22.4,west=55.2)
} # }
```
