# Function: decodeSyncdSnapshot()

> **decodeSyncdSnapshot**(`name`, `snapshot`, `getAppStateSyncKey`, `minimumVersionNumber`, `validateMacs`): `Promise`\<\{ `mutationMap`: [`ChatMutationMap`](../type-aliases/ChatMutationMap.md); `state`: [`LTHashState`](../type-aliases/LTHashState.md); \}\>

Defined in: [src/Utils/chat-utils.ts:376](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/src/Utils/chat-utils.ts#L376)

## Parameters

### name

`"critical_unblock_low"` | `"regular_high"` | `"regular_low"` | `"critical_block"` | `"regular"`

### snapshot

[`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md)

### getAppStateSyncKey

`FetchAppStateSyncKey`

### minimumVersionNumber

`undefined` | `number`

### validateMacs

`boolean` = `true`

## Returns

`Promise`\<\{ `mutationMap`: [`ChatMutationMap`](../type-aliases/ChatMutationMap.md); `state`: [`LTHashState`](../type-aliases/LTHashState.md); \}\>
