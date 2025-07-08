# Class: Citation

Defined in: [WAProto/index.d.ts:8775](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8775)

Represents a Citation.

## Implements

- [`ICitation`](../interfaces/ICitation.md)

## Constructors

### new Citation()

> **new Citation**(`properties`?): [`Citation`](Citation.md)

Defined in: [WAProto/index.d.ts:8781](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8781)

Constructs a new Citation.

#### Parameters

##### properties?

[`ICitation`](../interfaces/ICitation.md)

Properties to set

#### Returns

[`Citation`](Citation.md)

## Properties

### cmsId

> **cmsId**: `string`

Defined in: [WAProto/index.d.ts:8790](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8790)

Citation cmsId.

#### Implementation of

[`ICitation`](../interfaces/ICitation.md).[`cmsId`](../interfaces/ICitation.md#cmsid)

***

### imageUrl

> **imageUrl**: `string`

Defined in: [WAProto/index.d.ts:8793](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8793)

Citation imageUrl.

#### Implementation of

[`ICitation`](../interfaces/ICitation.md).[`imageUrl`](../interfaces/ICitation.md#imageurl)

***

### subtitle

> **subtitle**: `string`

Defined in: [WAProto/index.d.ts:8787](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8787)

Citation subtitle.

#### Implementation of

[`ICitation`](../interfaces/ICitation.md).[`subtitle`](../interfaces/ICitation.md#subtitle)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:8784](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8784)

Citation title.

#### Implementation of

[`ICitation`](../interfaces/ICitation.md).[`title`](../interfaces/ICitation.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8863](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8863)

Converts this Citation to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Citation`](Citation.md)

Defined in: [WAProto/index.d.ts:8800](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8800)

Creates a new Citation instance using the specified properties.

#### Parameters

##### properties?

[`ICitation`](../interfaces/ICitation.md)

Properties to set

#### Returns

[`Citation`](Citation.md)

Citation instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Citation`](Citation.md)

Defined in: [WAProto/index.d.ts:8826](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8826)

Decodes a Citation message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Citation`](Citation.md)

Citation

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Citation`](Citation.md)

Defined in: [WAProto/index.d.ts:8835](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8835)

Decodes a Citation message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Citation`](Citation.md)

Citation

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8808](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8808)

Encodes the specified Citation message. Does not implicitly [verify](Citation.md#verify) messages.

#### Parameters

##### message

[`ICitation`](../interfaces/ICitation.md)

Citation message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8816](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8816)

Encodes the specified Citation message, length delimited. Does not implicitly [verify](Citation.md#verify) messages.

#### Parameters

##### message

[`ICitation`](../interfaces/ICitation.md)

Citation message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Citation`](Citation.md)

Defined in: [WAProto/index.d.ts:8849](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8849)

Creates a Citation message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Citation`](Citation.md)

Citation

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8870](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8870)

Gets the default type url for Citation

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

Defined in: [WAProto/index.d.ts:8857](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8857)

Creates a plain object from a Citation message. Also converts values to other types if specified.

#### Parameters

##### message

[`Citation`](Citation.md)

Citation

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8842](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L8842)

Verifies a Citation message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
