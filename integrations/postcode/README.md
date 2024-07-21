# Integration for PostcodeAPI
This integration provides API for obtaining address from postcode.

## Get /postcodes/{new}.json
### Parameters
This API requires one arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| new | string | Postcode for which retrieve address | true |

### Response
This API returns JSON of address information.
The sample of response is as follows.

```JSON
{
  "jis": "13103",
  "old": "106",
  "new": "1066190",
  "prefecture_kana": "ホッカイドウ",
  "prefecture_roman": "Hokkaido",
  "city_kana": "港区",
  "city_roman": "Minatoku",
  "suburb_kana": "アカサカ",
  "suburb_roman": "Akasaka",
  "prefecture": "東京都",
  "city": "港区",
  "suburb": "string",
  "street_address": "string",
  "is_separated_suburb": 0,
  "is_koaza": 0,
  "is_chome": 0,
  "is_include_area": 0,
  "is_eparated_suburb": 0,
  "reason": 0,
  "status": 0,
  "postcode_type": 0,
  "office": "（株）　ＪＡ北海道情報センター",
  "office_kana": "(カブ) ジエイエイホツカイドウジヨウホウセンタ-",
  "office_roman": "(kabu) jieieihotsukaidoujiyouhousenta-",
  "handling_post_office": "string",
  "post_type": "string",
  "multiple_numbers": "string",
  "created_at": "2021-10-15T12:13:26.433+09:00",
  "updated_at": "2021-10-15T12:13:26.433+09:00"
}
```


## Examples

```
input: 郵便番号が 1350061 の住所を教えて

output: The address for the postal code 1350061 is in Tokyo, Koto Ward, Toyosu area.
```