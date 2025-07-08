# Function: hkdf()

> **hkdf**(`buffer`, `expandedLength`, `info`): `Promise`\<`Buffer`\<`ArrayBufferLike`\>\>

Defined in: [src/Utils/crypto.ts:126](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/src/Utils/crypto.ts#L126)

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
