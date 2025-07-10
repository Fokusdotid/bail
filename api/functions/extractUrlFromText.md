# Function: extractUrlFromText()

> **extractUrlFromText**(`text`): `undefined` \| `string`

Defined in: [src/Utils/messages.ts:77](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Utils/messages.ts#L77)

Uses a regex to test whether the string contains a URL, and returns the URL if it does.

## Parameters

### text

`string`

eg. hello https://google.com

## Returns

`undefined` \| `string`

the URL, eg. https://google.com
