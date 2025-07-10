# Type Alias: MessageUpsertType

> **MessageUpsertType**: `"append"` \| `"notify"`

Defined in: [src/Types/Message.ts:354](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Message.ts#L354)

Type of message upsert
1. notify => notify the user, this message was just received
2. append => append the message to the chat history, no notification required
