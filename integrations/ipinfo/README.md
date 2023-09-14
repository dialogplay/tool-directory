# Integration for ipinfo
This integration provides API for obtaining ip information from your access.

## Get /
### Parameters
This API requires one argument.

| name | type | description | runtime |
| --- | --- | --- | --- |
| token | string | API key for calling API | false |

### Response
This API returns JSON of ip information.
The sample of response is as follows.
```JSON
{
  "ip": "54.246.228.58",
  "hostname": "ec2-54-246-228-58.eu-west-1.compute.amazonaws.com",
  "city": "Dublin",
  "region": "Leinster",
  "country": "IE",
  "loc": "53.3331,-6.2489",
  "org": "AS16509 Amazon.com, Inc.",
  "postal": "D02",
  "timezone": "Europe/Dublin"
}
```
