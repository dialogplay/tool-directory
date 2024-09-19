# Integration for Real estate info API
This integration provides API for obtaining real estate information.

## Get /ex-api/external/XKT004
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |
| administrativeAreaCode | string | Local government code / City code in Japan of 5 digits | true | false |

### Response
This API returns JSON of Elementary school district information.
The sample of response is as follows.
```JSON
{
  "type": "FeatureCollection",
  "name": "elementary_school_district",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::6668"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              139.75709348917007,
              35.74078896715368
            ],
            [
              139.75709348917007,
              35.737584265995665
            ],
            [
              139.74897176027298,
              35.737584265995665
            ],
            [
              139.7487035393715,
              35.73805888340728
            ],
            [
              139.74835753440857,
              35.73869460504902
            ],
            [
              139.74776476621628,
              35.739095194161564
            ],
            [
              139.74783718585968,
              35.73919316401823
            ],
            [
              139.74815368652344,
              35.73964817799465
            ],
            [
              139.74959939718246,
              35.74151174877245
            ],
            [
              139.7497335076332,
              35.74174251501576
            ],
            [
              139.74998027086258,
              35.7422998345053
            ],
            [
              139.75056767463684,
              35.74207560096103
            ],
            [
              139.75072592496872,
              35.742029883364765
            ],
            [
              139.75076615810394,
              35.74209954826287
            ],
            [
              139.75111484527588,
              35.742778777824526
            ],
            [
              139.75112825632095,
              35.74282449499073
            ],
            [
              139.751138985157,
              35.7428898051826
            ],
            [
              139.75185245275497,
              35.74330996613584
            ],
            [
              139.75195169448853,
              35.74337745292166
            ],
            [
              139.75205093622208,
              35.743475417508904
            ],
            [
              139.75215554237366,
              35.74359079786818
            ],
            [
              139.7522333264351,
              35.7435341962034
            ],
            [
              139.75235402584076,
              35.743484125466395
            ],
            [
              139.75244253873825,
              35.74342752372576
            ],
            [
              139.75303530693054,
              35.743157576409104
            ],
            [
              139.75368976593018,
              35.74288109716011
            ],
            [
              139.75420206785202,
              35.742495766211434
            ],
            [
              139.75432813167572,
              35.74238256128449
            ],
            [
              139.75446492433548,
              35.74216485904945
            ],
            [
              139.7545239329338,
              35.742103902316956
            ],
            [
              139.7545748949051,
              35.742090840153935
            ],
            [
              139.75475996732712,
              35.74218227525016
            ],
            [
              139.7548645734787,
              35.7421583279732
            ],
            [
              139.75550025701523,
              35.741779524634055
            ],
            [
              139.75581407546997,
              35.74160318453376
            ],
            [
              139.75613325834274,
              35.741439906314895
            ],
            [
              139.75678771734238,
              35.741063276612905
            ],
            [
              139.75697547197342,
              35.74090217434663
            ],
            [
              139.75709348917007,
              35.74078896715368
            ]
          ]
        ]
      },
      "properties": {
        "_id": "YUeflpABHEII8kGRWNDY",
        "_index": "bs003_elementary_school_district_202407091729",
        "A27_003": "B113211700337",
        "A27_004_ja": "田端小学校",
        "A27_001": "13117",
        "A27_002": "北区立",
        "A27_005": "北区田端5-4-1"
      }
    }
  ]
}
```


## Get /ex-api/external/XKT005
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |
| administrativeAreaCode | string | Local government code / City code in Japan of 5 digits | true | false |

### Response
This API returns JSON of Junior high school district information.
The sample of response is as follows.
```JSON
{
  "type": "FeatureCollection",
  "name": "junior_high_school_district",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::6668"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              139.75709348917007,
              35.744759830945384
            ],
            [
              139.75709348917007,
              35.737584265995665
            ],
            [
              139.74897176027298,
              35.737584265995665
            ],
            [
              139.7487035393715,
              35.73805888340728
            ],
            [
              139.74835753440857,
              35.73869460504902
            ],
            [
              139.74776476621628,
              35.739095194161564
            ],
            [
              139.74783718585968,
              35.73919316401823
            ],
            [
              139.74815368652344,
              35.73964817799465
            ],
            [
              139.74959939718246,
              35.74151174877245
            ],
            [
              139.7497335076332,
              35.74174251501576
            ],
            [
              139.74998027086258,
              35.7422998345053
            ],
            [
              139.75056767463684,
              35.74207560096103
            ],
            [
              139.75072592496872,
              35.742029883364765
            ],
            [
              139.75076615810394,
              35.74209954826287
            ],
            [
              139.75111484527588,
              35.742778777824526
            ],
            [
              139.75112825632095,
              35.74282449499073
            ],
            [
              139.751138985157,
              35.7428898051826
            ],
            [
              139.75185245275497,
              35.74330996613584
            ],
            [
              139.75195169448853,
              35.74337745292166
            ],
            [
              139.75205093622208,
              35.743475417508904
            ],
            [
              139.75215554237366,
              35.74359079786818
            ],
            [
              139.7522333264351,
              35.7435341962034
            ],
            [
              139.75235402584076,
              35.743484125466395
            ],
            [
              139.75244253873825,
              35.74342752372576
            ],
            [
              139.75303530693054,
              35.743157576409104
            ],
            [
              139.75368976593018,
              35.74288109716011
            ],
            [
              139.75420206785202,
              35.742495766211434
            ],
            [
              139.75432813167572,
              35.74238256128449
            ],
            [
              139.75446492433548,
              35.74216485904945
            ],
            [
              139.7545239329338,
              35.742103902316956
            ],
            [
              139.7545748949051,
              35.742090840153935
            ],
            [
              139.75475996732712,
              35.74218227525016
            ],
            [
              139.7548645734787,
              35.7421583279732
            ],
            [
              139.75550025701523,
              35.741779524634055
            ],
            [
              139.75584894418716,
              35.742156150947665
            ],
            [
              139.75604206323624,
              35.742227992758885
            ],
            [
              139.75611180067062,
              35.74223887787615
            ],
            [
              139.75617349147797,
              35.742397800418644
            ],
            [
              139.75635051727295,
              35.74296164633175
            ],
            [
              139.7563934326172,
              35.743390514873596
            ],
            [
              139.75650072097778,
              35.74374318676567
            ],
            [
              139.75658923387527,
              35.743991362345724
            ],
            [
              139.7566482424736,
              35.74421123655539
            ],
            [
              139.75675284862518,
              35.74444634889974
            ],
            [
              139.7568091750145,
              35.74461397486935
            ],
            [
              139.7568815946579,
              35.74473588444377
            ],
            [
              139.75709348917007,
              35.744759830945384
            ]
          ]
        ]
      },
      "properties": {
        "_id": "ukrplpABHEII8kGR_Sph",
        "_index": "bs004_junior_high_school_district_202407091850",
        "A32_004_ja": "田端中学校",
        "A32_001": "13117",
        "A32_002": "北区",
        "A32_003": "C113211700102",
        "A32_005": "北区田端4-17-1"
      }
    }
  ]
}
```


## Get /ex-api/external/XKT007
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |

### Response
This API returns JSON of preschool gis information.
The sample of response is as follows.
```JSON
5{
  "type": "FeatureCollection",
  "name": "preschool",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::6668"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.74917829036713,
          35.74073236349683
        ]
      },
      "properties": {
        "_id": "ayT6lpABk4JyLPT2qejd",
        "_index": "bs006_preschool_202407091911",
        "schoolClassCode": 16011,
        "welfareFacilityClassCode": "",
        "welfareFacilityMiddleClassCode": "",
        "preSchoolName_ja": "聖学院幼稚園",
        "schoolClassCode_name_ja": "幼稚園",
        "closeSchoolCode": 0,
        "location_ja": "東京都北区中里3-13-2",
        "welfareFacilityMinorClassCode": "",
        "administratorCode": 4,
        "administrativeAreaCode": "13117",
        "schoolCode": "A113311700033"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.75406259298325,
          35.744463764601335
        ]
      },
      "properties": {
        "_id": "hCT6lpABk4JyLPT2qejd",
        "_index": "bs006_preschool_202407091911",
        "schoolClassCode": 16011,
        "welfareFacilityClassCode": "",
        "welfareFacilityMiddleClassCode": "",
        "preSchoolName_ja": "上中里幼稚園",
        "schoolClassCode_name_ja": "幼稚園",
        "closeSchoolCode": 0,
        "location_ja": "東京都北区上中里2-2-3",
        "welfareFacilityMinorClassCode": "",
        "administratorCode": 4,
        "administrativeAreaCode": "13117",
        "schoolCode": "A113311700284"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.7561600804329,
          35.73919316401823
        ]
      },
      "properties": {
        "_id": "DyX6lpABk4JyLPT2ujv9",
        "_index": "bs006_preschool_202407091911",
        "welfareFacilityClassCode": "05",
        "welfareFacilityMiddleClassCode": "0504",
        "preSchoolName_ja": "ＭＩＷＡたばた保育園",
        "location_ja": "田端5-11-8",
        "welfareFacilityMinorClassCode": "050401",
        "administratorCode": 5,
        "administrativeAreaCode": "13117",
        "schoolCode": ""
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.74879205226898,
          35.744202528677434
        ]
      },
      "properties": {
        "_id": "ECX6lpABk4JyLPT2ujv9",
        "_index": "bs006_preschool_202407091911",
        "welfareFacilityClassCode": "05",
        "welfareFacilityMiddleClassCode": "0504",
        "preSchoolName_ja": "まなびの森保育園上中里",
        "location_ja": "上中里1-26-12",
        "welfareFacilityMinorClassCode": "050401",
        "administratorCode": 4,
        "administrativeAreaCode": "13117",
        "schoolCode": ""
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.7531560063362,
          35.740767196521205
        ]
      },
      "properties": {
        "_id": "bCX6lpABk4JyLPT2vEJw",
        "_index": "bs006_preschool_202407091911",
        "welfareFacilityClassCode": "05",
        "welfareFacilityMiddleClassCode": "0504",
        "preSchoolName_ja": "中里保育園",
        "location_ja": "中里3-11-18",
        "welfareFacilityMinorClassCode": "050401",
        "administratorCode": 3,
        "administrativeAreaCode": "13117",
        "schoolCode": ""
      }
    }
  ]
}
```


## Get /ex-api/external/XKT010
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |

### Response
This API returns JSON of medical institution gis information.
The sample of response is as follows.
```JSON
{
  "type": "FeatureCollection",
  "name": "medical_institution",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::6668"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.7482904791832,
          35.73876427286555
        ]
      },
      "properties": {
        "_id": "-Ls0B44B_RVTRAlpSrsG",
        "_index": "bs007_medical_institution_202403040203",
        "P04_001": 2,
        "P04_010": 9,
        "P04_006": "",
        "P04_005": "",
        "P04_004": "内科　胃腸科　外科　リハビリテーション科　こう門科",
        "P04_009": 9,
        "P04_008": 0,
        "P04_007": 9,
        "P04_001_name_ja": "診療所",
        "P04_003_ja": "豊島区駒込二丁目１２番１１号　古川ビル　２階",
        "P04_002_ja": "医療法人社団　至仁望信会　高橋クリニック",
        "medical_subject_ja": "内科　胃腸科　外科　リハビリテーション科　こう門科"
      }
    }
  ]
}
```


## Get /ex-api/external/XKT011
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |
| administrativeAreaCode | string | Local government code / City code in Japan of 5 digits | true | false |
| welfareFacilityClassCode | string | Facility class code of 2 digits | true | false |
| welfareFacilityMiddleClassCode | string | Facility middle class code of 4 digits | true | false |
| welfareFacilityMinorClassCode | string | Facility minor class code of 6 digits | true | false |

### Response
This API returns JSON of welfare facility information.
The sample of response is as follows.

```JSON
{
  "type": "FeatureCollection",
  "name": "welfare_facility",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::6668"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.74752873182297,
          35.74278530884989
        ]
      },
      "properties": {
        "_id": "ISb9lpABk4JyLPT22v_C",
        "_index": "bs008_welfare_facility_202407091914",
        "P14_006_name_ja": "障害者サービス施設",
        "P14_005_name_ja": "その他の社会福祉施設等",
        "P14_008_ja": "東京都北区立たばた福祉作業所",
        "P14_004_ja": "西ヶ原1-19-12",
        "P14_005": "99",
        "P14_006": "9911",
        "P14_007": "991100",
        "P14_009": 3,
        "P14_010": 1,
        "P14_001": "東京都",
        "P14_002": "北区",
        "P14_003": "13117"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.7496798634529,
          35.738592280332995
        ]
      },
      "properties": {
        "_id": "pSf9lpABk4JyLPT23QkS",
        "_index": "bs008_welfare_facility_202407091914",
        "P14_006_name_ja": "障害者サービス施設",
        "P14_005_name_ja": "その他の社会福祉施設等",
        "P14_008_ja": "有限会社春光",
        "P14_004_ja": "中里2-9-6　宮澤ビル",
        "P14_005": "99",
        "P14_006": "9911",
        "P14_007": "991100",
        "P14_009": 4,
        "P14_010": 1,
        "P14_001": "東京都",
        "P14_002": "北区",
        "P14_003": "13117"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.75051403045654,
          35.739029880856805
        ]
      },
      "properties": {
        "_id": "xCf9lpABk4JyLPT23QkS",
        "_index": "bs008_welfare_facility_202407091914",
        "P14_006_name_ja": "障害者サービス施設",
        "P14_005_name_ja": "その他の社会福祉施設等",
        "P14_008_ja": "ニチイケアセンター駒込",
        "P14_004_ja": "中里2-26-4　メゾンホシノ1階",
        "P14_005": "99",
        "P14_006": "9911",
        "P14_007": "991100",
        "P14_009": 4,
        "P14_010": 1,
        "P14_001": "東京都",
        "P14_002": "北区",
        "P14_003": "13117"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.75526958703995,
          35.738459475718216
        ]
      },
      "properties": {
        "_id": "lSf9lpABk4JyLPT23Q_f",
        "_index": "bs008_welfare_facility_202407091914",
        "P14_006_name_ja": "児童福祉サービス施設",
        "P14_005_name_ja": "その他の社会福祉施設等",
        "P14_008_ja": "たばこま子ども発達ラボ",
        "P14_004_ja": "田端4-19-5　第二アサカビル101",
        "P14_005": "99",
        "P14_006": "9912",
        "P14_007": "991200",
        "P14_009": 4,
        "P14_010": 2,
        "P14_001": "東京都",
        "P14_002": "北区",
        "P14_003": "13117"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.74803298711777,
          35.73959375062242
        ]
      },
      "properties": {
        "_id": "Rif9lpABk4JyLPT23Q7f",
        "_index": "bs008_welfare_facility_202407091914",
        "P14_006_name_ja": "障害者サービス施設",
        "P14_005_name_ja": "その他の社会福祉施設等",
        "P14_008_ja": "ワーク・イン・あすか",
        "P14_004_ja": "西ヶ原1-1-13　ヴェルテN101",
        "P14_005": "99",
        "P14_006": "9911",
        "P14_007": "991100",
        "P14_009": 5,
        "P14_010": 1,
        "P14_001": "東京都",
        "P14_002": "北区",
        "P14_003": "13117"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.7550469636917,
          35.74421776746321
        ]
      },
      "properties": {
        "_id": "VSf9lpABk4JyLPT24SDs",
        "_index": "bs008_welfare_facility_202407091914",
        "P14_006_name_ja": "介護保険等の施設",
        "P14_005_name_ja": "その他の社会福祉施設等",
        "P14_008_ja": "北区立特別養護老人ホーム上中里つつじ荘",
        "P14_004_ja": "上中里2-45-2",
        "P14_005": "99",
        "P14_006": "9910",
        "P14_007": "991001",
        "P14_009": 5,
        "P14_010": 1,
        "P14_001": "東京都",
        "P14_002": "北区",
        "P14_003": "13117"
      }
    }
  ]
}
```


## Get /ex-api/external/XKT013
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |

### Response
This API returns JSON of estimated future population information.
The sample of response is as follows.

```JSON
{
  "type": "FeatureCollection",
  "name": "estimated_future_population",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::6668"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              139.74608033895493,
              35.737584265995665
            ],
            [
              139.74608033895493,
              35.741666318688644
            ],
            [
              139.74999904632568,
              35.741666318688644
            ],
            [
              139.74999904632568,
              35.737584265995665
            ],
            [
              139.74608033895493,
              35.737584265995665
            ]
          ]
        ]
      },
      "properties": {
        "_id": "trGUeZEBk4JyLPT2wONa",
        "_index": "bs012_estimated_future_population_202408221603",
        "PT12_2035": 451.3447,
        "PTB_2020": 3903.8089,
        "RTB_2020": 67.9859,
        "PT10_2020": 456.7903,
        "PT10_2025": 477.7529,
        "PT12_2030": 438.9367,
        "RTD_2040": 14.8472,
        "PT14_2050": 354.9614,
        "PT9_2035": 340.9099,
        "HITOKU2030": "",
        "PT9_2030": 425.0438,
        "PT7_2025": 389.9726,
        "PTD_2045": 827.9165,
        "RTD_2045": 15.482,
        "PTD_2040": 806.361,
        "HITOKU2035": "",
        "PT7_2020": 509.4182,
        "PT12_2025": 375.7063,
        "RTB_2035": 66.2342,
        "HITOKU2050": "",
        "PT10_2030": 432.5234,
        "PTB_2030": 3722.3569,
        "RTB_2030": 66.6346,
        "PT0_2050": 5249.2914,
        "PT10_2035": 413.5248,
        "PT12_2020": 346.8376,
        "PT7_2030": 373.0907,
        "RTD_2050": 17.0841,
        "PT14_2045": 396.6736,
        "PT9_2025": 443.707,
        "PT14_2040": 387.1783,
        "PT9_2020": 486.5945,
        "PTB_2025": 3814.6398,
        "PT7_2035": 403.9155,
        "HITOKU2040": "",
        "PTD_2050": 896.7934,
        "RTB_2025": 67.1387,
        "HITOKU2045": "",
        "PT5_2035": 315.0489,
        "RTB_2045": 62.9517,
        "RTB_2040": 64.8125,
        "PT5_2030": 284.5875,
        "PT10_2040": 333.6256,
        "PT10_2045": 329.3094,
        "PT7_2040": 323.3149,
        "PT14_2030": 305.1742,
        "PT16_2045": 276.1929,
        "PT14_2035": 332.5091,
        "PT7_2045": 352.6015,
        "PT16_2040": 251.8478,
        "PTD_2020": 736.7611,
        "PT16_2050": 321.1831,
        "PT5_2025": 360.6157,
        "PT10_2050": 352.5945,
        "PTD_2025": 838.1324,
        "RTB_2050": 61.7155,
        "PT5_2020": 342.211,
        "PT14_2020": 313.8358,
        "PT17_2020": 230.0783,
        "PT7_2050": 414.633,
        "PT17_2025": 221.255,
        "HITOKU2020": "",
        "PTD_2035": 814.8507,
        "HITOKU2025": "",
        "PT14_2025": 291.1403,
        "PT4_2050": 161.5896,
        "PTD_2030": 836.2886,
        "PT2_2030": 148.8266,
        "PT3_2040": 138.3549,
        "PT3_2045": 134.5251,
        "PT16_2025": 329.2195,
        "PT4_2045": 166.4887,
        "PT16_2020": 267.7268,
        "PT2_2035": 139.538,
        "PT4_2040": 178.8711,
        "PT15_2025": 283.8089,
        "PT2_2040": 135.8277,
        "PT15_2020": 369.7628,
        "PT3_2050": 129.3121,
        "RTA_2050": 7.498,
        "PT16_2035": 239.0975,
        "PT4_2035": 194.6262,
        "PT2_2045": 130.5591,
        "PT4_2030": 164.5353,
        "PT16_2030": 253.4048,
        "PT2_2050": 129.192,
        "PT4_2025": 140.4231,
        "RTA_2035": 7.846,
        "PT15_2030": 265.4735,
        "PT15_2035": 278.6332,
        "PT3_2020": 110.8967,
        "PT8_2050": 328.7126,
        "RTA_2040": 7.6058,
        "PT3_2025": 134.9306,
        "RTA_2045": 7.5264,
        "PT4_2020": 169.375,
        "PT9_2050": 283.7866,
        "PT15_2040": 304.4323,
        "PT3_2030": 159.827,
        "RTA_2025": 7.9906,
        "PTE_2050": 575.6103,
        "PT15_2045": 354.1255,
        "PT3_2035": 147.6724,
        "RTA_2030": 8.1795,
        "PT9_2045": 359.1403,
        "PT9_2040": 335.3399,
        "PT8_2035": 355.3286,
        "PTE_2040": 554.5132,
        "PT13_2040": 428.6636,
        "PTN_2025": 5681.7263,
        "PTN_2020": 5742.0858,
        "PTE_2045": 551.7237,
        "RTE_2045": 10.3172,
        "PT13_2045": 383.6372,
        "PT6_2020": 416.893,
        "PT15_2050": 364.3188,
        "RTE_2040": 10.2101,
        "PTC_2030": 1406.9363,
        "RTC_2030": 25.1858,
        "RTC_2035": 25.9198,
        "PT8_2030": 363.7622,
        "PT6_2025": 389.003,
        "PT11_2030": 465.001,
        "PTC_2025": 1413.0817,
        "RTA_2020": 7.2781,
        "PTA_2020": 417.9173,
        "MESH_ID": 533945894,
        "PT11_2035": 418.7307,
        "PTN_2035": 5501.5494,
        "RTE_2035": 10.4653,
        "PT8_2045": 301.3105,
        "PTE_2030": 582.8839,
        "PT13_2030": 358.7633,
        "PTE_2035": 575.7532,
        "PTN_2030": 5586.2189,
        "SHICODE": 13116,
        "PT13_2035": 418.3442,
        "PTC_2040": 1497.9715,
        "RTC_2040": 27.5816,
        "RTE_2030": 10.4343,
        "PT8_2040": 382.0142,
        "PTC_2045": 1578.7157,
        "RTC_2045": 29.5219,
        "PTC_2035": 1425.9929,
        "PT11_2040": 399.9817,
        "PT11_2045": 323.9765,
        "PTE_2020": 469.0343,
        "PTA_2035": 431.649,
        "PTE_2025": 508.913,
        "PT1_2045": 137.4003,
        "PTC_2050": 1616.0736,
        "PT1_2040": 138.8937,
        "PTA_2040": 413.0763,
        "PT2_2020": 135.9965,
        "PT19_2050": 170.2391,
        "PT13_2050": 366.787,
        "PTN_2015": 5818.0744,
        "PTA_2025": 454.0048,
        "PT8_2025": 458.4552,
        "RTC_2020": 24.736,
        "RTE_2050": 10.9655,
        "PT8_2020": 477.2146,
        "RTC_2025": 24.8706,
        "PT11_2020": 383.2955,
        "PT1_2050": 135.088,
        "PT11_2025": 448.7813,
        "PTA_2030": 456.9258,
        "PT2_2025": 160.9774,
        "PT19_2040": 192.9826,
        "PT1_2025": 158.0968,
        "PT0_2020": 5742.0858,
        "PT5_2050": 311.5266,
        "PT18_2035": 205.5853,
        "PT0_2025": 5681.7263,
        "PT17_2030": 273.3272,
        "PT17_2035": 211.1404,
        "PT18_2030": 164.9356,
        "PT1_2020": 171.0241,
        "PT19_2045": 180.5917,
        "PT5_2045": 336.4839,
        "PT19_2030": 144.6211,
        "PT5_2040": 370.6353,
        "PT6_2050": 386.893,
        "PTA_2045": 402.4844,
        "PT18_2020": 153.2908,
        "PT1_2035": 144.4385,
        "PT17_2040": 202.1354,
        "PT18_2025": 169.4121,
        "PT1_2030": 148.2722,
        "PT17_2045": 214.8434,
        "PTA_2050": 393.5922,
        "PT19_2035": 159.0274,
        "PTB_2040": 3519.9998,
        "PTN_2045": 5347.6154,
        "RTE_2025": 8.957,
        "PT19_2020": 85.6652,
        "RTE_2020": 8.1684,
        "PT13_2020": 315.1792,
        "RTC_2050": 30.7865,
        "PT6_2040": 362.5893,
        "PT12_2050": 313.2806,
        "PT0_2040": 5431.0476,
        "PT13_2025": 330.2226,
        "PT17_2050": 237.435,
        "PT6_2045": 426.755,
        "PT11_2050": 319.8221,
        "PT18_2050": 167.9362,
        "PT0_2045": 5347.6154,
        "PT19_2025": 118.2459,
        "RTD_2025": 14.7514,
        "PTB_2035": 3643.9075,
        "PTN_2040": 5431.0476,
        "RTD_2020": 12.8309,
        "PTB_2050": 3239.6256,
        "PT12_2045": 386.7122,
        "PT6_2030": 416.113,
        "PT0_2030": 5586.2189,
        "PT18_2045": 156.2886,
        "PT6_2035": 332.134,
        "PTC_2020": 1420.3596,
        "PT12_2040": 404.9642,
        "PT18_2040": 159.3952,
        "PT0_2035": 5501.5494,
        "RTD_2035": 14.8113,
        "PTB_2045": 3366.4152,
        "PTN_2050": 5249.2914,
        "RTD_2030": 14.9706
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              139.74608033895493,
              35.741666318688644
            ],
            [
              139.74608033895493,
              35.74583306221193
            ],
            [
              139.74999904632568,
              35.74583306221193
            ],
            [
              139.74999904632568,
              35.741666318688644
            ],
            [
              139.74608033895493,
              35.741666318688644
            ]
          ]
        ]
      },
      "properties": {
        "_id": "3LGUeZEBk4JyLPT2wONa",
        "_index": "bs012_estimated_future_population_202408221603",
        "PT12_2035": 296.7425,
        "PTB_2020": 2583.7063,
        "RTB_2020": 62.5781,
        "PT10_2020": 356.8811,
        "PT10_2025": 311.277,
        "PT12_2030": 343.0422,
        "RTD_2040": 12.7487,
        "PT14_2050": 221.4574,
        "PT9_2035": 224.9967,
        "HITOKU2030": "",
        "PT9_2030": 230.9265,
        "PT7_2025": 249.2026,
        "PTD_2045": 556.8664,
        "RTD_2045": 13.5394,
        "PTD_2040": 530.1229,
        "HITOKU2035": "",
        "PT7_2020": 255.3988,
        "PT12_2025": 279.57,
        "RTB_2035": 66.1934,
        "HITOKU2050": "",
        "PT10_2030": 260.7974,
        "PTB_2030": 2768.8867,
        "RTB_2030": 66.4144,
        "PT0_2050": 4062.6185,
        "PT10_2035": 225.0599,
        "PT12_2020": 231.5462,
        "PT7_2030": 306.7997,
        "RTD_2050": 15.6131,
        "PT14_2045": 265.2512,
        "PT9_2025": 266.4668,
        "PT14_2040": 307.3427,
        "PT9_2020": 316.2036,
        "PTB_2025": 2672.7904,
        "PT7_2035": 365.3876,
        "HITOKU2040": "",
        "PTD_2050": 634.2997,
        "RTB_2025": 64.4219,
        "HITOKU2045": "",
        "PT5_2035": 287.1787,
        "RTB_2045": 62.5037,
        "RTB_2040": 63.9341,
        "PT5_2030": 264.7662,
        "PT10_2040": 219.1227,
        "PT10_2045": 267.7483,
        "PT7_2040": 339.145,
        "PT14_2030": 206.1975,
        "PT16_2045": 206.8274,
        "PT14_2035": 250.3033,
        "PT7_2045": 354.2648,
        "PT16_2040": 169.8663,
        "PTD_2020": 608.1343,
        "PT16_2050": 255.9081,
        "PT5_2025": 279.8525,
        "PT10_2050": 317.8392,
        "PTD_2025": 611.8064,
        "RTB_2050": 62.2392,
        "PT5_2020": 234.7454,
        "PT14_2020": 230.4956,
        "PT17_2020": 185.5688,
        "PT7_2050": 278.5288,
        "PT17_2025": 182.7295,
        "HITOKU2020": "",
        "PTD_2035": 547.1848,
        "HITOKU2025": "",
        "PT14_2025": 194.4133,
        "PT4_2050": 149.3502,
        "PTD_2030": 591.276,
        "PT2_2030": 135.6493,
        "PT3_2040": 136.3517,
        "PT3_2045": 137.7432,
        "PT16_2025": 203.8246,
        "PT4_2045": 148.1039,
        "PT16_2020": 224.8699,
        "PT2_2035": 139.1072,
        "PT4_2040": 145.7065,
        "PT15_2025": 210.653,
        "PT2_2040": 140.7366,
        "PT15_2020": 232.3776,
        "PT3_2050": 139.6886,
        "RTA_2050": 10.6265,
        "PT16_2035": 158.1526,
        "PT4_2035": 153.6811,
        "PT2_2045": 142.7324,
        "PT4_2030": 191.1981,
        "PT16_2030": 185.4739,
        "PT2_2050": 143.5785,
        "PT4_2025": 168.1894,
        "RTA_2035": 10.1413,
        "PT15_2030": 178.5554,
        "PT15_2035": 190.5213,
        "PT3_2020": 148.4703,
        "PT8_2050": 332.8498,
        "RTA_2040": 10.3518,
        "PT3_2025": 172.8003,
        "RTA_2045": 10.5694,
        "PT4_2020": 172.6485,
        "PT9_2050": 303.0883,
        "PT15_2040": 231.7885,
        "PT3_2030": 139.6263,
        "RTA_2025": 11.0685,
        "PTE_2050": 378.3916,
        "PT15_2045": 285.3661,
        "PT3_2035": 133.2548,
        "RTA_2030": 10.1746,
        "PT9_2045": 326.8217,
        "PT9_2040": 275.2664,
        "PT8_2035": 289.2536,
        "PTE_2040": 360.2566,
        "PT13_2040": 282.1797,
        "PTN_2025": 4148.8832,
        "PTN_2020": 4128.7729,
        "PTE_2045": 350.039,
        "RTE_2045": 8.5107,
        "PT13_2045": 234.8452,
        "PT6_2020": 245.0083,
        "PT15_2050": 246.6054,
        "RTE_2040": 8.6637,
        "PTC_2030": 976.0289,
        "RTC_2030": 23.411,
        "RTC_2035": 23.6653,
        "PT8_2030": 236.0895,
        "PT6_2025": 305.4645,
        "PT11_2030": 304.5279,
        "PTC_2025": 1016.8727,
        "RTA_2020": 11.4818,
        "PTA_2020": 474.0591,
        "MESH_ID": 533945992,
        "PT11_2035": 254.3098,
        "PTN_2035": 4174.9307,
        "RTE_2035": 9.3183,
        "PT8_2045": 318.7271,
        "PTE_2030": 405.8021,
        "PT13_2030": 266.6485,
        "PTE_2035": 389.0322,
        "PTN_2030": 4169.1077,
        "SHICODE": 13117,
        "PT13_2035": 326.8186,
        "PTC_2040": 1069.2541,
        "RTC_2040": 25.7141,
        "RTE_2030": 9.7335,
        "PT8_2040": 344.0953,
        "PTC_2045": 1107.4836,
        "RTC_2045": 26.9269,
        "PTC_2035": 988.0094,
        "PT11_2040": 218.6993,
        "PT11_2045": 212.8832,
        "PTE_2020": 383.2645,
        "PTA_2035": 423.392,
        "PTE_2025": 407.9818,
        "PT1_2045": 154.2358,
        "PTC_2050": 1102.3625,
        "PT1_2040": 153.3637,
        "PTA_2040": 430.452,
        "PT2_2020": 175.0966,
        "PT19_2050": 99.5112,
        "PT13_2050": 201.686,
        "PTN_2015": 4131.5165,
        "PTA_2025": 459.2201,
        "PT8_2025": 242.0088,
        "RTC_2020": 25.9401,
        "RTE_2050": 9.314,
        "PT8_2020": 276.9798,
        "RTC_2025": 24.5096,
        "PT11_2020": 285.1706,
        "PT1_2050": 148.4488,
        "PT11_2025": 350.7007,
        "PTA_2030": 424.1921,
        "PT2_2025": 141.8113,
        "PT19_2040": 118.9574,
        "PT1_2025": 144.6085,
        "PT0_2020": 4128.7729,
        "PT5_2050": 214.6131,
        "PT18_2035": 120.3749,
        "PT0_2025": 4148.8832,
        "PT17_2030": 165.6872,
        "PT17_2035": 151.5705,
        "PT18_2030": 132.9306,
        "PT1_2020": 150.4922,
        "PT19_2045": 111.4203,
        "PT5_2045": 212.2872,
        "PT19_2030": 107.1843,
        "PT5_2040": 227.5335,
        "PT6_2050": 263.6035,
        "PTA_2045": 434.7113,
        "PT18_2020": 113.6177,
        "PT1_2035": 151.0301,
        "PT17_2040": 130.4856,
        "PT18_2025": 132.6405,
        "PT1_2030": 148.9164,
        "PT17_2045": 141.4844,
        "PTA_2050": 431.7159,
        "PT19_2035": 117.0868,
        "PTB_2040": 2658.5325,
        "PTN_2045": 4112.9301,
        "RTE_2025": 9.8335,
        "PT19_2020": 84.0779,
        "RTE_2020": 9.2828,
        "PT13_2020": 209.1239,
        "RTC_2050": 27.1343,
        "PT6_2040": 359.6415,
        "PT12_2050": 206.5798,
        "PT0_2040": 4158.2386,
        "PT13_2025": 220.058,
        "PT17_2050": 172.164,
        "PT6_2045": 282.9258,
        "PT11_2050": 260.4015,
        "PT18_2050": 106.7164,
        "PT0_2045": 4112.9301,
        "PT19_2025": 92.6118,
        "RTD_2025": 14.7463,
        "PTB_2035": 2763.5293,
        "PTN_2040": 4158.2386,
        "RTD_2020": 14.7292,
        "PTB_2050": 2528.5401,
        "PT12_2045": 212.128,
        "PT6_2030": 364.0906,
        "PT0_2030": 4169.1077,
        "PT18_2045": 97.1342,
        "PT6_2035": 340.1008,
        "PTC_2020": 1071.0075,
        "PT12_2040": 247.1427,
        "PT18_2040": 110.8137,
        "PT0_2035": 4174.9307,
        "RTD_2035": 13.1064,
        "PTB_2045": 2570.7352,
        "PTN_2050": 4062.6185,
        "RTD_2030": 14.1823
      }
    }
  ]
}
```


## Get /ex-api/external/XKT014
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |

### Response
This API returns JSON of fire protection area information.
The sample of response is as follows.

```JSON
{
  "type": "FeatureCollection",
  "name": "fire_protection_area",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::6668"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "MultiPolygon",
        "coordinates": [
          [
            [
              [
                139.74608033895493,
                35.738864420244994
              ],
              [
                139.74608033895493,
                35.73950013545516
              ],
              [
                139.74623054265976,
                35.73986806419963
              ],
              [
                139.74610179662704,
                35.74019680382891
              ],
              [
                139.74619835615158,
                35.74027300156247
              ],
              [
                139.7464182972908,
                35.740333959696784
              ],
              [
                139.74660873413086,
                35.740808560717824
              ],
              [
                139.74679112434387,
                35.74128533595912
              ],
              [
                139.74683672189713,
                35.74142902108839
              ],
              [
                139.7468662261963,
                35.741574882999814
              ],
              [
                139.74687427282333,
                35.74172074464403
              ],
              [
                139.74686354398727,
                35.74186878305444
              ],
              [
                139.74684208631516,
                35.742018998218924
              ],
              [
                139.74709957838058,
                35.741942802156416
              ],
              [
                139.7470647096634,
                35.74186442898747
              ],
              [
                139.747354388237,
                35.74179258684816
              ],
              [
                139.7473356127739,
                35.74195804137476
              ],
              [
                139.74714517593384,
                35.74313362942553
              ],
              [
                139.74669456481934,
                35.74325118727582
              ],
              [
                139.74648267030716,
                35.743386160889855
              ],
              [
                139.7461822628975,
                35.743081381436326
              ],
              [
                139.74608033895493,
                35.743146691417465
              ],
              [
                139.74608033895493,
                35.7441350425911
              ],
              [
                139.74658459424973,
                35.743819381105
              ],
              [
                139.7469761967659,
                35.74357120498877
              ],
              [
                139.74704056978226,
                35.743545081142074
              ],
              [
                139.74779158830643,
                35.74335350600421
              ],
              [
                139.74775403738022,
                35.74307920443603
              ],
              [
                139.74778354167938,
                35.74286368111228
              ],
              [
                139.7476789355278,
                35.74278966286647
              ],
              [
                139.74770575761795,
                35.74267428134607
              ],
              [
                139.747896194458,
                35.741500863555785
              ],
              [
                139.7476789355278,
                35.74098272552054
              ],
              [
                139.74752604961395,
                35.740573437629806
              ],
              [
                139.74724173545837,
                35.73986153293497
              ],
              [
                139.7478425502777,
                35.73951972933648
              ],
              [
                139.74795252084732,
                35.73945006218099
              ],
              [
                139.74851042032242,
                35.73906253751588
              ],
              [
                139.74922120571136,
                35.73895803615969
              ],
              [
                139.74936872720718,
                35.73887748293738
              ],
              [
                139.75013852119446,
                35.73835497357054
              ],
              [
                139.75022971630096,
                35.73828095113295
              ],
              [
                139.750594496727,
                35.73781068933391
              ],
              [
                139.75076347589493,
                35.737584265995665
              ],
              [
                139.74896907806396,
                35.737584265995665
              ],
              [
                139.74870085716248,
                35.738061060544865
              ],
              [
                139.74846482276917,
                35.73848560123372
              ],
              [
                139.74835485219955,
                35.73869242792878
              ],
              [
                139.74737584590912,
                35.739356446844795
              ],
              [
                139.74677234888077,
                35.73973961589623
              ],
              [
                139.74657386541367,
                35.739846293315324
              ],
              [
                139.74616885185242,
                35.73884047197008
              ],
              [
                139.74608033895493,
                35.738864420244994
              ]
            ]
          ],
          [
            [
              [
                139.7549369931221,
                35.74652314444997
              ],
              [
                139.75653290748596,
                35.74652314444997
              ],
              [
                139.75709348917007,
                35.74621837700677
              ],
              [
                139.75709348917007,
                35.74527359051736
              ],
              [
                139.75680381059647,
                35.745454276358345
              ],
              [
                139.75620031356812,
                35.74584176991151
              ],
              [
                139.75581407546997,
                35.746076877440046
              ],
              [
                139.75527226924896,
                35.746368583963886
              ],
              [
                139.7549369931221,
                35.74652314444997
              ]
            ]
          ]
        ]
      },
      "properties": {
        "_id": "WKWFeJEBk4JyLPT2prbl",
        "_index": "bs002_fire_protection_area_202408221417",
        "decision_date": "",
        "city_name": "北区",
        "prefecture": "東京都",
        "city_code": "13117",
        "notice_number_s": "",
        "notice_number": "",
        "decision_classification": "",
        "decision_maker": "",
        "kubun_id": 24,
        "first_decision_date": "",
        "fire_prevention_ja": "防火地域"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              139.74608033895493,
              35.737584265995665
            ],
            [
              139.74608033895493,
              35.738864420244994
            ],
            [
              139.74616885185242,
              35.73884047197008
            ],
            [
              139.74657386541367,
              35.739846293315324
            ],
            [
              139.74677234888077,
              35.73973961589623
            ],
            [
              139.74737584590912,
              35.739356446844795
            ],
            [
              139.74835485219955,
              35.73869242792878
            ],
            [
              139.74846482276917,
              35.73848560123372
            ],
            [
              139.74870085716248,
              35.738061060544865
            ],
            [
              139.74896907806396,
              35.737584265995665
            ],
            [
              139.74861234426498,
              35.737584265995665
            ],
            [
              139.74880278110504,
              35.73764087189059
            ],
            [
              139.74873840808868,
              35.73776279214299
            ],
            [
              139.7487223148346,
              35.73778238645184
            ],
            [
              139.74842727184296,
              35.738287482527284
            ],
            [
              139.74831998348236,
              35.738505195364695
            ],
            [
              139.7482019662857,
              35.738637999903204
            ],
            [
              139.74819660186768,
              35.73869895928934
            ],
            [
              139.74815636873245,
              35.73871637624822
            ],
            [
              139.7475689649582,
              35.73912349657698
            ],
            [
              139.74705934524536,
              35.73941522858037
            ],
            [
              139.74672943353653,
              35.73860098882459
            ],
            [
              139.7467052936554,
              35.738526966615694
            ],
            [
              139.74667847156525,
              35.73841593317336
            ],
            [
              139.7466677427292,
              35.73834191079244
            ],
            [
              139.74666506052017,
              35.73826571121077
            ],
            [
              139.74667310714722,
              35.738152500269095
            ],
            [
              139.74669456481934,
              35.738041466304566
            ],
            [
              139.7467589378357,
              35.737804157900484
            ],
            [
              139.74689036607742,
              35.73784552363652
            ],
            [
              139.74697083234787,
              35.73786729506787
            ],
            [
              139.74722027778625,
              35.73794784931221
            ],
            [
              139.74735170602798,
              35.737821575055094
            ],
            [
              139.7474429011345,
              35.73784552363652
            ],
            [
              139.74753946065903,
              35.73765828908094
            ],
            [
              139.74793374538422,
              35.737817220766814
            ],
            [
              139.74807053804398,
              35.737584265995665
            ],
            [
              139.74608033895493,
              35.737584265995665
            ]
          ]
        ]
      },
      "properties": {
        "_id": "OKWFeJEBk4JyLPT2prZR",
        "_index": "bs002_fire_protection_area_202408221417",
        "decision_date": "",
        "city_name": "豊島区",
        "prefecture": "東京都",
        "city_code": "13116",
        "notice_number_s": "",
        "notice_number": "",
        "decision_classification": "",
        "decision_maker": "",
        "kubun_id": 24,
        "first_decision_date": "",
        "fire_prevention_ja": "防火地域"
      }
    }
  ]
}
```


## Get /ex-api/external/XKT015
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |

### Response
This API returns JSON of passengers by station information.
The sample of response is as follows.

```JSON
{
  "type": "FeatureCollection",
  "name": "passengers_by_station",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::6668"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "LineString",
        "coordinates": [
          [
            139.74696278572083,
            35.74652314444997
          ],
          [
            139.74711030721664,
            35.74644912960676
          ]
        ]
      },
      "properties": {
        "_id": "z0oAl5ABHEII8kGR7Pd5",
        "_index": "bs018_passengers_by_station_202407091918",
        "S12_009": 14104,
        "S12_008": "",
        "S12_007": "1",
        "S12_006": "1",
        "S12_005": "2",
        "S12_049": 12314,
        "S12_004": "11",
        "S12_048": "",
        "S12_047": "1",
        "S12_001_ja": "上中里",
        "S12_046": "1",
        "S12_045": 11776,
        "S12_044": "",
        "S12_043": "1",
        "S12_042": "1",
        "S12_041": 16124,
        "S12_040": "",
        "S12_039": "1",
        "S12_038": "1",
        "S12_037": 16124,
        "S12_036": "",
        "S12_035": "1",
        "S12_034": "1",
        "S12_033": 15280,
        "S12_032": "",
        "S12_031": "1",
        "S12_030": "1",
        "S12_001g": "003277",
        "S12_002_ja": "東日本旅客鉄道",
        "S12_029": 14818,
        "S12_028": "",
        "S12_027": "1",
        "S12_026": "1",
        "S12_025": 14488,
        "S12_024": "",
        "S12_023": "1",
        "S12_022": "1",
        "S12_001c": "003277",
        "S12_021": 14188,
        "S12_020": "",
        "S12_003_ja": "東北線",
        "S12_019": "1",
        "S12_018": "1",
        "S12_017": 13946,
        "S12_016": "",
        "S12_015": "1",
        "S12_014": "1",
        "S12_013": 13966,
        "S12_012": "",
        "S12_011": "1",
        "S12_010": "1",
        "S12_053": 13094,
        "S12_052": "",
        "S12_051": 1,
        "S12_050": 1
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "LineString",
        "coordinates": [
          [
            139.7545427083969,
            35.74652314444997
          ],
          [
            139.75508987903595,
            35.74627062293705
          ]
        ]
      },
      "properties": {
        "_id": "ykoAl5ABHEII8kGR7Pd5",
        "_index": "bs018_passengers_by_station_202407091918",
        "S12_009": 15368,
        "S12_008": "",
        "S12_007": "1",
        "S12_006": "1",
        "S12_005": "2",
        "S12_049": 17560,
        "S12_004": "11",
        "S12_048": "",
        "S12_047": "1",
        "S12_001_ja": "尾久",
        "S12_046": "1",
        "S12_045": 16758,
        "S12_044": "",
        "S12_043": "1",
        "S12_042": "1",
        "S12_041": 20000,
        "S12_040": "",
        "S12_039": "1",
        "S12_038": "1",
        "S12_037": 20000,
        "S12_036": "",
        "S12_035": "1",
        "S12_034": "1",
        "S12_033": 18084,
        "S12_032": "",
        "S12_031": "1",
        "S12_030": "1",
        "S12_001g": "003278",
        "S12_002_ja": "東日本旅客鉄道",
        "S12_029": 17744,
        "S12_028": "",
        "S12_027": "1",
        "S12_026": "1",
        "S12_025": 16248,
        "S12_024": "",
        "S12_023": "1",
        "S12_022": "1",
        "S12_001c": "003278",
        "S12_021": 16056,
        "S12_020": "",
        "S12_003_ja": "東北線",
        "S12_019": "1",
        "S12_018": "1",
        "S12_017": 15486,
        "S12_016": "",
        "S12_015": "1",
        "S12_014": "1",
        "S12_013": 15288,
        "S12_012": "",
        "S12_011": "1",
        "S12_010": "1",
        "S12_053": 18970,
        "S12_052": "",
        "S12_051": 1,
        "S12_050": 1
      }
    }
  ]
}
```


## Get /ex-api/external/XKT016
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |
| administrativeAreaCode | string | Local government code / City code in Japan of 5 digits | true | false |

### Response
This API returns JSON of disaster risk area information.
The sample of response is as follows.

```JSON
{
  "type": "FeatureCollection",
  "name": "disaster_risk_area",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::6668"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              139.9180555343628,
              35.74668641224311
            ],
            [
              139.91848468780518,
              35.74668641224311
            ],
            [
              139.9183988571167,
              35.74644259888197
            ],
            [
              139.91801261901855,
              35.74647742940786
            ],
            [
              139.9180555343628,
              35.74668641224311
            ]
          ]
        ]
      },
      "properties": {
        "_id": "Fq8_B44Byh1a-fbIDHZB",
        "_index": "bs019_disaster_risk_area_202403040215",
        "A48_011": "千葉県建築基準法施行条例",
        "A48_001": "千葉県",
        "A48_012": 1.2,
        "A48_010": "千第1043号(急傾斜)",
        "A48_004": 1,
        "A48_002": "市川市",
        "A48_013": "1/2000",
        "A48_003": "12203",
        "A48_014": "",
        "A48_007_name_ja": "急傾斜地崩壊等",
        "A48_009": "1986-11-07T00:00:00",
        "A48_006": "市川市国分5丁目",
        "A48_007": 4,
        "A48_008_ja": "急傾斜地崩壊",
        "A48_005_ja": "国分の2"
      }
    }
  ]
}
```


## Get /ex-api/external/XKT017
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |
| administrativeAreaCode | string | Local government code / City code in Japan of 5 digits | true | false |

### Response
This API returns JSON of cultural facility information.
The sample of response is as follows.

```JSON
{
  "type": "FeatureCollection",
  "name": "cultural_facility",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::4612"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.74748849868774,
          35.74339922284034
        ]
      },
      "properties": {
        "_id": "zLBAB44Byh1a-fbIIwa8",
        "_index": "bs020_cultural_facility_202403040216",
        "P27_001": "13117",
        "P27_006_ja": "西ヶ原1-23-3",
        "P27_004_name_ja": "図書館",
        "P27_005_ja": "北区立滝野川図書館",
        "P27_003_name_ja": "図書館",
        "P27_009": 9999,
        "P27_008": -99,
        "P27_007": 3,
        "P27_004": "03003",
        "P27_003": "03003",
        "P27_002": "3"
      }
    }
  ]
}
```


## Get /ex-api/external/XKT018
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |

### Response
This API returns JSON of city town hall information.
The sample of response is as follows.

```JSON
{
  "type": "FeatureCollection",
  "name": "city_town_hall",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::6668"
    }
  },
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.74759578704834,
          35.74339922284034
        ]
      },
      "properties": {
        "_id": "xq45B44Byh1a-fbIVRlU",
        "_index": "bs009_city_town_hall_202403040208",
        "P05_004_ja": "北区西ケ原1-23-3",
        "P05_003_ja": "滝野川会館",
        "P05_002": "5",
        "P05_001": "13117",
        "P05_002_name_ja": "集会施設"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.74748313426971,
          35.743540727166774
        ]
      },
      "properties": {
        "_id": "y645B44Byh1a-fbIVRlU",
        "_index": "bs009_city_town_hall_202403040208",
        "P05_004_ja": "北区西ケ原1-23-3",
        "P05_003_ja": "滝野川区民事務所",
        "P05_002": "3",
        "P05_001": "13117",
        "P05_002_name_ja": "上記以外の行政サービス施設"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          139.7474616765976,
          35.743540727166774
        ]
      },
      "properties": {
        "_id": "zK45B44Byh1a-fbIVRlU",
        "_index": "bs009_city_town_hall_202403040208",
        "P05_004_ja": "北区西ケ原1-23-3",
        "P05_003_ja": "滝野川文化センター",
        "P05_002": "5",
        "P05_001": "13117",
        "P05_002_name_ja": "集会施設"
      }
    }
  ]
}
```


## Get /ex-api/external/XKT019
### Parameters
This API requires at least five arguments.

| name | type | description | runtime | required |
| --- | --- | --- | --- | --- |
| Ocp-Apim-Subscription-Key | string | Access token provided on developer site | false | true |
| response_format | string | geojson or pbf | true | true |
| z | number | Zoom level | true | true |
| x | number | Tile x value | true | true |
| y | number | Tile y value | true | true |
| prefectureCode | string | Local government code / Prefecture code in Japan of 2 digits | true | false |
| districtCode | string | District code in Japan of 1 or 2 digits | true | false |

### Response
This API returns JSON of natural park area information.
The sample of response is as follows.

```JSON
{
  "type": "FeatureCollection",
  "name": "natural_park_area",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::4612"
    }
  },
  "features": []
}
```


## Examples

```
input: ズームレベル14、x=14552、y=6451のタイルで取得するgeojsonに小学校区はいくつありますか？

output: The specified tile contains 8 elementary school districts. These are: 千代田小学校, 麹町小学校, 富士見小学 校, お茶の水小学校, 泰明小学校, 城東小学校, 九段小学校.

```
