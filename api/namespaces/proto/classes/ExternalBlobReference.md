# Class: ExternalBlobReference

Defined in: [WAProto/index.d.ts:14677](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14677)

Represents an ExternalBlobReference.

## Implements

- [`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

## Constructors

### new ExternalBlobReference()

> **new ExternalBlobReference**(`properties`?): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:14683](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14683)

Constructs a new ExternalBlobReference.

#### Parameters

##### properties?

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

Properties to set

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

## Properties

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:14689](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14689)

ExternalBlobReference directPath.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`directPath`](../interfaces/IExternalBlobReference.md#directpath)

***

### fileEncSha256?

> `optional` **fileEncSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:14701](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14701)

ExternalBlobReference fileEncSha256.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`fileEncSha256`](../interfaces/IExternalBlobReference.md#fileencsha256)

***

### fileSha256?

> `optional` **fileSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:14698](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14698)

ExternalBlobReference fileSha256.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`fileSha256`](../interfaces/IExternalBlobReference.md#filesha256)

***

### fileSizeBytes?

> `optional` **fileSizeBytes**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:14695](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14695)

ExternalBlobReference fileSizeBytes.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`fileSizeBytes`](../interfaces/IExternalBlobReference.md#filesizebytes)

***

### handle?

> `optional` **handle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:14692](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14692)

ExternalBlobReference handle.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`handle`](../interfaces/IExternalBlobReference.md#handle)

***

### mediaKey?

> `optional` **mediaKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:14686](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14686)

ExternalBlobReference mediaKey.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`mediaKey`](../interfaces/IExternalBlobReference.md#mediakey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14771](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14771)

Converts this ExternalBlobReference to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:14708](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14708)

Creates a new ExternalBlobReference instance using the specified properties.

#### Parameters

##### properties?

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

Properties to set

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

ExternalBlobReference instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:14734](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14734)

Decodes an ExternalBlobReference message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

ExternalBlobReference

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:14743](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14743)

Decodes an ExternalBlobReference message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

ExternalBlobReference

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14716](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14716)

Encodes the specified ExternalBlobReference message. Does not implicitly [verify](ExternalBlobReference.md#verify) messages.

#### Parameters

##### message

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

ExternalBlobReference message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14724](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14724)

Encodes the specified ExternalBlobReference message, length delimited. Does not implicitly [verify](ExternalBlobReference.md#verify) messages.

#### Parameters

##### message

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

ExternalBlobReference message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:14757](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14757)

Creates an ExternalBlobReference message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

ExternalBlobReference

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:14778](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14778)

Gets the default type url for ExternalBlobReference

#### Parameters

##### typeUrlPrefix?

`string`

your custom typeUrlPrefix(default "type.googleapis.com")

#### Returns

`string`

The default type url

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:14765](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14765)

Creates a plain object from an ExternalBlobReference message. Also converts values to other types if specified.

#### Parameters

##### message

[`ExternalBlobReference`](ExternalBlobReference.md)

ExternalBlobReference

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14750](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L14750)

Verifies an ExternalBlobReference message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
