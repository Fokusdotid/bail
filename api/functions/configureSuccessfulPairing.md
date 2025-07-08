# Function: configureSuccessfulPairing()

> **configureSuccessfulPairing**(`stanza`, `__namedParameters`): `object`

Defined in: [src/Utils/validate-connection.ts:110](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/src/Utils/validate-connection.ts#L110)

## Parameters

### stanza

[`BinaryNode`](../type-aliases/BinaryNode.md)

### \_\_namedParameters

`Pick`\<[`AuthenticationCreds`](../type-aliases/AuthenticationCreds.md), `"signedIdentityKey"` \| `"advSecretKey"` \| `"signalIdentities"`\>

## Returns

`object`

### creds

> **creds**: `Partial`\<[`AuthenticationCreds`](../type-aliases/AuthenticationCreds.md)\> = `authUpdate`

### reply

> **reply**: [`BinaryNode`](../type-aliases/BinaryNode.md)
