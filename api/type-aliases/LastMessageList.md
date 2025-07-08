# Type Alias: LastMessageList

> **LastMessageList**: [`MinimalMessage`](MinimalMessage.md)[] \| [`ISyncActionMessageRange`](../namespaces/proto/namespaces/SyncActionValue/interfaces/ISyncActionMessageRange.md)

Defined in: [src/Types/Chat.ts:82](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/src/Types/Chat.ts#L82)

the last messages in a chat, sorted reverse-chronologically. That is, the latest message should be first in the chat
for MD modifications, the last message in the array (i.e. the earlist message) must be the last message recv in the chat
