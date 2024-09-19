# Integration for Real estate info API
This integration provides API for obtaining real estate price information.

## Get /ex-api/external/XIT001
### Parameters
This API requires at least two arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| year | string | Trade year | true | true |
| city | string | Local government code / City code in Japan of 5 digits | true | false |
| station | string | Station code in Japan of 6 digits | true | false |

### Response
This API returns JSON of real estate price information.
The sample of response is as follows.
```JSON
{
  "status": "OK",
  "data": [
    {
      "PriceCategory": "不動産取引価格情報",
      "Type": "宅地(土地と建物)",
      "Region": "商業地",
      "MunicipalityCode": "13102",
      "Prefecture": "東京都",
      "Municipality": "中央区",
      "DistrictName": "八重洲",
      "TradePrice": "36000000",
      "PricePerUnit": "",
      "FloorPlan": "",
      "Area": "40",
      "UnitPrice": "",
      "LandShape": "長方形",
      "Frontage": "4.1",
      "TotalFloorArea": "95",
      "BuildingYear": "1947年",
      "Structure": "木造",
      "Use": "住宅、店舗",
      "Purpose": "店舗",
      "Direction": "南西",
      "Classification": "私道",
      "Breadth": "3",
      "CityPlanning": "商業地域",
      "CoverageRatio": "80",
      "FloorAreaRatio": "800",
      "Period": "2022年第1四半期",
      "Renovation": "",
      "Remarks": "私道を含む取引"
    }
  ]
}
```


## Get /ex-api/external/XIT002
### Parameters
This API requires at least two arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| area | string | Prefecture code | true | true |

### Response
This API returns JSON of local government / city code list.
The sample of response is as follows.
```JSON
{
  "status": "OK",
  "data": [
    {
      "id": "13101",
      "name": "千代田区"
    },
    {
      "id": "13102",
      "name": "中央区"
    },
  ]
}
```


## Examples

```
input: 東京駅付近の2022年の不動産価格を教えて。東京駅の駅コードは003785。駅コードのみ指定

output: 2022年に東京駅周辺での不動産取引は以下の通りです：\n\n1. 八重洲の宅地(土地と建物)、取引価格：36000000円、面積：40平方メートル、建築年：1947年\n2. 八丁堀の中古マンション、成約価格：69000000円、間取り：１ＬＤＫ、面積：60平方メートル、建築年：2014年\n3. 八丁堀の中古マンション、成約価格：69000000円、間取り：２ＬＤＫ、面積：50平方メートル、建築年：2014年\n4. 日本橋の中古マンション、成約価格：52000000円、間取り：１ＬＤＫ、面積：40平方メートル、建築年：2004年\n5. 日本橋の宅地(土地と建物)、取引価格：3000000000円、面積：140平方メートル、建築年：1984年\n6. 新川の中古マンション、成約価格：130000000円、間取り：２ＬＤＫ、面積：80平方メートル、建築年：2017年\n7. 八丁堀の中古マンション、成約価格：56000000円、間取り：１ＬＤＫ、面積：45平方メートル、建築年：2011年\n8. 八丁堀の中古マンション、成約価格：71000000円、間取り：１ＬＤＫ、面積：50平方メートル、建築年：2014年\n\nこれらの情報は不動産情報ライブラリから取得されました。

input: 東京都の市区町村コードを取得して、八丈町の2022年第一四半期の不動産価格を教えて

output: The real estate prices in Hachijo town, Tokyo for the first quarter of 2022 vary depending on the type of property and its location. Here are some examples:\n\n1. A forest land in the district of Kashitate was sold for 240,000 yen with an area of 8888 square meters.\n2. A forest land in the district of Sueyoshi was sold for 520,000 yen with an area of 750 square meters.\n3. An agricultural land in the district of Ogago was sold for 1,000,000 yen with an area of 2300 square meters.\n4. A residential land with a building in the district of Ogago was sold for 3,000,000 yen with an area of 710 square meters and a total floor area of 60 square meters. The building was built in 1990.\n5. A residential land in the district of Ogago was sold for 2,100,000 yen with an area of 240 square meters.\n\nPlease note that these are just a few examples and the prices can vary greatly depending on various factors such as the size of the property, its location, and the type of property.

```
