# Function: assertMediaContent()

> **assertMediaContent**(`content`): [`IVideoMessage`](../namespaces/proto/namespaces/Message/interfaces/IVideoMessage.md) \| [`IImageMessage`](../namespaces/proto/namespaces/Message/interfaces/IImageMessage.md) \| [`IAudioMessage`](../namespaces/proto/namespaces/Message/interfaces/IAudioMessage.md) \| [`IDocumentMessage`](../namespaces/proto/namespaces/Message/interfaces/IDocumentMessage.md) \| [`IStickerMessage`](../namespaces/proto/namespaces/Message/interfaces/IStickerMessage.md)

Defined in: [src/Utils/messages.ts:1054](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Utils/messages.ts#L1054)

Checks whether the given message is a media message; if it is returns the inner content

## Parameters

### content

`undefined` | `null` | [`IMessage`](../namespaces/proto/interfaces/IMessage.md)

## Returns

[`IVideoMessage`](../namespaces/proto/namespaces/Message/interfaces/IVideoMessage.md) \| [`IImageMessage`](../namespaces/proto/namespaces/Message/interfaces/IImageMessage.md) \| [`IAudioMessage`](../namespaces/proto/namespaces/Message/interfaces/IAudioMessage.md) \| [`IDocumentMessage`](../namespaces/proto/namespaces/Message/interfaces/IDocumentMessage.md) \| [`IStickerMessage`](../namespaces/proto/namespaces/Message/interfaces/IStickerMessage.md)
