# Class: BotSourcesMetadata

Defined in: [WAProto/index.d.ts:7148](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7148)

Represents a BotSourcesMetadata.

## Implements

- [`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md)

## Constructors

### new BotSourcesMetadata()

> **new BotSourcesMetadata**(`properties`?): [`BotSourcesMetadata`](BotSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:7154](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7154)

Constructs a new BotSourcesMetadata.

#### Parameters

##### properties?

[`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md)

Properties to set

#### Returns

[`BotSourcesMetadata`](BotSourcesMetadata.md)

## Properties

### sources

> **sources**: [`IBotSourceItem`](../namespaces/BotSourcesMetadata/interfaces/IBotSourceItem.md)[]

Defined in: [WAProto/index.d.ts:7157](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7157)

BotSourcesMetadata sources.

#### Implementation of

[`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md).[`sources`](../interfaces/IBotSourcesMetadata.md#sources)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7227](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7227)

Converts this BotSourcesMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotSourcesMetadata`](BotSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:7164](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7164)

Creates a new BotSourcesMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md)

Properties to set

#### Returns

[`BotSourcesMetadata`](BotSourcesMetadata.md)

BotSourcesMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotSourcesMetadata`](BotSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:7190](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7190)

Decodes a BotSourcesMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotSourcesMetadata`](BotSourcesMetadata.md)

BotSourcesMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotSourcesMetadata`](BotSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:7199](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7199)

Decodes a BotSourcesMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotSourcesMetadata`](BotSourcesMetadata.md)

BotSourcesMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7172](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7172)

Encodes the specified BotSourcesMetadata message. Does not implicitly [verify](BotSourcesMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md)

BotSourcesMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7180](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7180)

Encodes the specified BotSourcesMetadata message, length delimited. Does not implicitly [verify](BotSourcesMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md)

BotSourcesMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotSourcesMetadata`](BotSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:7213](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7213)

Creates a BotSourcesMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotSourcesMetadata`](BotSourcesMetadata.md)

BotSourcesMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7234](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7234)

Gets the default type url for BotSourcesMetadata

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

Defined in: [WAProto/index.d.ts:7221](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7221)

Creates a plain object from a BotSourcesMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotSourcesMetadata`](BotSourcesMetadata.md)

BotSourcesMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7206](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7206)

Verifies a BotSourcesMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
