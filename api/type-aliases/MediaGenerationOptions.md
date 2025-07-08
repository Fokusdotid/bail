# Type Alias: MediaGenerationOptions

> **MediaGenerationOptions**: `object`

Defined in: [src/Types/Message.ts:279](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/src/Types/Message.ts#L279)

## Type declaration

### backgroundColor?

> `optional` **backgroundColor**: `string`

### font?

> `optional` **font**: `number`

### logger?

> `optional` **logger**: `ILogger`

### mediaCache?

> `optional` **mediaCache**: [`CacheStore`](CacheStore.md)

cache media so it does not have to be uploaded again

### mediaTypeOverride?

> `optional` **mediaTypeOverride**: [`MediaType`](MediaType.md)

### mediaUploadTimeoutMs?

> `optional` **mediaUploadTimeoutMs**: `number`

### options?

> `optional` **options**: `AxiosRequestConfig`

### upload

> **upload**: [`WAMediaUploadFunction`](WAMediaUploadFunction.md)
