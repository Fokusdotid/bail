# Type Alias: MessageUpsertType

> **MessageUpsertType**: `"append"` \| `"notify"`

Defined in: [src/Types/Message.ts:306](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/src/Types/Message.ts#L306)

Type of message upsert
1. notify => notify the user, this message was just received
2. append => append the message to the chat history, no notification required
