# Type Alias: MessageUpsertType

> **MessageUpsertType**: `"append"` \| `"notify"`

Defined in: [src/Types/Message.ts:306](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/src/Types/Message.ts#L306)

Type of message upsert
1. notify => notify the user, this message was just received
2. append => append the message to the chat history, no notification required
