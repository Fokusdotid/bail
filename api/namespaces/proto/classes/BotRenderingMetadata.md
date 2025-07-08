# Class: BotRenderingMetadata

Defined in: [WAProto/index.d.ts:6831](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6831)

Represents a BotRenderingMetadata.

## Implements

- [`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md)

## Constructors

### new BotRenderingMetadata()

> **new BotRenderingMetadata**(`properties`?): [`BotRenderingMetadata`](BotRenderingMetadata.md)

Defined in: [WAProto/index.d.ts:6837](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6837)

Constructs a new BotRenderingMetadata.

#### Parameters

##### properties?

[`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md)

Properties to set

#### Returns

[`BotRenderingMetadata`](BotRenderingMetadata.md)

## Properties

### keywords

> **keywords**: [`IKeyword`](../namespaces/BotRenderingMetadata/interfaces/IKeyword.md)[]

Defined in: [WAProto/index.d.ts:6840](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6840)

BotRenderingMetadata keywords.

#### Implementation of

[`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md).[`keywords`](../interfaces/IBotRenderingMetadata.md#keywords)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6910](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6910)

Converts this BotRenderingMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotRenderingMetadata`](BotRenderingMetadata.md)

Defined in: [WAProto/index.d.ts:6847](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6847)

Creates a new BotRenderingMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md)

Properties to set

#### Returns

[`BotRenderingMetadata`](BotRenderingMetadata.md)

BotRenderingMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotRenderingMetadata`](BotRenderingMetadata.md)

Defined in: [WAProto/index.d.ts:6873](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6873)

Decodes a BotRenderingMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotRenderingMetadata`](BotRenderingMetadata.md)

BotRenderingMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotRenderingMetadata`](BotRenderingMetadata.md)

Defined in: [WAProto/index.d.ts:6882](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6882)

Decodes a BotRenderingMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotRenderingMetadata`](BotRenderingMetadata.md)

BotRenderingMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6855](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6855)

Encodes the specified BotRenderingMetadata message. Does not implicitly [verify](BotRenderingMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md)

BotRenderingMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6863](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6863)

Encodes the specified BotRenderingMetadata message, length delimited. Does not implicitly [verify](BotRenderingMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md)

BotRenderingMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotRenderingMetadata`](BotRenderingMetadata.md)

Defined in: [WAProto/index.d.ts:6896](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6896)

Creates a BotRenderingMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotRenderingMetadata`](BotRenderingMetadata.md)

BotRenderingMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6917](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6917)

Gets the default type url for BotRenderingMetadata

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

Defined in: [WAProto/index.d.ts:6904](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6904)

Creates a plain object from a BotRenderingMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotRenderingMetadata`](BotRenderingMetadata.md)

BotRenderingMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6889](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6889)

Verifies a BotRenderingMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
