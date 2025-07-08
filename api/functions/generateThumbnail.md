# Function: generateThumbnail()

> **generateThumbnail**(`file`, `mediaType`, `options`): `Promise`\<\{ `originalImageDimensions`: `undefined` \| \{ `height`: `number`; `width`: `number`; \}; `thumbnail`: `undefined` \| `string`; \}\>

Defined in: [src/Utils/messages-media.ts:325](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/src/Utils/messages-media.ts#L325)

generates a thumbnail for a given media, if required

## Parameters

### file

`string`

### mediaType

`"image"` | `"video"`

### options

#### logger?

`ILogger`

## Returns

`Promise`\<\{ `originalImageDimensions`: `undefined` \| \{ `height`: `number`; `width`: `number`; \}; `thumbnail`: `undefined` \| `string`; \}\>
