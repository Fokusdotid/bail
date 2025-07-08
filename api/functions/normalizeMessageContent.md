# Function: normalizeMessageContent()

> **normalizeMessageContent**(`content`): `undefined` \| [`IMessage`](../namespaces/proto/interfaces/IMessage.md)

Defined in: [src/Utils/messages.ts:670](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/src/Utils/messages.ts#L670)

Normalizes ephemeral, view once messages to regular message content
Eg. image messages in ephemeral messages, in view once messages etc.

## Parameters

### content

`undefined` | `null` | [`IMessage`](../namespaces/proto/interfaces/IMessage.md)

## Returns

`undefined` \| [`IMessage`](../namespaces/proto/interfaces/IMessage.md)
