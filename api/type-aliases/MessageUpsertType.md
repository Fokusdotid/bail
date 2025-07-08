# Type Alias: MessageUpsertType

> **MessageUpsertType**: `"append"` \| `"notify"`

Defined in: [src/Types/Message.ts:354](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/src/Types/Message.ts#L354)

Type of message upsert
1. notify => notify the user, this message was just received
2. append => append the message to the chat history, no notification required
