# Type Alias: SignalKeyStore

> **SignalKeyStore**: `object`

Defined in: [src/Types/Auth.ts:81](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Auth.ts#L81)

## Type declaration

### clear()?

clear all the data in the store

#### Returns

`Awaitable`\<`void`\>

### get()

#### Type Parameters

• **T** *extends* keyof [`SignalDataTypeMap`](SignalDataTypeMap.md)

#### Parameters

##### type

`T`

##### ids

`string`[]

#### Returns

`Awaitable`\<\{\}\>

### set()

#### Parameters

##### data

[`SignalDataSet`](SignalDataSet.md)

#### Returns

`Awaitable`\<`void`\>
