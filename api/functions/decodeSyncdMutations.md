# Function: decodeSyncdMutations()

> **decodeSyncdMutations**(`msgMutations`, `initialState`, `getAppStateSyncKey`, `onMutation`, `validateMacs`): `Promise`\<\{ `hash`: `Buffer`\<`any`\>; `indexValueMap`: \{\}; \}\>

Defined in: [src/Utils/chat-utils.ts:209](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/src/Utils/chat-utils.ts#L209)

## Parameters

### msgMutations

([`ISyncdMutation`](../namespaces/proto/interfaces/ISyncdMutation.md) \| [`ISyncdRecord`](../namespaces/proto/interfaces/ISyncdRecord.md))[]

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
