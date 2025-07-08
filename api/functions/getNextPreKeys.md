# Function: getNextPreKeys()

> **getNextPreKeys**(`__namedParameters`, `count`): `Promise`\<\{ `preKeys`: \{\}; `update`: `Partial`\<[`AuthenticationCreds`](../type-aliases/AuthenticationCreds.md)\>; \}\>

Defined in: [src/Utils/signal.ts:153](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/src/Utils/signal.ts#L153)

get the next N keys for upload or processing

## Parameters

### \_\_namedParameters

[`AuthenticationState`](../type-aliases/AuthenticationState.md)

### count

`number`

number of pre-keys to get or generate

## Returns

`Promise`\<\{ `preKeys`: \{\}; `update`: `Partial`\<[`AuthenticationCreds`](../type-aliases/AuthenticationCreds.md)\>; \}\>
