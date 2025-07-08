# Function: decodeSyncdPatch()

> **decodeSyncdPatch**(`msg`, `name`, `initialState`, `getAppStateSyncKey`, `onMutation`, `validateMacs`): `Promise`\<\{ `hash`: `Buffer`\<`any`\>; `indexValueMap`: \{\}; \}\>

Defined in: [src/Utils/chat-utils.ts:274](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/src/Utils/chat-utils.ts#L274)

## Parameters

### msg

[`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)

### name

`"critical_unblock_low"` | `"regular_high"` | `"regular_low"` | `"critical_block"` | `"regular"`

### initialState

[`LTHashState`](../type-aliases/LTHashState.md)

### getAppStateSyncKey

`FetchAppStateSyncKey`

### onMutation

(`mutation`) => `void`

### validateMacs

`boolean`

## Returns

`Promise`\<\{ `hash`: `Buffer`\<`any`\>; `indexValueMap`: \{\}; \}\>
