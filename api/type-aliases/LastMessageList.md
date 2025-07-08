# Type Alias: LastMessageList

> **LastMessageList**: [`MinimalMessage`](MinimalMessage.md)[] \| [`ISyncActionMessageRange`](../namespaces/proto/namespaces/SyncActionValue/interfaces/ISyncActionMessageRange.md)

Defined in: [src/Types/Chat.ts:82](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/src/Types/Chat.ts#L82)

the last messages in a chat, sorted reverse-chronologically. That is, the latest message should be first in the chat
for MD modifications, the last message in the array (i.e. the earlist message) must be the last message recv in the chat
