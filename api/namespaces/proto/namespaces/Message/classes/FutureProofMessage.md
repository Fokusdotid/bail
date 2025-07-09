# Class: FutureProofMessage

Defined in: [WAProto/index.d.ts:23422](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23422)

Represents a FutureProofMessage.

## Implements

- [`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

## Constructors

### new FutureProofMessage()

> **new FutureProofMessage**(`properties`?): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:23428](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23428)

Constructs a new FutureProofMessage.

#### Parameters

##### properties?

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

Properties to set

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:23431](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23431)

FutureProofMessage message.

#### Implementation of

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md).[`message`](../interfaces/IFutureProofMessage.md#message)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:23501](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23501)

Converts this FutureProofMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:23438](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23438)

Creates a new FutureProofMessage instance using the specified properties.

#### Parameters

##### properties?

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

Properties to set

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

FutureProofMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:23464](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23464)

Decodes a FutureProofMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

FutureProofMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:23473](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23473)

Decodes a FutureProofMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

FutureProofMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23446](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23446)

Encodes the specified FutureProofMessage message. Does not implicitly [verify](FutureProofMessage.md#verify) messages.

#### Parameters

##### message

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

FutureProofMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23454](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23454)

Encodes the specified FutureProofMessage message, length delimited. Does not implicitly [verify](FutureProofMessage.md#verify) messages.

#### Parameters

##### message

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

FutureProofMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:23487](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23487)

Creates a FutureProofMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

FutureProofMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:23508](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23508)

Gets the default type url for FutureProofMessage

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

Defined in: [WAProto/index.d.ts:23495](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23495)

Creates a plain object from a FutureProofMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`FutureProofMessage`](FutureProofMessage.md)

FutureProofMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:23480](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L23480)

Verifies a FutureProofMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
