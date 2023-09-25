# Integration for japansearchAPI
This integration provides API for obtaining digital archives of the japansearch.

## Get /item/search/jps-cross
### Parameters
This API requires at least one keyword argument.

| name | type | description | runtime |
| --- | --- | --- | --- |
| keyword | string | Keyword for obtaining digital archives | true |
| from | number | Start position for obtaining | true |
| size | number | Maximum obtaining counts | true |

### Response
This API returns JSON of current works information.
The sample of response is as follows.
```JSON
{
	"list": [
		{
			"id": "kochizu_collection-172",
			"common": {
				"id": "kochizu_collection-172",
				"title": "江戸實測図　(南)",
				"titleYomi": "えどじっそくず　みなみ",
				"lastUpdatedDate": 1600150262365,
				"linkUrl": "https://kochizu.gsi.go.jp/items/172?from=category,7",
				"thumbnailUrl": [
					"https://kochizu.gsi.go.jp/map-thumbnails/186-2.jpg"
				],
				"contentsType": "image",
				"contentsRightsType": "ccby",
				"contentsAccess": "internet",
				"category": [
					"map"
				],
				"contributor": [
					"伊能忠敬"
				],
				"location": [
					"江戸實測図　(南)",
					"東京都渋谷･目黒･港･品川･千代田･江東区",
					"晩年の伊能忠敬による測量に基づき、縮尺6000分の１（１町を６分）で作成された江戸図の模写図。別名「江戸府内図」と称され、手彩色で北部と南部の２枚で江戸市中を描いた。本図は、その南半分である。図中の凡例には、文化14年（1817）、高橋景保ほか６名が連署して、図を作製することになった背景や測量過程などが明記される。北は上野不忍池、東が中川、南は品川宿、西は堀之内妙法寺まで描かれている。",
					"江戸府内図、中川、品川宿、堀之内、測量"
				],
				"coordinates": {
					"lat": 35.672990000000006,
					"lon": 139.81636
				},
				"provider": "GSI",
				"ownerOrg": "GSI",
				"database": "kochizu_collection",
				"apiType": "ok",
				"subCategory": [
					"古地図"
				],
				"access": "PUBLIC",
				"dclass": "291"
			},
			"rdfindex": {
				"type": [
					"地図資料"
				],
				"temporal": [
					"江戸時代",
					"朝鮮・李氏朝鮮時代",
					"中国・清時代"
				],
				"spatial": [
					"日本 > 東京都"
				]
			},
			"kochizu_collection-8-s": "1817年",
			"kochizu_collection-7-s": "文化14年",
			"kochizu_collection-12-u": "https://kochizu.gsi.go.jp/items/172?from=category,7",
			"kochizu_collection-5-s": "伊能忠敬",
			"kochizu_collection-13-u": "https://kochizu.gsi.go.jp/map-thumbnails/186-2.jpg",
			"kochizu_collection-10-s": "晩年の伊能忠敬による測量に基づき、縮尺6000分の１（１町を６分）で作成された江戸図の模写図。別名「江戸府内図」と称され、手彩色で北部と南部の２枚で江戸市中を描いた。本図は、その南半分である。図中の凡例には、文化14年（1817）、高橋景保ほか６名が連署して、図を作製することになった背景や測量過程などが明記される。北は上野不忍池、東が中川、南は品川宿、西は堀之内妙法寺まで描かれている。",
			"kochizu_collection-9-s": "東京都渋谷･目黒･港･品川･千代田･江東区",
			"kochizu_collection-11-s": "江戸府内図、中川、品川宿、堀之内、測量",
			"kochizu_collection-0-s": "172",
			"kochizu_collection-4-s": "えどじっそくず　みなみ",
			"kochizu_collection-3-s": "江戸實測図　(南)",
			"kochizu_collection-2-s": "186",
			"kochizu_collection-1-s": "都市図"
		}
	],
	"hit": 819862,
	"from": 0,
	"facets": [
		{
			"key": "rights",
			"counts": {
				"incr": 107406,
				"edu": 173259,
				"noncom": 171993,
				"com": 163112,
				"pdm": 86737,
				"uneval": 63190,
				"nocr_cont": 51227,
				"others": 45848,
				"ccby": 42443,
				"ccbysa": 30506,
				"ccbyncsa": 7156,
				"cc0": 3426,
				"ccbync": 1725,
				"incr_edu": 1266,
				"ccbyncnd": 629,
				"undet": 601,
				"ccbynd": 20,
				"nocr_other": 12
			}
		},
		{
			"key": "contents",
			"counts": {
				"internet": 381597,
				"not_exist": 219092,
				"restricted": 46071,
				"iiif": 175631,
				"thumb": 392597,
				"image": 383828,
				"text": 17295,
				"video": 1026,
				"pdf": 648,
				"sound": 328
			}
		},
		{
			"key": "type",
			"counts": {
				"ancdoc": 235343,
				"archeology": 81545,
				"paint": 104134,
				"docs": 59230,
				"performance": 33763,
				"media": 25423,
				"book": 25266,
				"periodical": 19751,
				"other": 16082,
				"natural": 7700,
				"architecture": 5260,
				"lacquer": 4200,
				"daw": 3618,
				"map": 2939,
				"photo": 3480,
				"ceramic": 2155,
				"sculpture": 1944,
				"poster": 1788,
				"arts": 1815,
				"metal": 1179,
				"craft": 2018,
				"exhibition": 716,
				"article": 705,
				"weaponry": 797,
				"broadcast": 548,
				"anime": 328,
				"movie": 166,
				"site": 165,
				"video": 146,
				"offdoc": 115,
				"postcard": 106,
				"customs": 81,
				"org": 75,
				"recording": 44,
				"mediaart": 40,
				"stone": 36,
				"game": 27,
				"dataset": 4,
				"ematerial": 4,
				"mscore": 3,
				"3d": 2
			}
		},
		{
			"key": "db",
			"counts": {
				"fukui": 100386,
				"dignl": 84856,
				"arc_nishikie": 84007,
				"kyudai": 65590,
				"nmj01": 45890,
				"arc_ban": 38873,
				"enpk_ukiyoe": 35880,
				"arc_books": 34628,
				"bibnl": 34468,
				"cobas": 33829,
				"nij14": 33729,
				"nij16": 28925,
				"adeac": 22044,
				"utokyo_da": 17904,
				"nij21": 16310,
				"tokyomuseumcolection": 16269,
				"nij15": 13099,
				"nij10": 9878,
				"bunka": 9040,
				"nme_lib_books": 7578,
				"tokyo": 7497,
				"aokenshida_doc": 6602,
				"nij06": 5383,
				"saga": 4879,
				"nij11": 4494,
				"miyagi": 4490,
				"miemu02": 3375,
				"najda": 3306,
				"osaka": 3132,
				"keioobjecthub": 2912,
				"nij01": 2875,
				"nij19": 2366,
				"syozo": 2260,
				"nmj02": 2161,
				"aokenshida_txt": 1883,
				"aokenshida_mat": 1677,
				"nin01": 1646,
				"saitama_museum": 1510,
				"nme_trackInfo": 1295,
				"s_net": 1272,
				"ukansai": 1183,
				"cria": 1150,
				"sdcommons_npl": 1100,
				"ryukoku": 934,
				"artmuseb": 872,
				"enpaku_engekijoen": 850,
				"chiba": 820,
				"exhib": 805,
				"yamanashi": 741,
				"cb1": 704,
				"rekibun": 676,
				"tfam_art_db": 599,
				"michi": 558,
				"apmoa_mapps": 502,
				"irc05": 500,
				"uryukyu": 479,
				"tpada_kenmei": 385,
				"miebunkazai": 354,
				"madb_animation": 342,
				"enpk_eigaphoto": 310,
				"shimane_u": 287,
				"nij17": 281,
				"chiba_u": 273,
				"narabook": 266,
				"nij20": 244,
				"irc06": 242,
				"sapporo": 242,
				"Nhikie": 233,
				"doshisha": 233,
				"u001": 224,
				"arc_resource": 217,
				"oitacityarchive": 206,
				"kochizu_collection": 187,
				"bunkazai_video": 183,
				"kyoto": 183,
				"artmuse": 180,
				"aozora": 169,
				"ukobe_s": 168,
				"nfad": 164,
				"nme_audcat": 154,
				"sdcommons_npmh": 152,
				"ibaraki": 151,
				"saiku": 151,
				"aokenshida_lib": 145,
				"nij13": 129,
				"shisan": 118,
				"photo": 116,
				"irc01": 115,
				"nij22": 114,
				"irc07": 109,
				"saitama_monjo_search": 109,
				"lib": 102,
				"nmj03": 94,
				"nij07": 89,
				"nier_orai": 80,
				"epad_db": 70,
				"hpmm_magazine": 70,
				"nier_mode": 70,
				"hpmm_book": 69,
				"rih01": 65,
				"SHUGYOKU1": 59,
				"hdm": 57,
				"machihaku": 53,
				"bjfl": 52,
				"tdc_muse": 51,
				"miemub": 50,
				"a1545100173162": 49,
				"kamakura": 47,
				"nij02": 46,
				"SHUGYOKU2": 44,
				"madb_mediaart": 42,
				"tokushima": 42,
				"u002": 42,
				"kuhi": 36,
				"waseda_enpaku_jdta": 34,
				"daito": 33,
				"wakayama_archives": 30,
				"sdcommons_video": 29,
				"sf004": 29,
				"u006": 29,
				"utokushima": 28,
				"madb_game": 27,
				"rih04": 25,
				"kennai": 24,
				"hpmm_abomb": 22,
				"sekigahara_archive": 22,
				"Chigamu": 21,
				"nme_mobib": 21,
				"ukobe": 21,
				"aomori": 19,
				"nme_movcat": 19,
				"tdc": 19,
				"nme_lib_serialpub": 18,
				"nme_inada": 15,
				"moco_cs": 14,
				"nme_umesaoWW": 14,
				"nier_rare": 13,
				"moco_od": 11,
				"Polamuseumofart": 10,
				"nme_ir": 10,
				"saitama_digi_lib": 10,
				"suisan": 10,
				"yuma_001": 8,
				"nin05": 7,
				"nme_mocat": 6,
				"rih02": 6,
				"u011": 6,
				"nme_vtqcat": 5,
				"a12345": 4,
				"kyusan": 4,
				"miemug": 4,
				"sf003": 4,
				"aokenshida_pic": 3,
				"enpk_adultfilmpress": 3,
				"hischigasakicity": 3,
				"hpmm_abombdrawing": 3,
				"irc04": 3,
				"iwate": 3,
				"miemu01": 3,
				"nme_nakanisi": 3,
				"yamagata": 3,
				"FGKE": 2,
				"MoMAS": 2,
				"kaizuArchive": 2,
				"minakata": 2,
				"rih06": 2,
				"u004": 2,
				"gunma": 1,
				"jafc": 1,
				"jomon_archives": 1,
				"maibunb": 1,
				"musee_gsj": 1,
				"nda01": 1
			}
		},
		{
			"key": "cm",
			"counts": {
				"book": 398111,
				"humanities": 372794,
				"art": 141961,
				"cultural": 91389,
				"pfart": 75872,
				"regional": 38161,
				"science": 22731,
				"official": 22054,
				"movie": 772,
				"broadcast": 741,
				"anime": 343,
				"map": 337,
				"media": 337,
				"game": 27,
				"dataset": 4
			}
		},
		{
			"key": "tempo",
			"counts": {
				"edo": 501914,
				"showa": 51867,
				"heisei": 34165,
				"meiji": 15404,
				"taisyo": 4336,
				"reiwa": 3009,
				"muromachi": 1052,
				"kamakura": 790,
				"aduchi": 618,
				"heian": 596,
				"asuka": 341,
				"ancient": 317,
				"nara": 202
			}
		}
	]
}
```

## Examples

```
input: japansearchから北杜夫の作品を5件取得して、教えて

output: The user asked for 5 works of Kitahara Hakushū from Japansearch. The search results returned are as follows:\n\n1. [北杜夫による北杜夫](http://dl.ndl.go.jp/info:ndljp/pid/12493762) - Published by 青銅社 in 1982.10 in Tokyo.\n2. [北杜夫](https://museumcollection.tokyo/works/86635/) - A photograph by 林 忠彦 (HAYASHI Tadahiko) taken between 1946-1971.\n3. [北杜夫集](http://dl.ndl.go.jp/info:ndljp/pid/2529582) - Published by 新潮社 in 1968.10(12刷:1991.5) in Tokyo.\n4. [北杜夫](https://www.sagalibdb.jp/jinmei/detail/?name=北杜夫) - A book in the Saga library database.\n5. [追悼　北杜夫　北杜夫の心の葛藤](https://bridge.nihu.jp/integrated_searchresults_detail/14234657) - A paper by 三浦朱門 (MIURA Shumon) published in 2012.\n\nPlease note that the access to some of these works might be restricted.
```