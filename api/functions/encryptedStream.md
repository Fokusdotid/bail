# Function: encryptedStream()

> **encryptedStream**(`media`, `mediaType`, `__namedParameters`): `Promise`\<\{ `encFilePath`: `string`; `fileEncSha256`: `Buffer`\<`ArrayBufferLike`\>; `fileLength`: `number`; `fileSha256`: `Buffer`\<`ArrayBufferLike`\>; `mac`: `Buffer`\<`ArrayBuffer`\>; `mediaKey`: `Buffer`\<`ArrayBufferLike`\>; `originalFilePath`: `undefined` \| `string`; \}\>

Defined in: [src/Utils/messages-media.ts:374](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Utils/messages-media.ts#L374)

## Parameters

### media

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

### mediaType

`"ppic"` | `"product"` | `"image"` | `"video"` | `"sticker"` | `"thumbnail-document"` | `"audio"` | `"thumbnail-image"` | `"thumbnail-video"` | `"thumbnail-link"` | `"gif"` | `"md-app-state"` | `"md-msg-hist"` | `"document"` | `"ptt"` | `"product-catalog-image"` | `"payment-bg-image"` | `"ptv"`

### \_\_namedParameters

`EncryptedStreamOptions` = `{}`

## Returns

`Promise`\<\{ `encFilePath`: `string`; `fileEncSha256`: `Buffer`\<`ArrayBufferLike`\>; `fileLength`: `number`; `fileSha256`: `Buffer`\<`ArrayBufferLike`\>; `mac`: `Buffer`\<`ArrayBuffer`\>; `mediaKey`: `Buffer`\<`ArrayBufferLike`\>; `originalFilePath`: `undefined` \| `string`; \}\>
