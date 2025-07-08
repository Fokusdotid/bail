# Function: hkdf()

> **hkdf**(`buffer`, `expandedLength`, `info`): `Promise`\<`Buffer`\<`ArrayBufferLike`\>\>

Defined in: [src/Utils/crypto.ts:126](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Utils/crypto.ts#L126)

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
