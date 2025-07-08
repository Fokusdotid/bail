# Function: getRawMediaUploadData()

> **getRawMediaUploadData**(`media`, `mediaType`, `logger`?): `Promise`\<\{ `fileLength`: `number`; `filePath`: `string`; `fileSha256`: `Buffer`\<`ArrayBufferLike`\>; \}\>

Defined in: [src/Utils/messages-media.ts:53](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/src/Utils/messages-media.ts#L53)

## Parameters

### media

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

### mediaType

`"ppic"` | `"product"` | `"image"` | `"video"` | `"sticker"` | `"thumbnail-document"` | `"audio"` | `"thumbnail-image"` | `"thumbnail-video"` | `"thumbnail-link"` | `"gif"` | `"md-app-state"` | `"md-msg-hist"` | `"document"` | `"ptt"` | `"product-catalog-image"` | `"payment-bg-image"` | `"ptv"`

### logger?

`ILogger`

## Returns

`Promise`\<\{ `fileLength`: `number`; `filePath`: `string`; `fileSha256`: `Buffer`\<`ArrayBufferLike`\>; \}\>
