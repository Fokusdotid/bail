# Function: extractUrlFromText()

> **extractUrlFromText**(`text`): `undefined` \| `string`

Defined in: [src/Utils/messages.ts:77](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/src/Utils/messages.ts#L77)

Uses a regex to test whether the string contains a URL, and returns the URL if it does.

## Parameters

### text

`string`

eg. hello https://google.com

## Returns

`undefined` \| `string`

the URL, eg. https://google.com
