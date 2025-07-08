# Function: getRawMediaUploadData()

> **getRawMediaUploadData**(`media`, `mediaType`, `logger`?): `Promise`\<\{ `fileLength`: `number`; `filePath`: `string`; `fileSha256`: `Buffer`\<`ArrayBufferLike`\>; \}\>

Defined in: [src/Utils/messages-media.ts:54](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/src/Utils/messages-media.ts#L54)

## Parameters

### media

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

### mediaType

`"ppic"` | `"product"` | `"image"` | `"video"` | `"sticker"` | `"thumbnail-document"` | `"audio"` | `"thumbnail-image"` | `"thumbnail-video"` | `"thumbnail-link"` | `"gif"` | `"md-app-state"` | `"md-msg-hist"` | `"document"` | `"ptt"` | `"product-catalog-image"` | `"payment-bg-image"` | `"ptv"`

### logger?

`ILogger`

## Returns

`Promise`\<\{ `fileLength`: `number`; `filePath`: `string`; `fileSha256`: `Buffer`\<`ArrayBufferLike`\>; \}\>
