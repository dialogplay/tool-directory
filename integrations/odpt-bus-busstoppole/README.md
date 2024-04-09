# Integration for ODPT API
This integration provides API for obtaining ODPT.

## Get /odpt:BusstopPole
### Parameters
This API requires at least one argument.

| name | type | description | runtime |
| --- | --- | --- | --- |
| acl:consumerKey | string | Access token provided on developer site | false |
| @id | string | Data identifier | true |
| owl:sameAs | string | Data identifier alternative | true |
| dc:title | string | Bus stop pole name in japanese. e.g: 豊洲駅前 | true |
| odpt:busstopPoleNumber | string | busstop pole number. 標柱番号 | true |
| odpt:platformNumber | string | platform number. のりば番号 | true |
| odpt:operator | string | Operator id based on ODPT | true |

### Response
This API returns JSON of bus stop pole information.
The sample of response is as follows.
```JSON
[
  {
    "@context": "http://vocab.odpt.org/context_odpt_BusstopPole.jsonld,",
    "@type": "odpt:BusstopPole",
    "owl:sameAs": "odpt.BusstopPole:Toei.Akabaneekihigashiguchi.21.1",
    "dc:date": "2017-11-14T17:44:05+09:00",
    "dc:title": "赤羽駅東口",
    "odpt:kana": "あかばねえきひがしぐち",
    "geo:long": 139.7214941,
    "geo:lat": 35.7790549,
    "odpt:busroutePattern": [
      "odpt.BusroutePattern:Toei.Ou57.40301.1",
      "odpt.BusroutePattern:Toei.Ou57.40301.2",
      "odpt.BusroutePattern:Toei.Ou57.40302.2"
    ],
    "odpt:operator": [
      "odpt.Operator:Toei"
    ],
    "odpt:busstopPoleNumber": "1",
    "odpt:busstopTimetable": [
      "odpt.BusstopPoleTimetable:Toei.Ou57.Akabaneekihigashiguchi.21.1.Toshimagochoumedanchi.Holiday",
      "odpt.BusstopPoleTimetable:Toei.Ou57.Akabaneekihigashiguchi.21.1.Toshimagochoumedanchi.Saturday",
      "odpt.BusstopPoleTimetable:Toei.Ou57.Akabaneekihigashiguchi.21.1.Toshimagochoumedanchi.Weekday"
    ]
  }
]
```


## Get /places/odpt:BusstopPole
### Parameters
This API requires at least four arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| acl:consumerKey | string | Access token provided on developer site | false |
| lat | number | Specify the center latitude of the acquired range, decimal notation, the geodetic system WGS84 | true |
| lon | number | Specify the center longitude of the acquired range, decimal notation, the geodetic system WGS84 | true |
| radius | number | Specify the radius of the acquisition range in meters, the range of 0-4000m | true |
| @id | string | Data identifier | true |
| owl:sameAs | string | Data identifier alternative | true |
| dc:title | string | Bus stop pole name in japanese. e.g: 豊洲駅前 | true |
| odpt:busstopPoleNumber | string | busstop pole number. 標柱番号 | true |
| odpt:platformNumber | string | platform number. のりば番号 | true |
| odpt:operator | string | Operator id based on ODPT | true |

### Response
This API returns JSON of bus stop pole information.
The sample of response is as follows.
```JSON
[
  {
    "@context": "http://vocab.odpt.org/context_odpt_BusstopPole.jsonld,",
    "@type": "odpt:BusstopPole",
    "owl:sameAs": "odpt.BusstopPole:Toei.Akabaneekihigashiguchi.21.1",
    "dc:date": "2017-11-14T17:44:05+09:00",
    "dc:title": "赤羽駅東口",
    "odpt:kana": "あかばねえきひがしぐち",
    "geo:long": 139.7214941,
    "geo:lat": 35.7790549,
    "odpt:busroutePattern": [
      "odpt.BusroutePattern:Toei.Ou57.40301.1",
      "odpt.BusroutePattern:Toei.Ou57.40301.2",
      "odpt.BusroutePattern:Toei.Ou57.40302.2"
    ],
    "odpt:operator": [
      "odpt.Operator:Toei"
    ],
    "odpt:busstopPoleNumber": "1",
    "odpt:busstopTimetable": [
      "odpt.BusstopPoleTimetable:Toei.Ou57.Akabaneekihigashiguchi.21.1.Toshimagochoumedanchi.Holiday",
      "odpt.BusstopPoleTimetable:Toei.Ou57.Akabaneekihigashiguchi.21.1.Toshimagochoumedanchi.Saturday",
      "odpt.BusstopPoleTimetable:Toei.Ou57.Akabaneekihigashiguchi.21.1.Toshimagochoumedanchi.Weekday"
    ]
  }
]
```


## Examples

```
input: 東京スカイツリー、半径300m以内のバス停を教えて

output: Here are the bus stops within a 300m radius of the Tokyo Skytree: \n1. Oshiage \n2. Oshiage Sta. \n3. TOKYO SKYTREE Sta. Iriguchi \n4. TOKYO SKYTREE Sta. \n5. とうきょうスカイツリー駅入口

input: 経度139.7214941、緯度35.7790549、半径100m以内のバス停を教えて

output: The bus stop within 100m of the given coordinates is 'Akabane Sta. Higashiguchi (East Exit)' or '赤羽駅東口' in Japanese. The bus stop pole number is 1. It is operated by Toei and has two bus route patterns: 'odpt.BusroutePattern:Toei.Ou57.40301.1' and 'odpt.BusroutePattern:Toei.Ou57.40301.2'.
```