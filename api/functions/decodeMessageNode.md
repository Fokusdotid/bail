# Function: decodeMessageNode()

> **decodeMessageNode**(`stanza`, `meId`, `meLid`): `object`

Defined in: [src/Utils/decode-wa-message.ts:50](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Utils/decode-wa-message.ts#L50)

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
