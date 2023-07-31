# Integration for OpenWeather
This integration provides API for obtaining weather information of the city specified by users.

## Get /weather
### Parameters
This API requires three arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| appid | string | API key for calling API | false |
| q | string | Location for obtaining weather information | true |
| units | string | Units of measurement (Celsius by default) | true |

### Response
This API returns JSON of weather information.
The sample of response is as follows.
```JSON
{
  "coord": {
    "lon": 139.6917,
    "lat": 35.6895
  },
  "weather": [
    {
      "id": 211,
      "main": "Thunderstorm",
      "description": "thunderstorm",
      "icon": "11d"
    },
    {
      "id": 501,
      "main": "Rain",
      "description": "moderate rain",
      "icon": "10d"
    }
  ],
  "base": "stations",
  "main": {
    "temp": 25.37,
    "feels_like": 26.21,
    "temp_min": 24.75,
    "temp_max": 27.58,
    "pressure": 1013,
    "humidity": 86
  },
  "visibility": 10000,
  "wind": {
    "speed": 10.8,
    "deg": 160
  },
  "rain": {
    "1h": 1.33
  },
  "clouds": {
    "all": 75
  },
  "dt": 1690868464,
  "sys": {
    "type": 2,
    "id": 2018776,
    "country": "JP",
    "sunrise": 1690832909,
    "sunset": 1690883195
  },
  "timezone": 32400,
  "id": 1850144,
  "name": "Tokyo",
  "cod": 200
}
```
