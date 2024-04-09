# Integration for ODPT API
This integration provides API for obtaining ODPT.

## Get /odpt:Railway
### Parameters
This API requires at least one argument.

| name | type | description | runtime |
| --- | --- | --- | --- |
| acl:consumerKey | string | Access token provided on developer site | false |
| @id | string | Data identifier | true |
| owl:sameAs | string | Data identifier alternative | true |
| dc:title | string | Line name in japanese. e.g: 小田原線、京王線、相模原線 | true |
| odpt:operator | string | Operator id based on ODPT | true |
| odpt:lineCode | string | Line code. Line symbol. e.g: 小田原線 => OH、丸ノ内線 => M | true |

### Response
This API returns JSON of railway information.
The sample of response is as follows.
```JSON
[
  {
    "@context": "http://vocab.odpt.org/context_odpt.jsonld",
    "@id": "urn:ucode:_00001C000000000000010000030FD7E5",
    "@type": "odpt:Railway",
    "dc:date": "2017-01-13T15:10:00+09:00",
    "owl:sameAs": "odpt.Railway:JR-East.ChuoRapid",
    "dc:title": "中央線快速",
    "odpt:railwayTitle": {
      "ja": "中央線快速",
      "en": "Chuo Rapid Line"
    },
    "odpt:operator": "odpt.Operator:JR-East",
    "odpt:ascendingRailDirection": "odpt.RailDirection:Outbound",
    "odpt:descendingRailDirection": "odpt.RailDirection:Inbound",
    "odpt:stationOrder": [
      {
        "odpt:index": 1,
        "odpt:station": "odpt.Station:JR-East.ChuoRapid.Tokyo",
        "odpt:stationTitle": {
          "ja": "東京",
          "en": "Tokyo"
        }
      },
      {
        "odpt:index": 2,
        "odpt:station": "odpt.Station:JR-East.ChuoRapid.Kanda",
        "odpt:stationTitle": {
          "ja": "神田",
          "en": "Kanda"
        }
      },
      {
        "odpt:index": 3,
        "odpt:station": "odpt.Station:JR-East.ChuoRapid.Ochanomizu",
        "odpt:stationTitle": {
          "ja": "御茶ノ水",
          "en": "Ochanomizu"
        }
      }
    ]
  }
]
```


## Examples

```
input: 千代田線の駅名を順に教えて

output: 千代田線の駅名は以下の通りです：\n1. 代々木上原\n2. 代々木公園\n3. 明治神宮前〈原宿〉\n4. 表参道\n5. 乃木坂\n6. 赤坂\n7. 国会議事堂前\n8. 霞ケ関\n9. 日比谷\n10. 二重橋前〈丸の内〉\n11. 大手町\n12. 新御茶ノ水\n13. 湯島\n14. 根津\n15. 千駄木\n16. 西日暮里\n17. 町屋\n18. 北千住\n19. 綾瀬\n20. 北綾瀬
```