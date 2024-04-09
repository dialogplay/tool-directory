# Integration for ODPT API
This integration provides API for obtaining ODPT.

## Get /odpt:Station
### Parameters
This API requires at least one argument.

| name | type | description | runtime |
| --- | --- | --- | --- |
| acl:consumerKey | string | Access token provided on developer site | false |
| @id | string | Data identifier | true |
| owl:sameAs | string | Data identifier alternative | true |
| dc:title | string | Station name in japanese. e.g: 東京,新宿,上野 | true |
| odpt:operator | string | Operator id based on ODPT | true |
| odpt:railway | string | Railway id belonging the station | true |
| odpt:stationCode | string | Station number. e.g: OH01=小田急新宿駅 | true |

### Response
This API returns JSON of station information.
The sample of response is as follows.
```JSON
[
  {
    "@context": "http://vocab.odpt.org/context_odpt.jsonld",
    "@id": "urn:ucode:_00001C000000000000010000030FD7E5",
    "@type": "odpt:Station",
    "dc:date": "2017-01-13T15:10:00+09:00",
    "owl:sameAs": "odpt.Station:JR-East.Yamanote.Tokyo",
    "dc:title": "東京",
    "odpt:stationTitle": {
      "ja": "東京",
      "en": "Tokyo"
    },
    "odpt:operator": "odpt.Operator:JR-East",
    "odpt:railway": "odpt.Railway:JR-East.Yamanote",
    "geo:long": 139.1234,
    "geo:lat": 35.1234
  }
]
```


## Examples

```
input: 東京メトロの東京の乗り換え路線を教えて

output: 東京メトロの東京駅の乗り換え路線は以下の通りです：\n1. JR-Central.TokaidoShinkansen\n2. JR-East.AkitaShinkansen\n3. JR-East.ChuoRapid\n4. JR-East.HokurikuShinkansen\n5. JR-East.JobanRapid\n6. JR-East.JoetsuShinkansen\n7. JR-East.KeihinTohokuNegishi\n8. JR-East.Keiyo\n9. JR-East.SobuRapid\n10. JR-East.Takasaki\n11. JR-East.TohokuShinkansen\n12. JR-East.Tokaido\n13. JR-East.Utsunomiya\n14. JR-East.YamagataShinkansen\n15. JR-East.Yamanote\n16. JR-East.Yokosuka

input: 小田急の新宿の情報を教えて

output: 新宿駅は小田急線にあり、駅のIDは'odpt.Station:Odakyu.Odawara.Shinjuku'、所属する路線は'odpt.Railway:Odakyu.Odawara'です。
```