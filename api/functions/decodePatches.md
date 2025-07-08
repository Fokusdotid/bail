# Function: decodePatches()

> **decodePatches**(`name`, `syncds`, `initial`, `getAppStateSyncKey`, `options`, `minimumVersionNumber`?, `logger`?, `validateMacs`?): `Promise`\<\{ `mutationMap`: [`ChatMutationMap`](../type-aliases/ChatMutationMap.md); `state`: [`LTHashState`](../type-aliases/LTHashState.md); \}\>

Defined in: [src/Utils/chat-utils.ts:424](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Utils/chat-utils.ts#L424)

## Parameters

### name

`"critical_unblock_low"` | `"regular_high"` | `"regular_low"` | `"critical_block"` | `"regular"`

### syncds

[`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]

### initial

[`LTHashState`](../type-aliases/LTHashState.md)

### getAppStateSyncKey

`FetchAppStateSyncKey`

### options

`AxiosRequestConfig`\<\{\}\>

### minimumVersionNumber?

`number`

### logger?

`ILogger`

### validateMacs?

`boolean` = `true`

## Returns

`Promise`\<\{ `mutationMap`: [`ChatMutationMap`](../type-aliases/ChatMutationMap.md); `state`: [`LTHashState`](../type-aliases/LTHashState.md); \}\>
