# Type Alias: MessageUpsertType

> **MessageUpsertType**: `"append"` \| `"notify"`

Defined in: [src/Types/Message.ts:306](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/src/Types/Message.ts#L306)

Type of message upsert
1. notify => notify the user, this message was just received
2. append => append the message to the chat history, no notification required
