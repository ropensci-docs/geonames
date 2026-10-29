# Query the geonames web API for geographic data

www.geonames.org is a service where you can query for global geographic
data such as administrative areas, populated places, weather data etc.

## Details

The functions in this package are mostly thin wrappers to the API calls
documented at the geonames web services overview
[http://www.geonames.org/export/ws-overview.html](http://www.geonames.org/export/ws-overview.md).

A set of example calls are supplied in a file with the package. Once you
have set your geonames username with
`options(geonamesUsername="myusernamehere")` you can run this with
`source(system.file("tests","testing.R",package="geonames"),echo=TRUE)`
