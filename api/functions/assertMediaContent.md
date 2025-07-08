# Function: assertMediaContent()

> **assertMediaContent**(`content`): [`IVideoMessage`](../namespaces/proto/namespaces/Message/interfaces/IVideoMessage.md) \| [`IImageMessage`](../namespaces/proto/namespaces/Message/interfaces/IImageMessage.md) \| [`IAudioMessage`](../namespaces/proto/namespaces/Message/interfaces/IAudioMessage.md) \| [`IDocumentMessage`](../namespaces/proto/namespaces/Message/interfaces/IDocumentMessage.md) \| [`IStickerMessage`](../namespaces/proto/namespaces/Message/interfaces/IStickerMessage.md)

Defined in: [src/Utils/messages.ts:942](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/src/Utils/messages.ts#L942)

Checks whether the given message is a media message; if it is returns the inner content

## Parameters

### content

`undefined` | `null` | [`IMessage`](../namespaces/proto/interfaces/IMessage.md)

## Returns

[`IVideoMessage`](../namespaces/proto/namespaces/Message/interfaces/IVideoMessage.md) \| [`IImageMessage`](../namespaces/proto/namespaces/Message/interfaces/IImageMessage.md) \| [`IAudioMessage`](../namespaces/proto/namespaces/Message/interfaces/IAudioMessage.md) \| [`IDocumentMessage`](../namespaces/proto/namespaces/Message/interfaces/IDocumentMessage.md) \| [`IStickerMessage`](../namespaces/proto/namespaces/Message/interfaces/IStickerMessage.md)
