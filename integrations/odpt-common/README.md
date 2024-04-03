# Integration for ODPT API
This integration provides API for obtaining ODPT.

## Get /odpt:Calendar
### Parameters
This API requires at least one argument.

| name | type | description | runtime |
| --- | --- | --- | --- |
| acl:consumerKey | string | Access token provided on developer site | false |
| @id | string | Data identifier | true |
| owl:sameAs | string | Data identifier alternative | true |

### Response
This API returns JSON of calendar information.
The sample of response is as follows.
```JSON
[ {
  "@context" : "http://vocab.odpt.org/context_odpt.jsonld",
  "@id" : "urn:ucode:_00001C000000000000010000030FD7E5",
  "@type" : "odpt:Calendar",
  "dc:date" : "2017-01-13T15:10:00+09:00",
  "owl:sameAs" : "odpt.Calendar:Weekday",
  "dc:title" : "平日",
  "odpt:calendarTitle" : {
    "ja" : "平日",
    "en" : "Weekday"
  }
} ]
```


## Get /odpt:Operator
### Parameters
This API requires at least one argument.

| name | type | description | runtime |
| --- | --- | --- | --- |
| acl:consumerKey | string | Access token provided on developer site | false |
| @id | string | Data identifier | true |
| owl:sameAs | string | Data identifier alternative | true |

### Response
This API returns JSON of operator information.
The sample of response is as follows.
```JSON
[ {
  "@context" : "http://vocab.odpt.org/context_odpt.jsonld",
  "@id" : "urn:ucode:_00001C000000000000010000030FD7E5",
  "@type" : "odpt:Operator",
  "dc:date" : "2017-01-13T15:10:00+09:00",
  "owl:sameAs" : "odpt.Operator:JR-East",
  "dc:title" : "JR東日本",
  "odpt:operatorTitle" : {
    "ja" : "JR東日本",
    "en" : "JR East"
  }
} ]
```


## Examples

```
input: Is Kintetsu included in ODPT operator?

output: No, Kintetsu is not included in the ODPT operator list.

input: 近鉄はODPTの事業者に含まれる？

output: No, Kintetsu is not included in the ODPT's operators.

input: Let me know about Tokyo Metro operator id.

output: The Tokyo Metro operator has the ID 'urn:ucode:_00001C000000000000010000030E6600', the type 'odpt:Operator', and the date '2022-02-24T08:00:00+09:00'. Its title is '東京メトロ' and the 'owl:sameAs' is 'odpt.Operator:TokyoMetro'. The operator title is 'Tokyo Metro' in English and '東京メトロ' in Japanese.

input: ODPTの東京メトロのidを教えて

output: The ID of Tokyo Metro in ODPT is 'urn:ucode:_00001C000000000000010000030E6600'.
```