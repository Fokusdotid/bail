# Function: getStream()

> **getStream**(`item`, `opts`?): `Promise`\<\{ `stream`: `Readable`; `type`: `"buffer"`; \} \| \{ `stream`: `Readable`; `type`: `"readable"`; \} \| \{ `stream`: `Readable`; `type`: `"remote"`; \} \| \{ `stream`: `ReadStream`; `type`: `"file"`; \}\>

Defined in: [src/Utils/messages-media.ts:302](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Utils/messages-media.ts#L302)

## Parameters

### item

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

### opts?

`AxiosRequestConfig`\<`any`\>

## Returns

`Promise`\<\{ `stream`: `Readable`; `type`: `"buffer"`; \} \| \{ `stream`: `Readable`; `type`: `"readable"`; \} \| \{ `stream`: `Readable`; `type`: `"remote"`; \} \| \{ `stream`: `ReadStream`; `type`: `"file"`; \}\>
