# Class: CtwaContextLinkData

Defined in: [WAProto/index.d.ts:8658](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8658)

Represents a CtwaContextLinkData.

## Implements

- [`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

## Constructors

### new CtwaContextLinkData()

> **new CtwaContextLinkData**(`properties`?): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:8664](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8664)

Constructs a new CtwaContextLinkData.

#### Parameters

##### properties?

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

Properties to set

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

## Properties

### context?

> `optional` **context**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8667](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8667)

CtwaContextLinkData context.

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`context`](../interfaces/ICtwaContextLinkData.md#context)

***

### icebreaker?

> `optional` **icebreaker**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8673](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8673)

CtwaContextLinkData icebreaker.

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`icebreaker`](../interfaces/ICtwaContextLinkData.md#icebreaker)

***

### phone?

> `optional` **phone**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8676](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8676)

CtwaContextLinkData phone.

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`phone`](../interfaces/ICtwaContextLinkData.md#phone)

***

### sourceUrl?

> `optional` **sourceUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8670](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8670)

CtwaContextLinkData sourceUrl.

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`sourceUrl`](../interfaces/ICtwaContextLinkData.md#sourceurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8746](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8746)

Converts this CtwaContextLinkData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:8683](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8683)

Creates a new CtwaContextLinkData instance using the specified properties.

#### Parameters

##### properties?

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

Properties to set

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

CtwaContextLinkData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:8709](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8709)

Decodes a CtwaContextLinkData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

CtwaContextLinkData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:8718](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8718)

Decodes a CtwaContextLinkData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

CtwaContextLinkData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8691](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8691)

Encodes the specified CtwaContextLinkData message. Does not implicitly [verify](CtwaContextLinkData.md#verify) messages.

#### Parameters

##### message

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

CtwaContextLinkData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8699](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8699)

Encodes the specified CtwaContextLinkData message, length delimited. Does not implicitly [verify](CtwaContextLinkData.md#verify) messages.

#### Parameters

##### message

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

CtwaContextLinkData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:8732](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8732)

Creates a CtwaContextLinkData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

CtwaContextLinkData

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8753](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8753)

Gets the default type url for CtwaContextLinkData

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

Defined in: [WAProto/index.d.ts:8740](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8740)

Creates a plain object from a CtwaContextLinkData message. Also converts values to other types if specified.

#### Parameters

##### message

[`CtwaContextLinkData`](CtwaContextLinkData.md)

CtwaContextLinkData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8725](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8725)

Verifies a CtwaContextLinkData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
