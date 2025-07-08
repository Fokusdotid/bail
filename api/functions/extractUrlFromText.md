# Function: extractUrlFromText()

> **extractUrlFromText**(`text`): `undefined` \| `string`

Defined in: [src/Utils/messages.ts:77](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Utils/messages.ts#L77)

Uses a regex to test whether the string contains a URL, and returns the URL if it does.

## Parameters

### text

`string`

eg. hello https://google.com

## Returns

`undefined` \| `string`

the URL, eg. https://google.com
