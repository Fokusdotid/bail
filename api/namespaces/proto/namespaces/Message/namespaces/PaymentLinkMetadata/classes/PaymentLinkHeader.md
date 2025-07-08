# Class: PaymentLinkHeader

Defined in: [WAProto/index.d.ts:29146](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29146)

Represents a PaymentLinkHeader.

## Implements

- [`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md)

## Constructors

### new PaymentLinkHeader()

> **new PaymentLinkHeader**(`properties`?): [`PaymentLinkHeader`](PaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:29152](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29152)

Constructs a new PaymentLinkHeader.

#### Parameters

##### properties?

[`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md)

Properties to set

#### Returns

[`PaymentLinkHeader`](PaymentLinkHeader.md)

## Properties

### headerType?

> `optional` **headerType**: `null` \| [`PaymentLinkHeaderType`](../namespaces/PaymentLinkHeader/enumerations/PaymentLinkHeaderType.md)

Defined in: [WAProto/index.d.ts:29155](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29155)

PaymentLinkHeader headerType.

#### Implementation of

[`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md).[`headerType`](../interfaces/IPaymentLinkHeader.md#headertype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29225](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29225)

Converts this PaymentLinkHeader to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PaymentLinkHeader`](PaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:29162](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29162)

Creates a new PaymentLinkHeader instance using the specified properties.

#### Parameters

##### properties?

[`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md)

Properties to set

#### Returns

[`PaymentLinkHeader`](PaymentLinkHeader.md)

PaymentLinkHeader instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PaymentLinkHeader`](PaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:29188](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29188)

Decodes a PaymentLinkHeader message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PaymentLinkHeader`](PaymentLinkHeader.md)

PaymentLinkHeader

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PaymentLinkHeader`](PaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:29197](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29197)

Decodes a PaymentLinkHeader message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PaymentLinkHeader`](PaymentLinkHeader.md)

PaymentLinkHeader

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29170](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29170)

Encodes the specified PaymentLinkHeader message. Does not implicitly [verify](PaymentLinkHeader.md#verify) messages.

#### Parameters

##### message

[`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md)

PaymentLinkHeader message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29178](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29178)

Encodes the specified PaymentLinkHeader message, length delimited. Does not implicitly [verify](PaymentLinkHeader.md#verify) messages.

#### Parameters

##### message

[`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md)

PaymentLinkHeader message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PaymentLinkHeader`](PaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:29211](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29211)

Creates a PaymentLinkHeader message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PaymentLinkHeader`](PaymentLinkHeader.md)

PaymentLinkHeader

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:29232](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29232)

Gets the default type url for PaymentLinkHeader

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

Defined in: [WAProto/index.d.ts:29219](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29219)

Creates a plain object from a PaymentLinkHeader message. Also converts values to other types if specified.

#### Parameters

##### message

[`PaymentLinkHeader`](PaymentLinkHeader.md)

PaymentLinkHeader

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29204](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L29204)

Verifies a PaymentLinkHeader message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
