# Function: makeCacheableSignalKeyStore()

> **makeCacheableSignalKeyStore**(`store`, `logger`?, `_cache`?): [`SignalKeyStore`](../type-aliases/SignalKeyStore.md)

Defined in: [src/Utils/auth-utils.ts:23](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/src/Utils/auth-utils.ts#L23)

Adds caching capability to a SignalKeyStore

## Parameters

### store

[`SignalKeyStore`](../type-aliases/SignalKeyStore.md)

the store to add caching to

### logger?

`ILogger`

to log trace events

### \_cache?

[`CacheStore`](../type-aliases/CacheStore.md)

cache store to use

## Returns

[`SignalKeyStore`](../type-aliases/SignalKeyStore.md)
