# Function: normalizeMessageContent()

> **normalizeMessageContent**(`content`): `undefined` \| [`IMessage`](../namespaces/proto/interfaces/IMessage.md)

Defined in: [src/Utils/messages.ts:782](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Utils/messages.ts#L782)

Normalizes ephemeral, view once messages to regular message content
Eg. image messages in ephemeral messages, in view once messages etc.

## Parameters

### content

`undefined` | `null` | [`IMessage`](../namespaces/proto/interfaces/IMessage.md)

## Returns

`undefined` \| [`IMessage`](../namespaces/proto/interfaces/IMessage.md)
