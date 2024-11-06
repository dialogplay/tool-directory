# Integration for VOICEVOX API
This integration provides API for obtaining voicevox tts url.

## Get /v2/voicevox/audio/
### Parameters
This API requires at least two arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| key | string | API key | true |
| text | string | Text for TTS | true |

### Response
This API returns binary wav data.


## Get /v2/voicevox/speakers/
### Parameters
This API requires one argument.

| name | type | description | runtime |
| --- | --- | --- | --- |
| key | string | API key | true |

### Response
This API returns JSON of speakers list.
The sample of response is as follows.
```JSON
[
	{
		"supported_features": {
			"permitted_synthesis_morphing": "SELF_ONLY"
		},
		"name": "四国めたん",
		"speaker_uuid": "7ffcb7ce-00ec-4bdc-82cd-45a8889e43ff",
		"styles": [
			{
				"name": "ノーマル",
				"id": 2,
				"type": "talk"
			},
			{
				"name": "あまあま",
				"id": 0,
				"type": "talk"
			},
			{
				"name": "ツンツン",
				"id": 6,
				"type": "talk"
			},
			{
				"name": "セクシー",
				"id": 4,
				"type": "talk"
			},
			{
				"name": "ささやき",
				"id": 36,
				"type": "talk"
			},
			{
				"name": "ヒソヒソ",
				"id": 37,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "SELF_ONLY"
		},
		"name": "ずんだもん",
		"speaker_uuid": "388f246b-8c41-4ac1-8e2d-5d79f3ff56d9",
		"styles": [
			{
				"name": "ノーマル",
				"id": 3,
				"type": "talk"
			},
			{
				"name": "あまあま",
				"id": 1,
				"type": "talk"
			},
			{
				"name": "ツンツン",
				"id": 7,
				"type": "talk"
			},
			{
				"name": "セクシー",
				"id": 5,
				"type": "talk"
			},
			{
				"name": "ささやき",
				"id": 22,
				"type": "talk"
			},
			{
				"name": "ヒソヒソ",
				"id": 38,
				"type": "talk"
			},
			{
				"name": "ヘロヘロ",
				"id": 75,
				"type": "talk"
			},
			{
				"name": "なみだめ",
				"id": 76,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "春日部つむぎ",
		"speaker_uuid": "35b2c544-660e-401e-b503-0e14c635303a",
		"styles": [
			{
				"name": "ノーマル",
				"id": 8,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "雨晴はう",
		"speaker_uuid": "3474ee95-c274-47f9-aa1a-8322163d96f1",
		"styles": [
			{
				"name": "ノーマル",
				"id": 10,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "波音リツ",
		"speaker_uuid": "b1a81618-b27b-40d2-b0ea-27a9ad408c4b",
		"styles": [
			{
				"name": "ノーマル",
				"id": 9,
				"type": "talk"
			},
			{
				"name": "クイーン",
				"id": 65,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "玄野武宏",
		"speaker_uuid": "c30dc15a-0992-4f8d-8bb8-ad3b314e6a6f",
		"styles": [
			{
				"name": "ノーマル",
				"id": 11,
				"type": "talk"
			},
			{
				"name": "喜び",
				"id": 39,
				"type": "talk"
			},
			{
				"name": "ツンギレ",
				"id": 40,
				"type": "talk"
			},
			{
				"name": "悲しみ",
				"id": 41,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "白上虎太郎",
		"speaker_uuid": "e5020595-5c5d-4e87-b849-270a518d0dcf",
		"styles": [
			{
				"name": "ふつう",
				"id": 12,
				"type": "talk"
			},
			{
				"name": "わーい",
				"id": 32,
				"type": "talk"
			},
			{
				"name": "びくびく",
				"id": 33,
				"type": "talk"
			},
			{
				"name": "おこ",
				"id": 34,
				"type": "talk"
			},
			{
				"name": "びえーん",
				"id": 35,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "青山龍星",
		"speaker_uuid": "4f51116a-d9ee-4516-925d-21f183e2afad",
		"styles": [
			{
				"name": "ノーマル",
				"id": 13,
				"type": "talk"
			},
			{
				"name": "熱血",
				"id": 81,
				"type": "talk"
			},
			{
				"name": "不機嫌",
				"id": 82,
				"type": "talk"
			},
			{
				"name": "喜び",
				"id": 83,
				"type": "talk"
			},
			{
				"name": "しっとり",
				"id": 84,
				"type": "talk"
			},
			{
				"name": "かなしみ",
				"id": 85,
				"type": "talk"
			},
			{
				"name": "囁き",
				"id": 86,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "冥鳴ひまり",
		"speaker_uuid": "8eaad775-3119-417e-8cf4-2a10bfd592c8",
		"styles": [
			{
				"name": "ノーマル",
				"id": 14,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "SELF_ONLY"
		},
		"name": "九州そら",
		"speaker_uuid": "481fb609-6446-4870-9f46-90c4dd623403",
		"styles": [
			{
				"name": "ノーマル",
				"id": 16,
				"type": "talk"
			},
			{
				"name": "あまあま",
				"id": 15,
				"type": "talk"
			},
			{
				"name": "ツンツン",
				"id": 18,
				"type": "talk"
			},
			{
				"name": "セクシー",
				"id": 17,
				"type": "talk"
			},
			{
				"name": "ささやき",
				"id": 19,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "SELF_ONLY"
		},
		"name": "もち子さん",
		"speaker_uuid": "9f3ee141-26ad-437e-97bd-d22298d02ad2",
		"styles": [
			{
				"name": "ノーマル",
				"id": 20,
				"type": "talk"
			},
			{
				"name": "セクシー／あん子",
				"id": 66,
				"type": "talk"
			},
			{
				"name": "泣き",
				"id": 77,
				"type": "talk"
			},
			{
				"name": "怒り",
				"id": 78,
				"type": "talk"
			},
			{
				"name": "喜び",
				"id": 79,
				"type": "talk"
			},
			{
				"name": "のんびり",
				"id": 80,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "剣崎雌雄",
		"speaker_uuid": "1a17ca16-7ee5-4ea5-b191-2f02ace24d21",
		"styles": [
			{
				"name": "ノーマル",
				"id": 21,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "WhiteCUL",
		"speaker_uuid": "67d5d8da-acd7-4207-bb10-b5542d3a663b",
		"styles": [
			{
				"name": "ノーマル",
				"id": 23,
				"type": "talk"
			},
			{
				"name": "たのしい",
				"id": 24,
				"type": "talk"
			},
			{
				"name": "かなしい",
				"id": 25,
				"type": "talk"
			},
			{
				"name": "びえーん",
				"id": 26,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "後鬼",
		"speaker_uuid": "0f56c2f2-644c-49c9-8989-94e11f7129d0",
		"styles": [
			{
				"name": "人間ver.",
				"id": 27,
				"type": "talk"
			},
			{
				"name": "ぬいぐるみver.",
				"id": 28,
				"type": "talk"
			},
			{
				"name": "人間（怒り）ver.",
				"id": 87,
				"type": "talk"
			},
			{
				"name": "鬼ver.",
				"id": 88,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "No.7",
		"speaker_uuid": "044830d2-f23b-44d6-ac0d-b5d733caa900",
		"styles": [
			{
				"name": "ノーマル",
				"id": 29,
				"type": "talk"
			},
			{
				"name": "アナウンス",
				"id": 30,
				"type": "talk"
			},
			{
				"name": "読み聞かせ",
				"id": 31,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "ちび式じい",
		"speaker_uuid": "468b8e94-9da4-4f7a-8715-a22a48844f9e",
		"styles": [
			{
				"name": "ノーマル",
				"id": 42,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "櫻歌ミコ",
		"speaker_uuid": "0693554c-338e-4790-8982-b9c6d476dc69",
		"styles": [
			{
				"name": "ノーマル",
				"id": 43,
				"type": "talk"
			},
			{
				"name": "第二形態",
				"id": 44,
				"type": "talk"
			},
			{
				"name": "ロリ",
				"id": 45,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "小夜/SAYO",
		"speaker_uuid": "a8cc6d22-aad0-4ab8-bf1e-2f843924164a",
		"styles": [
			{
				"name": "ノーマル",
				"id": 46,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "ナースロボ＿タイプＴ",
		"speaker_uuid": "882a636f-3bac-431a-966d-c5e6bba9f949",
		"styles": [
			{
				"name": "ノーマル",
				"id": 47,
				"type": "talk"
			},
			{
				"name": "楽々",
				"id": 48,
				"type": "talk"
			},
			{
				"name": "恐怖",
				"id": 49,
				"type": "talk"
			},
			{
				"name": "内緒話",
				"id": 50,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "†聖騎士 紅桜†",
		"speaker_uuid": "471e39d2-fb11-4c8c-8d89-4b322d2498e0",
		"styles": [
			{
				"name": "ノーマル",
				"id": 51,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "雀松朱司",
		"speaker_uuid": "0acebdee-a4a5-4e12-a695-e19609728e30",
		"styles": [
			{
				"name": "ノーマル",
				"id": 52,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "麒ヶ島宗麟",
		"speaker_uuid": "7d1e7ba7-f957-40e5-a3fc-da49f769ab65",
		"styles": [
			{
				"name": "ノーマル",
				"id": 53,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "春歌ナナ",
		"speaker_uuid": "ba5d2428-f7e0-4c20-ac41-9dd56e9178b4",
		"styles": [
			{
				"name": "ノーマル",
				"id": 54,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "猫使アル",
		"speaker_uuid": "00a5c10c-d3bd-459f-83fd-43180b521a44",
		"styles": [
			{
				"name": "ノーマル",
				"id": 55,
				"type": "talk"
			},
			{
				"name": "おちつき",
				"id": 56,
				"type": "talk"
			},
			{
				"name": "うきうき",
				"id": 57,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "猫使ビィ",
		"speaker_uuid": "c20a2254-0349-4470-9fc8-e5c0f8cf3404",
		"styles": [
			{
				"name": "ノーマル",
				"id": 58,
				"type": "talk"
			},
			{
				"name": "おちつき",
				"id": 59,
				"type": "talk"
			},
			{
				"name": "人見知り",
				"id": 60,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "SELF_ONLY"
		},
		"name": "中国うさぎ",
		"speaker_uuid": "1f18ffc3-47ea-4ce0-9829-0576d03a7ec8",
		"styles": [
			{
				"name": "ノーマル",
				"id": 61,
				"type": "talk"
			},
			{
				"name": "おどろき",
				"id": 62,
				"type": "talk"
			},
			{
				"name": "こわがり",
				"id": 63,
				"type": "talk"
			},
			{
				"name": "へろへろ",
				"id": 64,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "栗田まろん",
		"speaker_uuid": "04dbd989-32d0-40b4-9e71-17c920f2a8a9",
		"styles": [
			{
				"name": "ノーマル",
				"id": 67,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "あいえるたん",
		"speaker_uuid": "dda44ade-5f9c-4a3a-9d2c-2a976c7476d9",
		"styles": [
			{
				"name": "ノーマル",
				"id": 68,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "満別花丸",
		"speaker_uuid": "287aa49f-e56b-4530-a469-855776c84a8d",
		"styles": [
			{
				"name": "ノーマル",
				"id": 69,
				"type": "talk"
			},
			{
				"name": "元気",
				"id": 70,
				"type": "talk"
			},
			{
				"name": "ささやき",
				"id": 71,
				"type": "talk"
			},
			{
				"name": "ぶりっ子",
				"id": 72,
				"type": "talk"
			},
			{
				"name": "ボーイ",
				"id": 73,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	},
	{
		"supported_features": {
			"permitted_synthesis_morphing": "ALL"
		},
		"name": "琴詠ニア",
		"speaker_uuid": "97a4af4b-086e-4efd-b125-7ae2da85e697",
		"styles": [
			{
				"name": "ノーマル",
				"id": 74,
				"type": "talk"
			}
		],
		"version": "0.15.4"
	}
]
```


## Get /v2/api/
### Parameters
This API requires one argument.

| name | type | description | runtime |
| --- | --- | --- | --- |
| key | string | API key | true |

### Response
This API returns JSON of points information.
The sample of response is as follows.
```JSON
{
  "points": 9998500,
  "resetInHours": 24
}
```


## Examples

```
input: id=2の四国めたんで、「こんにちは」を読み上げるURLを教えて。音声データは不要なのでAPIを呼び出さす必要はありません。

output: https://deprecatedapis.tts.quest/v2/voicevox/audio/?key=YOUR_API_KEY&text=こんにちは&speaker=2

input: 雨晴はうの uuid と、ノーマルの id を教えて。

output: The UUID of '雨晴はう' is '3474ee95-c274-47f9-aa1a-8322163d96f1' and the ID of the 'ノーマル' style is 10.

input: VOICEVOXのポイントの残りを教えて。

output: VOICEVOXの残りのポイントは9949500ポイントで、約0.91時間後にリセットされます。
```