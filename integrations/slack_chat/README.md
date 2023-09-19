# Integration for Slack chat
This integration provides API for Slack chat operation.

## Post /chat.postMessage
### Parameters
This API requires one arguments.

| name | type | description | runtime |
| --- | --- | --- | --- |
| token | string | API key for calling API | false |
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
input: Retreive current ip address as {#content}. Then please send messege the {#content} to slack target channel is {#channel}\n#channel: #random.

output: The current IP address has been successfully sent to the '#random' Slack channel.

input: Slackで Hello というメッセージを次のチャンネル {#channel} に送信して。\n#channel: #random

output: メッセージ 'Hello' が Slack の #random チャンネルに正常に送信されました。
```