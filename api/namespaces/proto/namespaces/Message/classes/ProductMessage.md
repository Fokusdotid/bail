# Class: ProductMessage

Defined in: [WAProto/index.d.ts:32187](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32187)

Represents a ProductMessage.

## Implements

- [`IProductMessage`](../interfaces/IProductMessage.md)

## Constructors

### new ProductMessage()

> **new ProductMessage**(`properties`?): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:32193](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32193)

Constructs a new ProductMessage.

#### Parameters

##### properties?

[`IProductMessage`](../interfaces/IProductMessage.md)

Properties to set

#### Returns

[`ProductMessage`](ProductMessage.md)

## Properties

### body?

> `optional` **body**: `null` \| `string`

Defined in: [WAProto/index.d.ts:32205](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32205)

ProductMessage body.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`body`](../interfaces/IProductMessage.md#body)

***

### businessOwnerJid?

> `optional` **businessOwnerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:32199](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32199)

ProductMessage businessOwnerJid.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`businessOwnerJid`](../interfaces/IProductMessage.md#businessownerjid)

***

### catalog?

> `optional` **catalog**: `null` \| [`ICatalogSnapshot`](../namespaces/ProductMessage/interfaces/ICatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:32202](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32202)

ProductMessage catalog.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`catalog`](../interfaces/IProductMessage.md#catalog)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:32211](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32211)

ProductMessage contextInfo.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`contextInfo`](../interfaces/IProductMessage.md#contextinfo)

***

### footer?

> `optional` **footer**: `null` \| `string`

Defined in: [WAProto/index.d.ts:32208](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32208)

ProductMessage footer.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`footer`](../interfaces/IProductMessage.md#footer)

***

### product?

> `optional` **product**: `null` \| [`IProductSnapshot`](../namespaces/ProductMessage/interfaces/IProductSnapshot.md)

Defined in: [WAProto/index.d.ts:32196](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32196)

ProductMessage product.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`product`](../interfaces/IProductMessage.md#product)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32281](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32281)

Converts this ProductMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:32218](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32218)

Creates a new ProductMessage instance using the specified properties.

#### Parameters

##### properties?

[`IProductMessage`](../interfaces/IProductMessage.md)

Properties to set

#### Returns

[`ProductMessage`](ProductMessage.md)

ProductMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:32244](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32244)

Decodes a ProductMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProductMessage`](ProductMessage.md)

ProductMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:32253](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32253)

Decodes a ProductMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProductMessage`](ProductMessage.md)

ProductMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32226](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32226)

Encodes the specified ProductMessage message. Does not implicitly [verify](ProductMessage.md#verify) messages.

#### Parameters

##### message

[`IProductMessage`](../interfaces/IProductMessage.md)

ProductMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32234](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32234)

Encodes the specified ProductMessage message, length delimited. Does not implicitly [verify](ProductMessage.md#verify) messages.

#### Parameters

##### message

[`IProductMessage`](../interfaces/IProductMessage.md)

ProductMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:32267](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32267)

Creates a ProductMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProductMessage`](ProductMessage.md)

ProductMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:32288](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32288)

Gets the default type url for ProductMessage

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

Defined in: [WAProto/index.d.ts:32275](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32275)

Creates a plain object from a ProductMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProductMessage`](ProductMessage.md)

ProductMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32260](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L32260)

Verifies a ProductMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
