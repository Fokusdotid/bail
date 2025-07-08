# Function: generateOrGetPreKeys()

> **generateOrGetPreKeys**(`creds`, `range`): `object`

Defined in: [src/Utils/signal.ts:43](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/src/Utils/signal.ts#L43)

## Parameters

### creds

[`AuthenticationCreds`](../type-aliases/AuthenticationCreds.md)

### range

`number`

## Returns

`object`

### lastPreKeyId

> **lastPreKeyId**: `number`

### newPreKeys

> **newPreKeys**: `object`

#### Index Signature

\[`id`: `number`\]: [`KeyPair`](../type-aliases/KeyPair.md)

### preKeysRange

> **preKeysRange**: readonly \[`number`, `number`\]
