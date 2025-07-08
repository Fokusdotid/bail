# Function: hkdf()

> **hkdf**(`buffer`, `expandedLength`, `info`): `Promise`\<`Buffer`\<`ArrayBufferLike`\>\>

Defined in: [src/Utils/crypto.ts:126](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/src/Utils/crypto.ts#L126)

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
