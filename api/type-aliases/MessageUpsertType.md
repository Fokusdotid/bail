# Type Alias: MessageUpsertType

> **MessageUpsertType**: `"append"` \| `"notify"`

Defined in: [src/Types/Message.ts:306](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Types/Message.ts#L306)

Type of message upsert
1. notify => notify the user, this message was just received
2. append => append the message to the chat history, no notification required
