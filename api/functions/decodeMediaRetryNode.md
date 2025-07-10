# Function: decodeMediaRetryNode()

> **decodeMediaRetryNode**(`node`): `object`

Defined in: [src/Utils/messages-media.ts:742](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Utils/messages-media.ts#L742)

## Parameters

### node

[`BinaryNode`](../type-aliases/BinaryNode.md)

## Returns

`object`

### error?

> `optional` **error**: `Boom`\<`any`\>

### key

> **key**: [`WAMessageKey`](../type-aliases/WAMessageKey.md)

### media?

> `optional` **media**: `object`

#### media.ciphertext

> **ciphertext**: `Uint8Array`

#### media.iv

> **iv**: `Uint8Array`
