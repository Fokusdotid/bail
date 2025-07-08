# Function: readAndEmitEventStream()

> **readAndEmitEventStream**(`filename`, `delayIntervalMs`): `object`

Defined in: [src/Utils/baileys-event-stream.ts:36](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/src/Utils/baileys-event-stream.ts#L36)

Read event file and emit events from there

## Parameters

### filename

`string`

filename containing event data

### delayIntervalMs

`number` = `0`

delay between each event emit

## Returns

`object`

### ev

> **ev**: [`BaileysEventEmitter`](../interfaces/BaileysEventEmitter.md)

### task

> **task**: `Promise`\<`void`\>
