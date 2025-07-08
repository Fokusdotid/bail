# Class: PrimaryFeature

Defined in: [WAProto/index.d.ts:47680](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47680)

Represents a PrimaryFeature.

## Implements

- [`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

## Constructors

### new PrimaryFeature()

> **new PrimaryFeature**(`properties`?): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:47686](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47686)

Constructs a new PrimaryFeature.

#### Parameters

##### properties?

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

Properties to set

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

## Properties

### flags

> **flags**: `string`[]

Defined in: [WAProto/index.d.ts:47689](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47689)

PrimaryFeature flags.

#### Implementation of

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md).[`flags`](../interfaces/IPrimaryFeature.md#flags)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:47759](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47759)

Converts this PrimaryFeature to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:47696](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47696)

Creates a new PrimaryFeature instance using the specified properties.

#### Parameters

##### properties?

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

Properties to set

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

PrimaryFeature instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:47722](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47722)

Decodes a PrimaryFeature message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

PrimaryFeature

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:47731](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47731)

Decodes a PrimaryFeature message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

PrimaryFeature

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47704](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47704)

Encodes the specified PrimaryFeature message. Does not implicitly [verify](PrimaryFeature.md#verify) messages.

#### Parameters

##### message

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

PrimaryFeature message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47712](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47712)

Encodes the specified PrimaryFeature message, length delimited. Does not implicitly [verify](PrimaryFeature.md#verify) messages.

#### Parameters

##### message

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

PrimaryFeature message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:47745](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47745)

Creates a PrimaryFeature message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

PrimaryFeature

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:47766](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47766)

Gets the default type url for PrimaryFeature

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

Defined in: [WAProto/index.d.ts:47753](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47753)

Creates a plain object from a PrimaryFeature message. Also converts values to other types if specified.

#### Parameters

##### message

[`PrimaryFeature`](PrimaryFeature.md)

PrimaryFeature

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:47738](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L47738)

Verifies a PrimaryFeature message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
