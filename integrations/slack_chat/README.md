# Integration for Slack chat
This integration provides API for Slack chat operation.

## Post /chat.postMessage
### Parameters
This API requires three arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| token | string | User OAuth Token or Bot User OAuth Token for calling API | false |
| channel | string | Channel to send message to | true |
| text | string | Message text | true |

### Response
This API returns JSON of sent message information.
The sample of response is as follows.
```JSON
{
  "ok": true,
  "channel": "C........",
  "ts": "1695079370.579359",
  "message": {
    "bot_id": "B..........",
    "type": "message",
    "text": "The current IP address is xxx.xxx.xxx.xxx",
    "user": "U..........",
    ...
}
```

## Examples

```
input: Post current ip address to #chatbot-test in slack.

output: The current IP address has been successfully sent to the '#chatbot-test' Slack channel.

input: SlackでIPアドレスをチャンネル#randomに送信して。

output: IPアドレス情報をSlackの#randomチャンネルに送信しました。
```