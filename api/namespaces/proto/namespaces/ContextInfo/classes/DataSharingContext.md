# Class: DataSharingContext

Defined in: [WAProto/index.d.ts:11348](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11348)

Represents a DataSharingContext.

## Implements

- [`IDataSharingContext`](../interfaces/IDataSharingContext.md)

## Constructors

### new DataSharingContext()

> **new DataSharingContext**(`properties`?): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:11354](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11354)

Constructs a new DataSharingContext.

#### Parameters

##### properties?

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

Properties to set

#### Returns

[`DataSharingContext`](DataSharingContext.md)

## Properties

### encryptedSignalTokenConsented?

> `optional` **encryptedSignalTokenConsented**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11360](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11360)

DataSharingContext encryptedSignalTokenConsented.

#### Implementation of

[`IDataSharingContext`](../interfaces/IDataSharingContext.md).[`encryptedSignalTokenConsented`](../interfaces/IDataSharingContext.md#encryptedsignaltokenconsented)

***

### parameters

> **parameters**: [`IParameters`](../namespaces/DataSharingContext/interfaces/IParameters.md)[]

Defined in: [WAProto/index.d.ts:11363](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11363)

DataSharingContext parameters.

#### Implementation of

[`IDataSharingContext`](../interfaces/IDataSharingContext.md).[`parameters`](../interfaces/IDataSharingContext.md#parameters)

***

### showMmDisclosure?

> `optional` **showMmDisclosure**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11357](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11357)

DataSharingContext showMmDisclosure.

#### Implementation of

[`IDataSharingContext`](../interfaces/IDataSharingContext.md).[`showMmDisclosure`](../interfaces/IDataSharingContext.md#showmmdisclosure)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11433](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11433)

Converts this DataSharingContext to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:11370](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11370)

Creates a new DataSharingContext instance using the specified properties.

#### Parameters

##### properties?

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

Properties to set

#### Returns

[`DataSharingContext`](DataSharingContext.md)

DataSharingContext instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:11396](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11396)

Decodes a DataSharingContext message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DataSharingContext`](DataSharingContext.md)

DataSharingContext

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:11405](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11405)

Decodes a DataSharingContext message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DataSharingContext`](DataSharingContext.md)

DataSharingContext

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11378](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11378)

Encodes the specified DataSharingContext message. Does not implicitly [verify](DataSharingContext.md#verify) messages.

#### Parameters

##### message

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

DataSharingContext message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11386](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11386)

Encodes the specified DataSharingContext message, length delimited. Does not implicitly [verify](DataSharingContext.md#verify) messages.

#### Parameters

##### message

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

DataSharingContext message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:11419](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11419)

Creates a DataSharingContext message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DataSharingContext`](DataSharingContext.md)

DataSharingContext

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11440](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11440)

Gets the default type url for DataSharingContext

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

Defined in: [WAProto/index.d.ts:11427](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11427)

Creates a plain object from a DataSharingContext message. Also converts values to other types if specified.

#### Parameters

##### message

[`DataSharingContext`](DataSharingContext.md)

DataSharingContext

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11412](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L11412)

Verifies a DataSharingContext message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
