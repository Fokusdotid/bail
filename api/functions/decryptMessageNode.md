# Function: decryptMessageNode()

> **decryptMessageNode**(`stanza`, `meId`, `meLid`, `repository`, `logger`): `object`

Defined in: [src/Utils/decode-wa-message.ts:139](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/src/Utils/decode-wa-message.ts#L139)

## Parameters

### stanza

[`BinaryNode`](../type-aliases/BinaryNode.md)

### meId

`string`

### meLid

`string`

### repository

[`SignalRepository`](../type-aliases/SignalRepository.md)

### logger

`ILogger`

## Returns

`object`

### author

> **author**: `string`

### category

> **category**: `string` = `stanza.attrs.category`

### fullMessage

> **fullMessage**: [`WAMessage`](../type-aliases/WAMessage.md)

### decrypt()

#### Returns

`Promise`\<`void`\>
