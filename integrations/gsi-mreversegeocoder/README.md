# Integration for GSI reverse geocoding API (国土地理院API)
This integration provides API to convert geo coordinates to address specified by users.

## Get /reverse-geocoder/LonLatToAddress
### Parameters
This API requires two arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| lat | number | Latitude to convert to address | true |
| lon | number | Longitude to convert to address | true |

### Response
This API returns JSON of current time information.
The sample of response is as follows.
```JSON
{
  "results": {
    "muniCd": "27128",
    "lv01Nm": "大阪城"
  }
}
```

## Examples

```
input: Tell me address of 35.7281866,139.7953495.

output: The address for the coordinates 35.7281866,139.7953495 is Nihon Tsutsumi 2-chome, Japan.

input: 35.6549426,139.7945008の住所を教えて

output: 指定された座標の住所は '豊洲二丁目' です。
```