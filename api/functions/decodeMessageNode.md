# Function: decodeMessageNode()

> **decodeMessageNode**(`stanza`, `meId`, `meLid`): `object`

Defined in: [src/Utils/decode-wa-message.ts:50](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/src/Utils/decode-wa-message.ts#L50)

Decode the received node as a message.

## Parameters

### stanza

[`BinaryNode`](../type-aliases/BinaryNode.md)

### meId

`string`

### meLid

`string`

## Returns

`object`

### author

> **author**: `string`

### fullMessage

> **fullMessage**: [`WAMessage`](../type-aliases/WAMessage.md)

### sender

> **sender**: `string`

## Note

this will only parse the message, not decrypt it
