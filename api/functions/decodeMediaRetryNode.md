# Function: decodeMediaRetryNode()

> **decodeMediaRetryNode**(`node`): `object`

Defined in: [src/Utils/messages-media.ts:743](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/src/Utils/messages-media.ts#L743)

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
