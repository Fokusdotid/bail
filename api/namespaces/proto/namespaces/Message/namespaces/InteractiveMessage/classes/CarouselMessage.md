# Class: CarouselMessage

Defined in: [WAProto/index.d.ts:25205](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25205)

Represents a CarouselMessage.

## Implements

- [`ICarouselMessage`](../interfaces/ICarouselMessage.md)

## Constructors

### new CarouselMessage()

> **new CarouselMessage**(`properties`?): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:25211](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25211)

Constructs a new CarouselMessage.

#### Parameters

##### properties?

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

Properties to set

#### Returns

[`CarouselMessage`](CarouselMessage.md)

## Properties

### cards

> **cards**: [`IInteractiveMessage`](../../../interfaces/IInteractiveMessage.md)[]

Defined in: [WAProto/index.d.ts:25214](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25214)

CarouselMessage cards.

#### Implementation of

[`ICarouselMessage`](../interfaces/ICarouselMessage.md).[`cards`](../interfaces/ICarouselMessage.md#cards)

***

### messageVersion?

> `optional` **messageVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:25217](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25217)

CarouselMessage messageVersion.

#### Implementation of

[`ICarouselMessage`](../interfaces/ICarouselMessage.md).[`messageVersion`](../interfaces/ICarouselMessage.md#messageversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25287](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25287)

Converts this CarouselMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:25224](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25224)

Creates a new CarouselMessage instance using the specified properties.

#### Parameters

##### properties?

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

Properties to set

#### Returns

[`CarouselMessage`](CarouselMessage.md)

CarouselMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:25250](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25250)

Decodes a CarouselMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CarouselMessage`](CarouselMessage.md)

CarouselMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:25259](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25259)

Decodes a CarouselMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CarouselMessage`](CarouselMessage.md)

CarouselMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25232](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25232)

Encodes the specified CarouselMessage message. Does not implicitly [verify](CarouselMessage.md#verify) messages.

#### Parameters

##### message

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

CarouselMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25240](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25240)

Encodes the specified CarouselMessage message, length delimited. Does not implicitly [verify](CarouselMessage.md#verify) messages.

#### Parameters

##### message

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

CarouselMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:25273](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25273)

Creates a CarouselMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CarouselMessage`](CarouselMessage.md)

CarouselMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:25294](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25294)

Gets the default type url for CarouselMessage

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

Defined in: [WAProto/index.d.ts:25281](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25281)

Creates a plain object from a CarouselMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`CarouselMessage`](CarouselMessage.md)

CarouselMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25266](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L25266)

Verifies a CarouselMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
