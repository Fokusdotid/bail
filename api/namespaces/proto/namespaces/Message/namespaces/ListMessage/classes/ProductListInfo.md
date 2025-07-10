# Class: ProductListInfo

Defined in: [WAProto/index.d.ts:27063](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27063)

Represents a ProductListInfo.

## Implements

- [`IProductListInfo`](../interfaces/IProductListInfo.md)

## Constructors

### new ProductListInfo()

> **new ProductListInfo**(`properties`?): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:27069](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27069)

Constructs a new ProductListInfo.

#### Parameters

##### properties?

[`IProductListInfo`](../interfaces/IProductListInfo.md)

Properties to set

#### Returns

[`ProductListInfo`](ProductListInfo.md)

## Properties

### businessOwnerJid?

> `optional` **businessOwnerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:27078](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27078)

ProductListInfo businessOwnerJid.

#### Implementation of

[`IProductListInfo`](../interfaces/IProductListInfo.md).[`businessOwnerJid`](../interfaces/IProductListInfo.md#businessownerjid)

***

### headerImage?

> `optional` **headerImage**: `null` \| [`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:27075](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27075)

ProductListInfo headerImage.

#### Implementation of

[`IProductListInfo`](../interfaces/IProductListInfo.md).[`headerImage`](../interfaces/IProductListInfo.md#headerimage)

***

### productSections

> **productSections**: [`IProductSection`](../interfaces/IProductSection.md)[]

Defined in: [WAProto/index.d.ts:27072](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27072)

ProductListInfo productSections.

#### Implementation of

[`IProductListInfo`](../interfaces/IProductListInfo.md).[`productSections`](../interfaces/IProductListInfo.md#productsections)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27148](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27148)

Converts this ProductListInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:27085](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27085)

Creates a new ProductListInfo instance using the specified properties.

#### Parameters

##### properties?

[`IProductListInfo`](../interfaces/IProductListInfo.md)

Properties to set

#### Returns

[`ProductListInfo`](ProductListInfo.md)

ProductListInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:27111](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27111)

Decodes a ProductListInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProductListInfo`](ProductListInfo.md)

ProductListInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:27120](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27120)

Decodes a ProductListInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProductListInfo`](ProductListInfo.md)

ProductListInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27093](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27093)

Encodes the specified ProductListInfo message. Does not implicitly [verify](ProductListInfo.md#verify) messages.

#### Parameters

##### message

[`IProductListInfo`](../interfaces/IProductListInfo.md)

ProductListInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27101](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27101)

Encodes the specified ProductListInfo message, length delimited. Does not implicitly [verify](ProductListInfo.md#verify) messages.

#### Parameters

##### message

[`IProductListInfo`](../interfaces/IProductListInfo.md)

ProductListInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:27134](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27134)

Creates a ProductListInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProductListInfo`](ProductListInfo.md)

ProductListInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:27155](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27155)

Gets the default type url for ProductListInfo

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

Defined in: [WAProto/index.d.ts:27142](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27142)

Creates a plain object from a ProductListInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProductListInfo`](ProductListInfo.md)

ProductListInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27127](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L27127)

Verifies a ProductListInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
