# Integration for TimeAPI
This integration provides API for obtaining time information of the timezone specified by users.

## Get /api/Time/current/zone
### Parameters
This API requires one arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| timeZone | string | Timezone for obtaining time information | true |

### Response
This API returns JSON of current time information.
The sample of response is as follows.
```JSON
{
  "year":2023,
  "month":9,
  "day":14,
  "hour":16,
  "minute":42,
  "seconds":9,
  "milliSeconds":476,
  "dateTime":"2023-09-14T16:42:09.4764246",
  "date":"09/14/2023",
  "time":"16:42",
  "timeZone":"Asia/Tokyo",
  "dayOfWeek":"Thursday",
  "dstActive":false
}
```

## Get /api/Time/current/coordinate
### Parameters
This API requires two arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| latitude | number | Latitude for obtaining time information | true |
| longitude | number | Longitude for obtaining time information | true |

### Response
This API returns JSON of current time information.
The sample of response is as follows.
```JSON
{
  "year":2023,
  "month":9,
  "day":14,
  "hour":16,
  "minute":42,
  "seconds":9,
  "milliSeconds":476,
  "dateTime":"2023-09-14T16:42:09.4764246",
  "date":"09/14/2023",
  "time":"16:42",
  "timeZone":"Asia/Tokyo",
  "dayOfWeek":"Thursday",
  "dstActive":false
}
```

## Get /api/Time/current/ip
### Parameters
This API requires one arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| ipAddress | string | IP address for obtaining time information | true |

### Response
This API returns JSON of current time information.
The sample of response is as follows.
```JSON
{
  "year":2023,
  "month":9,
  "day":14,
  "hour":16,
  "minute":42,
  "seconds":9,
  "milliSeconds":476,
  "dateTime":"2023-09-14T16:42:09.4764246",
  "date":"09/14/2023",
  "time":"16:42",
  "timeZone":"Asia/Tokyo",
  "dayOfWeek":"Thursday",
  "dstActive":false
}
```

## Get /api/TimeZone/AvailableTimeZones
### Parameters
This API requires no argument.

### Response
This API returns JSON of current time information.
The sample of response is as follows.
```JSON
[
  "Africa/Abidjan",
  "Africa/Accra",
  ...,
  "WET",
  "Zulu"
]
```

## Examples

```
input: Please tell me current time from timezone in Japan.

output: The current time in Japan (Asia/Tokyo timezone) is 19:14 (7:14 PM) on September 14, 2023, which is a Thursday. Daylight Saving Time is not in effect.

input: Please tell me all timezones in japan.

output: The timezone for Japan is 'Asia/Tokyo'.

input: 日本のタイムゾーンで今の時刻を教えて

output: 現在の日本（Asia/Tokyo）の時刻は、2023年9月14日の19時21分です。
```