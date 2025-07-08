# Function: hkdf()

> **hkdf**(`buffer`, `expandedLength`, `info`): `Promise`\<`Buffer`\<`ArrayBufferLike`\>\>

Defined in: [src/Utils/crypto.ts:126](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/src/Utils/crypto.ts#L126)

## Parameters

### buffer

`Uint8Array`\<`ArrayBufferLike`\> | `Buffer`\<`ArrayBufferLike`\>

### expandedLength

`number`

### info

#### info?

`string`

#### salt?

`Buffer`\<`ArrayBufferLike`\>

## Returns

`Promise`\<`Buffer`\<`ArrayBufferLike`\>\>
