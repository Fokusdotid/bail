# Function: getMediaKeys()

> **getMediaKeys**(`buffer`, `mediaType`): `Promise`\<[`MediaDecryptionKeyInfo`](../type-aliases/MediaDecryptionKeyInfo.md)\>

Defined in: [src/Utils/messages-media.ts:96](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/src/Utils/messages-media.ts#L96)

generates all the keys required to encrypt/decrypt & sign a media message

## Parameters

### buffer

`undefined` | `null` | `string` | `Uint8Array`\<`ArrayBufferLike`\>

### mediaType

`"ppic"` | `"product"` | `"image"` | `"video"` | `"sticker"` | `"thumbnail-document"` | `"audio"` | `"thumbnail-image"` | `"thumbnail-video"` | `"thumbnail-link"` | `"gif"` | `"md-app-state"` | `"md-msg-hist"` | `"document"` | `"ptt"` | `"product-catalog-image"` | `"payment-bg-image"` | `"ptv"`

## Returns

`Promise`\<[`MediaDecryptionKeyInfo`](../type-aliases/MediaDecryptionKeyInfo.md)\>
