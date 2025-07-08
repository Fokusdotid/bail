# Class: SyncActionData

Defined in: [WAProto/index.d.ts:43144](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43144)

Represents a SyncActionData.

## Implements

- [`ISyncActionData`](../interfaces/ISyncActionData.md)

## Constructors

### new SyncActionData()

> **new SyncActionData**(`properties`?): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:43150](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43150)

Constructs a new SyncActionData.

#### Parameters

##### properties?

[`ISyncActionData`](../interfaces/ISyncActionData.md)

Properties to set

#### Returns

[`SyncActionData`](SyncActionData.md)

## Properties

### index?

> `optional` **index**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:43153](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43153)

SyncActionData index.

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`index`](../interfaces/ISyncActionData.md#index)

***

### padding?

> `optional` **padding**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:43159](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43159)

SyncActionData padding.

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`padding`](../interfaces/ISyncActionData.md#padding)

***

### value?

> `optional` **value**: `null` \| [`ISyncActionValue`](../interfaces/ISyncActionValue.md)

Defined in: [WAProto/index.d.ts:43156](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43156)

SyncActionData value.

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`value`](../interfaces/ISyncActionData.md#value)

***

### version?

> `optional` **version**: `null` \| `number`

Defined in: [WAProto/index.d.ts:43162](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43162)

SyncActionData version.

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`version`](../interfaces/ISyncActionData.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:43232](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43232)

Converts this SyncActionData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:43169](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43169)

Creates a new SyncActionData instance using the specified properties.

#### Parameters

##### properties?

[`ISyncActionData`](../interfaces/ISyncActionData.md)

Properties to set

#### Returns

[`SyncActionData`](SyncActionData.md)

SyncActionData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:43195](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43195)

Decodes a SyncActionData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncActionData`](SyncActionData.md)

SyncActionData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:43204](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43204)

Decodes a SyncActionData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncActionData`](SyncActionData.md)

SyncActionData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:43177](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43177)

Encodes the specified SyncActionData message. Does not implicitly [verify](SyncActionData.md#verify) messages.

#### Parameters

##### message

[`ISyncActionData`](../interfaces/ISyncActionData.md)

SyncActionData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:43185](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43185)

Encodes the specified SyncActionData message, length delimited. Does not implicitly [verify](SyncActionData.md#verify) messages.

#### Parameters

##### message

[`ISyncActionData`](../interfaces/ISyncActionData.md)

SyncActionData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:43218](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43218)

Creates a SyncActionData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncActionData`](SyncActionData.md)

SyncActionData

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:43239](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43239)

Gets the default type url for SyncActionData

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

Defined in: [WAProto/index.d.ts:43226](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43226)

Creates a plain object from a SyncActionData message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncActionData`](SyncActionData.md)

SyncActionData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:43211](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L43211)

Verifies a SyncActionData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
