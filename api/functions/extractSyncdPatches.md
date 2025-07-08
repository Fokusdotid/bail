# Function: extractSyncdPatches()

> **extractSyncdPatches**(`result`, `options`): `Promise`\<\{ `critical_block`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `critical_unblock_low`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular_high`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular_low`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; \}\>

Defined in: [src/Utils/chat-utils.ts:308](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/src/Utils/chat-utils.ts#L308)

## Parameters

### result

[`BinaryNode`](../type-aliases/BinaryNode.md)

### options

`AxiosRequestConfig`\<\{\}\>

## Returns

`Promise`\<\{ `critical_block`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `critical_unblock_low`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular_high`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular_low`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; \}\>
