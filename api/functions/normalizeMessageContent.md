# Function: normalizeMessageContent()

> **normalizeMessageContent**(`content`): `undefined` \| [`IMessage`](../namespaces/proto/interfaces/IMessage.md)

Defined in: [src/Utils/messages.ts:670](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/src/Utils/messages.ts#L670)

Normalizes ephemeral, view once messages to regular message content
Eg. image messages in ephemeral messages, in view once messages etc.

## Parameters

### content

`undefined` | `null` | [`IMessage`](../namespaces/proto/interfaces/IMessage.md)

## Returns

`undefined` \| [`IMessage`](../namespaces/proto/interfaces/IMessage.md)
