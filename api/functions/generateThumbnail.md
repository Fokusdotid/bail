# Function: generateThumbnail()

> **generateThumbnail**(`file`, `mediaType`, `options`): `Promise`\<\{ `originalImageDimensions`: `undefined` \| \{ `height`: `number`; `width`: `number`; \}; `thumbnail`: `undefined` \| `string`; \}\>

Defined in: [src/Utils/messages-media.ts:326](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/src/Utils/messages-media.ts#L326)

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
