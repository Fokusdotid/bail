# Type Alias: MediaGenerationOptions

> **MediaGenerationOptions**: `object`

Defined in: [src/Types/Message.ts:327](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/src/Types/Message.ts#L327)

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
