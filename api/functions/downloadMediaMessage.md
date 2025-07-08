# Function: downloadMediaMessage()

> **downloadMediaMessage**\<`Type`\>(`message`, `type`, `options`, `ctx`?): `Promise`\<`Type` *extends* `"buffer"` ? `Buffer`\<`ArrayBufferLike`\> : `Transform`\>

Defined in: [src/Utils/messages.ts:878](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/src/Utils/messages.ts#L878)

Downloads the given message. Throws an error if it's not a media message

## Type Parameters

• **Type** *extends* `"stream"` \| `"buffer"`

## Parameters

### message

[`WAMessage`](../type-aliases/WAMessage.md)

### type

`Type`

### options

[`MediaDownloadOptions`](../type-aliases/MediaDownloadOptions.md)

### ctx?

`DownloadMediaMessageContext`

## Returns

`Promise`\<`Type` *extends* `"buffer"` ? `Buffer`\<`ArrayBufferLike`\> : `Transform`\>
