# Function: extractUrlFromText()

> **extractUrlFromText**(`text`): `undefined` \| `string`

Defined in: [src/Utils/messages.ts:77](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/src/Utils/messages.ts#L77)

Uses a regex to test whether the string contains a URL, and returns the URL if it does.

## Parameters

### text

`string`

eg. hello https://google.com

## Returns

`undefined` \| `string`

the URL, eg. https://google.com
