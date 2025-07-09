# Class: CompanionMetaNonceFetchResponse

Defined in: [WAProto/index.d.ts:30271](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30271)

Represents a CompanionMetaNonceFetchResponse.

## Implements

- [`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md)

## Constructors

### new CompanionMetaNonceFetchResponse()

> **new CompanionMetaNonceFetchResponse**(`properties`?): [`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:30277](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30277)

Constructs a new CompanionMetaNonceFetchResponse.

#### Parameters

##### properties?

[`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md)

Properties to set

#### Returns

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

## Properties

### nonce?

> `optional` **nonce**: `null` \| `string`

Defined in: [WAProto/index.d.ts:30280](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30280)

CompanionMetaNonceFetchResponse nonce.

#### Implementation of

[`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md).[`nonce`](../interfaces/ICompanionMetaNonceFetchResponse.md#nonce)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30350](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30350)

Converts this CompanionMetaNonceFetchResponse to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:30287](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30287)

Creates a new CompanionMetaNonceFetchResponse instance using the specified properties.

#### Parameters

##### properties?

[`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md)

Properties to set

#### Returns

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

CompanionMetaNonceFetchResponse instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:30313](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30313)

Decodes a CompanionMetaNonceFetchResponse message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

CompanionMetaNonceFetchResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:30322](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30322)

Decodes a CompanionMetaNonceFetchResponse message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

CompanionMetaNonceFetchResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30295](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30295)

Encodes the specified CompanionMetaNonceFetchResponse message. Does not implicitly [verify](CompanionMetaNonceFetchResponse.md#verify) messages.

#### Parameters

##### message

[`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md)

CompanionMetaNonceFetchResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30303](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30303)

Encodes the specified CompanionMetaNonceFetchResponse message, length delimited. Does not implicitly [verify](CompanionMetaNonceFetchResponse.md#verify) messages.

#### Parameters

##### message

[`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md)

CompanionMetaNonceFetchResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:30336](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30336)

Creates a CompanionMetaNonceFetchResponse message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

CompanionMetaNonceFetchResponse

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:30357](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30357)

Gets the default type url for CompanionMetaNonceFetchResponse

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

Defined in: [WAProto/index.d.ts:30344](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30344)

Creates a plain object from a CompanionMetaNonceFetchResponse message. Also converts values to other types if specified.

#### Parameters

##### message

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

CompanionMetaNonceFetchResponse

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30329](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L30329)

Verifies a CompanionMetaNonceFetchResponse message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
