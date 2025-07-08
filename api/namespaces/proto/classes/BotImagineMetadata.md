# Class: BotImagineMetadata

Defined in: [WAProto/index.d.ts:3996](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L3996)

Represents a BotImagineMetadata.

## Implements

- [`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md)

## Constructors

### new BotImagineMetadata()

> **new BotImagineMetadata**(`properties`?): [`BotImagineMetadata`](BotImagineMetadata.md)

Defined in: [WAProto/index.d.ts:4002](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4002)

Constructs a new BotImagineMetadata.

#### Parameters

##### properties?

[`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md)

Properties to set

#### Returns

[`BotImagineMetadata`](BotImagineMetadata.md)

## Properties

### imagineType?

> `optional` **imagineType**: `null` \| [`ImagineType`](../namespaces/BotImagineMetadata/enumerations/ImagineType.md)

Defined in: [WAProto/index.d.ts:4005](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4005)

BotImagineMetadata imagineType.

#### Implementation of

[`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md).[`imagineType`](../interfaces/IBotImagineMetadata.md#imaginetype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4075](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4075)

Converts this BotImagineMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotImagineMetadata`](BotImagineMetadata.md)

Defined in: [WAProto/index.d.ts:4012](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4012)

Creates a new BotImagineMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md)

Properties to set

#### Returns

[`BotImagineMetadata`](BotImagineMetadata.md)

BotImagineMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotImagineMetadata`](BotImagineMetadata.md)

Defined in: [WAProto/index.d.ts:4038](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4038)

Decodes a BotImagineMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotImagineMetadata`](BotImagineMetadata.md)

BotImagineMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotImagineMetadata`](BotImagineMetadata.md)

Defined in: [WAProto/index.d.ts:4047](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4047)

Decodes a BotImagineMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotImagineMetadata`](BotImagineMetadata.md)

BotImagineMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4020](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4020)

Encodes the specified BotImagineMetadata message. Does not implicitly [verify](BotImagineMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md)

BotImagineMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4028](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4028)

Encodes the specified BotImagineMetadata message, length delimited. Does not implicitly [verify](BotImagineMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md)

BotImagineMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotImagineMetadata`](BotImagineMetadata.md)

Defined in: [WAProto/index.d.ts:4061](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4061)

Creates a BotImagineMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotImagineMetadata`](BotImagineMetadata.md)

BotImagineMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4082](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4082)

Gets the default type url for BotImagineMetadata

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

Defined in: [WAProto/index.d.ts:4069](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4069)

Creates a plain object from a BotImagineMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotImagineMetadata`](BotImagineMetadata.md)

BotImagineMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:4054](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L4054)

Verifies a BotImagineMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
