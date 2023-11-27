# Integration for GSI geocoding API (国土地理院API)
This integration provides API to convert address to geo coordinates specified by users.

## Get /address-search/AddressSearch
### Parameters
This API requires one arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| q | string | Address to convert to geo coordinates | true |

### Response
This API returns JSON of geo coordinates information.
The sample of response is as follows.
```JSON
[
  {
    "geometry": {
      "coordinates": [
        135.527472906394,
        34.6866027171863
      ],
      "type": "Point"
    },
    "type": "Feature",
    "properties": {
      "addressCode": "27128",
      "title": "大阪城",
      "dataSource": "5"
    }
  }
]
```

## Examples

```
input: Please tell me geo coordinates of 東京タワー.

output: The geo coordinates of 東京タワー are [139.745384871667, 35.6579641891667].

input: 東京タワーの経度、緯度を教えて

output: 東京タワーの経度は139.745384871667、緯度は35.6579641891667です。。
```
