# Integration for Ministry of Internal Affairs and Communications API
This integration provides API for obtaining radio station information.

## Get /musen/list
### Parameters

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| ST | string | 検索パターン | false | true |
| DA | string | 詳細情報 | true | true |
| SC | string | スタートカウント | true | true |
| DC | string | 出力件数 | true | true |
| OF | string | 出力形式 | true | true |
| OW | string | 無線局の種別 | true | true |
| MA | string | 呼出符号 | true | false |
| MC | string | 文字コード | true | false |

### Response
This API returns JSON of real estate price information.
The sample of response is as follows.
```JSON
{
  "musen": [
    {
      "detailInfo": {
        "radioSpec1": "1AM",
        "radioStationPurpose": "アマチュア業務用",
        "note": "",
        "permittedOperatingHours": "常　時",
        "address": "＊＊＊＊＊",
        "licenseDate": "2020-08-17",
        "broadcastMatter": "",
        "commMatter": "アマチュア業務に関する事項",
        "office": "",
        "validTerms": "2025-08-16まで",
        "commPartner": "アマチュア局",
        "startingLimit": "",
        "broadcastDistrict": "",
        "workPersonName": "",
        "identificationSignals": "JA1RL       ",
        "radioStationNumber": "",
        "radioStationCategory": "アマチュア局",
        "movementArea": "陸上、海上及び上空",
        "radioEuipmentLocation": "東京都豊島区",
        "licenseNumber": "＊＊＊＊＊",
        "name": "一般社団法人日本アマチュア無線連盟"
      },
      "listInfo": {
        "name": "一般社団法人日本アマチュア無線連盟（JA1RL） 法人番号5013305001797",
        "radioStationPurpose": "アマチュア業務用",
        "tdfkCd": "東京都豊島区",
        "no": "7",
        "licenseDate": "2020-08-17"
      }
    },
    {
      "detailInfo": {
        "radioSpec1": "1AF",
        "radioStationPurpose": "アマチュア業務用",
        "note": "",
        "permittedOperatingHours": "常　時",
        "address": "＊＊＊＊＊",
        "licenseDate": "2023-04-18",
        "broadcastMatter": "",
        "commMatter": "アマチュア業務に関する事項",
        "office": "",
        "validTerms": "2028-04-17まで",
        "commPartner": "アマチュア局",
        "startingLimit": "",
        "broadcastDistrict": "",
        "workPersonName": "",
        "identificationSignals": "JA1RL       ",
        "radioStationNumber": "",
        "radioStationCategory": "アマチュア局",
        "movementArea": "移動しない",
        "radioEuipmentLocation": "東京都豊島区",
        "licenseNumber": "＊＊＊＊＊",
        "name": "一般社団法人日本アマチュア無線連盟"
      },
      "listInfo": {
        "name": "一般社団法人日本アマチュア無線連盟（JA1RL） 法人番号5013305001797",
        "radioStationPurpose": "アマチュア業務用",
        "tdfkCd": "東京都豊島区",
        "no": "8",
        "licenseDate": "2023-04-18"
      }
    },

...省略...

  ],
  "musenInformation": {
    "totalCount": "14",
    "lastUpdateDate": "2024-06-28"
  }
}
```


## Examples

```
input: ST:検索パターン=1、DA:詳細情報=1、SC:スタートカウント=1、DC:取得件数=1、OF:出力形式=2、OW:無線局の種別=AT、MA:呼出符号=JA1RLの免許情報を教えて

output: The API returned a list of radio stations with the call sign \"JA1RL\". The specific information for the station \"JA1RL\" is as follows:\n\n- The station is operated by the Japan Amateur Radio League, Inc.\n- The station is licensed for amateur use.\n- The station is located in Toshima Ward, Tokyo.\n- The station's license was last issued on August 17, 2020, and is valid until August 16, 2025.\n- The station is permitted to operate at all times.\n- The station's call sign is \"JA1RL\".\n- The station is permitted to operate on land, at sea, and in the air.\n\nPlease note that some information has been redacted for privacy reasons. \n\nLet me know if you need more information.

```
