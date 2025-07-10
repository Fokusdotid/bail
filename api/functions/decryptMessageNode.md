# Function: decryptMessageNode()

> **decryptMessageNode**(`stanza`, `meId`, `meLid`, `repository`, `logger`): `object`

Defined in: [src/Utils/decode-wa-message.ts:139](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Utils/decode-wa-message.ts#L139)

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
