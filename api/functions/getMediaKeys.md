# Function: getMediaKeys()

> **getMediaKeys**(`buffer`, `mediaType`): `Promise`\<[`MediaDecryptionKeyInfo`](../type-aliases/MediaDecryptionKeyInfo.md)\>

Defined in: [src/Utils/messages-media.ts:95](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Utils/messages-media.ts#L95)

generates all the keys required to encrypt/decrypt & sign a media message

## Parameters

### buffer

`undefined` | `null` | `string` | `Uint8Array`\<`ArrayBufferLike`\>

### mediaType

`"ppic"` | `"product"` | `"image"` | `"video"` | `"sticker"` | `"thumbnail-document"` | `"audio"` | `"thumbnail-image"` | `"thumbnail-video"` | `"thumbnail-link"` | `"gif"` | `"md-app-state"` | `"md-msg-hist"` | `"document"` | `"ptt"` | `"product-catalog-image"` | `"payment-bg-image"` | `"ptv"`

## Returns

`Promise`\<[`MediaDecryptionKeyInfo`](../type-aliases/MediaDecryptionKeyInfo.md)\>
