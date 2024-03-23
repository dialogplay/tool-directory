# Integration for WhatistodayAPI
This integration provides API for obtaining what is today.

## Get /anniv/{mmdd}
### Parameters
This API requires one arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| mmdd | string | What anniversary is it today. MMDD format date | true |

### Response
This API returns JSON of what is today information.
The sample of response is as follows.
```JSON
{
  "_count": 1,
  "_last": "string",
  "_items": [
    {
      "anniv1": "世界気象デー",
      "anniv2": "string",
      "anniv3": "string",
      "anniv4": "string",
      "anniv5": "string",
      "key": "83",
      "mmdd": "0323"
    }
  ]
}
```


## Get /anniv1_img/{mmdd}.png
### Parameters
This API requires one arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| mmdd | string | What anniversary is it today. MMDD format date | true |

### Response
This API returns png image of what is today information.


## Get /md/{mmdd}
### Parameters
This API requires one arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| mmdd | string | What kind of promotion is suitable today for fashion, life, gift and food. MMDD format date | true |

### Response
This API returns JSON of what is today information.
The sample of response is as follows.
```JSON
{
  "_count": 1,
  "_last": "string",
  "_items": [
    {
      "fashion1": "春物(プロパー)",
      "fashion2": "string",
      "food1": "冬メニュー",
      "food2": "string",
      "gift1": "バレンタイン",
      "gift2": "string",
      "key": "45",
      "life1": "新生活(入園・入学・フレッシャーズ)",
      "life2": "string",
      "mmdd": "0214"
    }
  ]
}
```


## Get /birthflower/{mmdd}
### Parameters
This API requires one arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| mmdd | string | Get today's birth flower. MMDD format date | true |

### Response
This API returns JSON of what is today information.
The sample of response is as follows.
```JSON
{
  "_count": 1,
  "_last": "string",
  "_items": [
    {
      "flower": "シュンラン",
      "key": "45",
      "lang": "素直なしぐさ",
      "mmdd": "0214"
    }
  ]
}
```


## Get /famousbirthday/{mmdd}
### Parameters
This API requires one arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| mmdd | string | Which great birthday is it today. MMDD format date | true |

### Response
This API returns JSON of what is today information.
The sample of response is as follows.
```JSON
{
  "_count": 1,
  "_last": "string",
  "_items": [
    {
      "key": "7qfmexz8qu8d",
      "lifespan": "1820-1893",
      "mmdd": "0214",
      "name": "清水次郎長",
      "profile": "侠客・博徒"
    }
  ]
}
```


## Examples

```
input: What is the day of 14 Feb.

output: February 14th is known for several events. It's Valentine's Day, Chocolate Day, Dried Sardines Day, Loincloth Day, and Necktie Day.

input: 2月14日は何の日か教えて

output: 2月14日はバレンタインデー、チョコレートの日、煮干の日、ふんどしの日、ネクタイの日として知られています。

[with timeAPI]

input: What anniversary is it today?

output: Today is the World Meteorological Day.

input: 今日は何の日？

output: 今日は「世界気象デー」です。

input: What is the birth flower today?

output: The birth flower for today, March 23rd, is スイートアリッサム (Sweet Alyssum) and it symbolizes '価値あるもの' which translates to 'valuable things' in English.

input: 今日の誕生花は？

output: 今日の誕生花はスイートアリッサムで、花言葉は「価値あるもの」です。
```