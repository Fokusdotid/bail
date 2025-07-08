# Function: processHistoryMessage()

> **processHistoryMessage**(`item`): `object`

Defined in: [src/Utils/history.ts:29](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/src/Utils/history.ts#L29)

## Parameters

### item

[`IHistorySync`](../namespaces/proto/interfaces/IHistorySync.md)

## Returns

`object`

### chats

> **chats**: [`Chat`](../type-aliases/Chat.md)[]

### contacts

> **contacts**: [`Contact`](../interfaces/Contact.md)[]

### messages

> **messages**: [`IWebMessageInfo`](../namespaces/proto/interfaces/IWebMessageInfo.md)[]

### progress

> **progress**: `undefined` \| `null` \| `number` = `item.progress`

### syncType

> **syncType**: [`HistorySyncType`](../namespaces/proto/namespaces/HistorySync/enumerations/HistorySyncType.md) = `item.syncType`
