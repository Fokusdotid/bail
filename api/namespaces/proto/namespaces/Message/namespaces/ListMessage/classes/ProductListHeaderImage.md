# Class: ProductListHeaderImage

Defined in: [WAProto/index.d.ts:26957](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L26957)

Represents a ProductListHeaderImage.

## Implements

- [`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

## Constructors

### new ProductListHeaderImage()

> **new ProductListHeaderImage**(`properties`?): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:26963](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L26963)

Constructs a new ProductListHeaderImage.

#### Parameters

##### properties?

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

Properties to set

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

## Properties

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:26969](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L26969)

ProductListHeaderImage jpegThumbnail.

#### Implementation of

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md).[`jpegThumbnail`](../interfaces/IProductListHeaderImage.md#jpegthumbnail)

***

### productId?

> `optional` **productId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26966](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L26966)

ProductListHeaderImage productId.

#### Implementation of

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md).[`productId`](../interfaces/IProductListHeaderImage.md#productid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27039](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L27039)

Converts this ProductListHeaderImage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:26976](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L26976)

Creates a new ProductListHeaderImage instance using the specified properties.

#### Parameters

##### properties?

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

Properties to set

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

ProductListHeaderImage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:27002](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L27002)

Decodes a ProductListHeaderImage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

ProductListHeaderImage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:27011](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L27011)

Decodes a ProductListHeaderImage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

ProductListHeaderImage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26984](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L26984)

Encodes the specified ProductListHeaderImage message. Does not implicitly [verify](ProductListHeaderImage.md#verify) messages.

#### Parameters

##### message

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

ProductListHeaderImage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26992](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L26992)

Encodes the specified ProductListHeaderImage message, length delimited. Does not implicitly [verify](ProductListHeaderImage.md#verify) messages.

#### Parameters

##### message

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

ProductListHeaderImage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:27025](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L27025)

Creates a ProductListHeaderImage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

ProductListHeaderImage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:27046](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L27046)

Gets the default type url for ProductListHeaderImage

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

Defined in: [WAProto/index.d.ts:27033](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L27033)

Creates a plain object from a ProductListHeaderImage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProductListHeaderImage`](ProductListHeaderImage.md)

ProductListHeaderImage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27018](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L27018)

Verifies a ProductListHeaderImage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
