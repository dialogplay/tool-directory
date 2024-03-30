# Integration for JMA Forecast
This integration provides API for obtaining weather information of the area specified by users.

## Get /forecast/data/overview_forecast/{area}.json
### Parameters
This API requires one argument.

| name | type | description | runtime |
| --- | --- | --- | --- |
| area | string | Location for obtaining weather information | true |

## Get /forecast/data/forecast/{area}.json
### Parameters

| name | type | description | runtime |
| --- | --- | --- | --- |
| area | string | Location for obtaining weather information | true |


## Examples

```
input: Tell me about tokyo overview forecast.

output: The overview forecast for Tokyo indicates that the region is gently covered by high pressure, with the Tokaido offshore being a pressure valley. The weather is expected to be sunny or cloudy. On the 27th, despite being covered by high pressure, the region is expected to be affected by a pressure valley and humid air, leading to sunny weather turning cloudy at night. On the 28th, it will initially be covered by high pressure, but is expected to be affected by humid air, resulting in cloudy weather turning rainy at night. The same forecast applies to the Kanto Koshin region. There is a warning for ships in the Kanto region and the Izu Islands to be cautious of high waves on the 27th and 28th.

input: 東京都の天気概況を日本語で教えて

output: 東京都の天気概況は次の通りです。\n\n本州は高気圧に緩やかに覆われていますが、東海道沖は気圧の谷となっています。東京地方は、晴れや曇りとなっています。\n\n27日は、高気圧に覆われますが、気圧の谷や湿った空気の影響を受ける見込みです。このため、晴れで夜は曇りとなるでしょう。\n\n28日は、はじめ高気圧に覆われますが、湿った空気の影響を受ける見込みです。このため、曇りで夜は雨となるでしょう。\n\n関東甲信地方は、晴れや曇りとなっています。27日は、高気圧に覆われますが、気圧の谷や湿った空気の影響を受ける見込みです。このため、晴れや曇りとなるでしょう。\n\n28日は、はじめ高気圧に覆われますが、湿った空気の影響を受ける見込みです。このため、曇りで夜は雨となるでしょう。\n\n関東地方と伊豆諸島の海上では、うねりを伴い、27日はしけとなり、28日は波が高い見込みです。船舶は高波に注意してください。

input: Tell me about tomorrow forecast in tokyo.

output: The forecast for Tokyo tomorrow is as follows: \n\n- Weather: Cloudy with rain at night\n- Wind: North wind, becoming a somewhat strong south wind later\n- Wave height: 0.5 meters, increasing to 1 meter later\n\nPlease note that this is a forecast and actual conditions may vary.

input: 東京都の明日の天気予報を日本語で教えて

output: 東京都の明日の天気予報は次の通りです：天気はくもりで、夜には雨が降る予定です。風は北から吹き、後に南からやや強く吹く予定です。波の高さは0.5メートルで、後に1メートルに増える予定です。降水確率は、今日の18:00時点で0％、明日の6:00時点で10％、明日の12:00時点で20％、明日の18:00時点で50％です。最低気温は6度、最高気温は15度となる予定です。
```
