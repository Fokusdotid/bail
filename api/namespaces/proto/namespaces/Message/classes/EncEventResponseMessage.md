# Class: EncEventResponseMessage

Defined in: [WAProto/index.d.ts:22550](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22550)

Represents an EncEventResponseMessage.

## Implements

- [`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md)

## Constructors

### new EncEventResponseMessage()

> **new EncEventResponseMessage**(`properties`?): [`EncEventResponseMessage`](EncEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:22556](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22556)

Constructs a new EncEventResponseMessage.

#### Parameters

##### properties?

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md)

Properties to set

#### Returns

[`EncEventResponseMessage`](EncEventResponseMessage.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:22565](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22565)

EncEventResponseMessage encIv.

#### Implementation of

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md).[`encIv`](../interfaces/IEncEventResponseMessage.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:22562](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22562)

EncEventResponseMessage encPayload.

#### Implementation of

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md).[`encPayload`](../interfaces/IEncEventResponseMessage.md#encpayload)

***

### eventCreationMessageKey?

> `optional` **eventCreationMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:22559](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22559)

EncEventResponseMessage eventCreationMessageKey.

#### Implementation of

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md).[`eventCreationMessageKey`](../interfaces/IEncEventResponseMessage.md#eventcreationmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:22635](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22635)

Converts this EncEventResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EncEventResponseMessage`](EncEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:22572](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22572)

Creates a new EncEventResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md)

Properties to set

#### Returns

[`EncEventResponseMessage`](EncEventResponseMessage.md)

EncEventResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EncEventResponseMessage`](EncEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:22598](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22598)

Decodes an EncEventResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EncEventResponseMessage`](EncEventResponseMessage.md)

EncEventResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EncEventResponseMessage`](EncEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:22607](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22607)

Decodes an EncEventResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EncEventResponseMessage`](EncEventResponseMessage.md)

EncEventResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22580](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22580)

Encodes the specified EncEventResponseMessage message. Does not implicitly [verify](EncEventResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md)

EncEventResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22588](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22588)

Encodes the specified EncEventResponseMessage message, length delimited. Does not implicitly [verify](EncEventResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md)

EncEventResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EncEventResponseMessage`](EncEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:22621](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22621)

Creates an EncEventResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EncEventResponseMessage`](EncEventResponseMessage.md)

EncEventResponseMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:22642](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22642)

Gets the default type url for EncEventResponseMessage

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

Defined in: [WAProto/index.d.ts:22629](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22629)

Creates a plain object from an EncEventResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EncEventResponseMessage`](EncEventResponseMessage.md)

EncEventResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:22614](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L22614)

Verifies an EncEventResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
