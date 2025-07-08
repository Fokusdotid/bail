# Function: encryptedStream()

> **encryptedStream**(`media`, `mediaType`, `__namedParameters`): `Promise`\<\{ `encFilePath`: `string`; `fileEncSha256`: `Buffer`\<`ArrayBufferLike`\>; `fileLength`: `number`; `fileSha256`: `Buffer`\<`ArrayBufferLike`\>; `mac`: `Buffer`\<`ArrayBuffer`\>; `mediaKey`: `Buffer`\<`ArrayBufferLike`\>; `originalFilePath`: `undefined` \| `string`; \}\>

Defined in: [src/Utils/messages-media.ts:372](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Utils/messages-media.ts#L372)

## Parameters

### media

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

### mediaType

`"ppic"` | `"product"` | `"image"` | `"video"` | `"sticker"` | `"thumbnail-document"` | `"audio"` | `"thumbnail-image"` | `"thumbnail-video"` | `"thumbnail-link"` | `"gif"` | `"md-app-state"` | `"md-msg-hist"` | `"document"` | `"ptt"` | `"product-catalog-image"` | `"payment-bg-image"` | `"ptv"`

### \_\_namedParameters

`EncryptedStreamOptions` = `{}`

## Returns

`Promise`\<\{ `encFilePath`: `string`; `fileEncSha256`: `Buffer`\<`ArrayBufferLike`\>; `fileLength`: `number`; `fileSha256`: `Buffer`\<`ArrayBufferLike`\>; `mac`: `Buffer`\<`ArrayBuffer`\>; `mediaKey`: `Buffer`\<`ArrayBufferLike`\>; `originalFilePath`: `undefined` \| `string`; \}\>
