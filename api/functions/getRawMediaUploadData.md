# Function: getRawMediaUploadData()

> **getRawMediaUploadData**(`media`, `mediaType`, `logger`?): `Promise`\<\{ `fileLength`: `number`; `filePath`: `string`; `fileSha256`: `Buffer`\<`ArrayBufferLike`\>; \}\>

Defined in: [src/Utils/messages-media.ts:53](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Utils/messages-media.ts#L53)

## Parameters

### media

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

### mediaType

`"ppic"` | `"product"` | `"image"` | `"video"` | `"sticker"` | `"thumbnail-document"` | `"audio"` | `"thumbnail-image"` | `"thumbnail-video"` | `"thumbnail-link"` | `"gif"` | `"md-app-state"` | `"md-msg-hist"` | `"document"` | `"ptt"` | `"product-catalog-image"` | `"payment-bg-image"` | `"ptv"`

### logger?

`ILogger`

## Returns

`Promise`\<\{ `fileLength`: `number`; `filePath`: `string`; `fileSha256`: `Buffer`\<`ArrayBufferLike`\>; \}\>
