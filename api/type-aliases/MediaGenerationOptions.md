# Type Alias: MediaGenerationOptions

> **MediaGenerationOptions**: `object`

Defined in: [src/Types/Message.ts:279](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Types/Message.ts#L279)

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
