# Type Alias: MediaGenerationOptions

> **MediaGenerationOptions**: `object`

Defined in: [src/Types/Message.ts:327](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/src/Types/Message.ts#L327)

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
