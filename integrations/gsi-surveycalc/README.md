# Integration for Survey calculation API (国土地理院API)
This integration provides API to calculate distance of two geo coordinates specified by users.
This tool can calculate distance between two locations without directly entering geo coordinates if LLM knows ones of locations.

## Get /sokuchi/surveycalc/surveycalc/bl2st_calc.pl
### Parameters
This API requires six arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| outputType | string | Output type xml or json. default value is json | true |
| ellipsoid | string | Geodetic system. GRS80 or bessel. defaul tvalue is bessel | true |
| latitude1 | number | Latitude of origin point | true |
| longitude1 | number | Longitude of origin point | true |
| latitude2 | number | Latitude of destination point | true |
| longitude2 | number | Longitude of destination point | true |

### Response
This API returns JSON of distance and azimuth information.
The sample of response is as follows.
```JSON
{
  "OutputData": {
    "geoLength": "8227.36",
    "azimuth1": "45.9278833333333",
    "azimuth2": "225.965988888889"
  }
}
```

## Examples

```
input: Tell me distance of between Tokyo tower and Tokyo sky tree.

output: The distance between Tokyo Tower and Tokyo Sky Tree is approximately 8217.867 meters.

input: Tell me distance of between 東京タワー and 東京スカイツリー.

output: The distance between 東京タワー and 東京スカイツリー is approximately 8227.360 meters.

input: 東京タワーの地理情報と東京スカイツリーの地理情報から距離を教えて。

output: 東京タワーと東京スカイツリーの間の距離は約8227.360メートルです。
```
