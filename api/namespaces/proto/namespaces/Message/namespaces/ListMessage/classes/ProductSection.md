# Class: ProductSection

Defined in: [WAProto/index.d.ts:27169](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27169)

Represents a ProductSection.

## Implements

- [`IProductSection`](../interfaces/IProductSection.md)

## Constructors

### new ProductSection()

> **new ProductSection**(`properties`?): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:27175](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27175)

Constructs a new ProductSection.

#### Parameters

##### properties?

[`IProductSection`](../interfaces/IProductSection.md)

Properties to set

#### Returns

[`ProductSection`](ProductSection.md)

## Properties

### products

> **products**: [`IProduct`](../interfaces/IProduct.md)[]

Defined in: [WAProto/index.d.ts:27181](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27181)

ProductSection products.

#### Implementation of

[`IProductSection`](../interfaces/IProductSection.md).[`products`](../interfaces/IProductSection.md#products)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:27178](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27178)

ProductSection title.

#### Implementation of

[`IProductSection`](../interfaces/IProductSection.md).[`title`](../interfaces/IProductSection.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27251](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27251)

Converts this ProductSection to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:27188](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27188)

Creates a new ProductSection instance using the specified properties.

#### Parameters

##### properties?

[`IProductSection`](../interfaces/IProductSection.md)

Properties to set

#### Returns

[`ProductSection`](ProductSection.md)

ProductSection instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:27214](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27214)

Decodes a ProductSection message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProductSection`](ProductSection.md)

ProductSection

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:27223](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27223)

Decodes a ProductSection message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProductSection`](ProductSection.md)

ProductSection

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27196](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27196)

Encodes the specified ProductSection message. Does not implicitly [verify](ProductSection.md#verify) messages.

#### Parameters

##### message

[`IProductSection`](../interfaces/IProductSection.md)

ProductSection message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27204](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27204)

Encodes the specified ProductSection message, length delimited. Does not implicitly [verify](ProductSection.md#verify) messages.

#### Parameters

##### message

[`IProductSection`](../interfaces/IProductSection.md)

ProductSection message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:27237](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27237)

Creates a ProductSection message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProductSection`](ProductSection.md)

ProductSection

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:27258](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27258)

Gets the default type url for ProductSection

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

Defined in: [WAProto/index.d.ts:27245](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27245)

Creates a plain object from a ProductSection message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProductSection`](ProductSection.md)

ProductSection

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27230](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L27230)

Verifies a ProductSection message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
